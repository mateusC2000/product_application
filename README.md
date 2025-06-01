## 🧾 Descrição

**Product Application** — esta aplicação é composta por dois serviços principais:

- **Backend (`products_api`)**: uma API desenvolvida em Ruby on Rails, responsável pelo gerenciamento dos produtos, regras de negócio, persistência dos dados e comunicação com o banco PostgreSQL.
- **Frontend (`product-frontend`)**: uma interface moderna construída com uma ferramenta como Vite (usando React), que consome a API do backend e exibe os dados de forma interativa para o usuário final.

Ambos os serviços estão orquestrados via Docker Compose, permitindo um ambiente de desenvolvimento completo e facilmente reproduzível com apenas alguns comandos.


## 🐳 Rodando com Docker

### Suba o container:
- docker compose up

### Acesse no navegador:
- http://localhost:5173