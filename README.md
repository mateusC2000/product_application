# 🧾 Descrição

**Product Application** é composta por dois serviços principais:

- **Backend (`products_api`)**: uma API em **Ruby on Rails** responsável por gerenciar produtos, aplicar regras de negócio, persistir dados e se comunicar com o banco **PostgreSQL**.
- **Frontend (`product-frontend`)**: uma interface moderna construída com **Vite** e **React**, que consome a API e exibe os dados ao usuário de forma interativa.

Ambos os serviços são orquestrados com **Docker Compose**, facilitando a configuração e execução do ambiente com poucos comandos.

---

## 📦 Clonando o Repositório

```bash
git clone https://github.com/mateusC2000/product_application.git
cd product_application
```

## 🔄 Atualizando os Submódulos

```
git submodule update --init --recursive
```

## ⚙️ Gerando o .env para o Backend

```
cp .env.exemple ./products_api/.env
```

## 🐳 Rodando com Docker

1. Subir os containers:

```
docker compose up
```

2. Acessar a aplicação:

- Abra o navegador e acesse:

```
http://localhost:5173
```