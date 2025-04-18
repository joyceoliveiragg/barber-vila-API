# Barbearia da Vila - API

Este repositório contém o backend do projeto **Barbearia da Vila**, uma API REST desenvolvida com **Spring Boot** e **Gradle**.

Este projeto faz parte do curso oferecido pela **Digital Innovation One (DIO)** dentro do programa **Decola Tech**, com foco em desenvolvimento Full Stack com Java e Angular.

---

## 📦 Estrutura do Projeto

O backend está localizado na pasta:

```
barbearia-da-vila/
└── backend/
    └── barber-shop-api-master/
```

---

## 🚀 Como rodar o projeto

### 🔧 Pré-requisitos

- Docker e Docker Compose instalados
- Porta `8080` (API) e `5432` (PostgreSQL) liberadas

---

### 🐳 Usando Docker Compose

1. Acesse a raiz do projeto onde se encontra o `docker-compose.yml`

2. Suba os containers com:

```bash
docker-compose up --build
```

3. A aplicação estará disponível em: [http://localhost:8080](http://localhost:8080)

O banco de dados estará disponível no serviço `db`, com as seguintes credenciais:

- **Usuário**: `vilabarber-shop-api`
- **Senha**: `vilabarber-shop-api`
- **Banco**: `vilabarber-shop-api`

---

### 🛠 Rodando localmente sem Docker

1. Acesse a pasta do backend:
```bash
cd barber-shop-api-master
```

2. Dê permissão ao Gradle wrapper (Linux/macOS):
```bash
chmod +x gradlew
```

3. Rode a aplicação:
```bash
./gradlew bootRun
```

4. A API estará disponível em: [http://localhost:8080](http://localhost:8080)

---

## 🧪 Testando

Você pode utilizar o [Postman](https://www.postman.com/) ou [Insomnia](https://insomnia.rest/) para testar os endpoints da API.

---

## 💡 Sugestões de melhorias

- Implementar autenticação com JWT
- Adicionar testes unitários com JUnit
- Documentar a API com Swagger/OpenAPI
- Configurar deploy automatizado com GitHub Actions

---

## 📄 Licença

Este projeto foi desenvolvido com fins educacionais para o programa **Decola Tech** da DIO e é uma adaptação do projeto original da Digital Innovation One com o tema de barbearia.
