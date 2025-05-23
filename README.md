# Docker Compose - MySQL e SQL Server

Este repositório contém arquivos `docker-compose.yml` prontos para subir rapidamente os bancos de dados **MySQL** e **SQL Server** em ambientes de desenvolvimento.

## 🧩 Objetivo

Facilitar o uso local dos bancos de dados, sem necessidade de instalação manual, ideal para testes e desenvolvimento.

---

## 📦 Estrutura do Repositório

```
.
├── mysql/
│   └── docker-compose.yml        # Compose para MySQL
├── sqlserver/
│   └── docker-compose.yml        # Compose para SQL Server
└── README.md                     # Este arquivo
```

---

## 🚀 Como usar

### 1. Clone o repositório

```bash
git clone https://github.com/williamsilvaec/docker-databases.git
cd docker-databases
```

### 2. Suba o banco desejado

#### MySQL

```bash
cd mysql
docker-compose up -d
```

#### SQL Server

```bash
cd sqlserver
docker-compose up -d
```

### 3. Verifique se os containers estão rodando

```bash
docker ps
```

---

## ⚙️ Requisitos

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

---

## 📝 Observações

- Os dados são persistidos em volumes locais.
- As portas padrão e credenciais podem ser personalizadas nos arquivos `docker-compose`.
- Ideal para desenvolvedores que precisam subir rapidamente um ambiente com banco de dados.

---
