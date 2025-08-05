# 🏎️ Fastify F1 API

Uma API simples e modular feita com **Fastify**, simulando dados de times e pilotos de Fórmula 1. O projeto segue uma estrutura organizada com uso de **controllers** e **utils** para facilitar escalabilidade e manutenção.

---

## 📁 Estrutura do Projeto

src/
- ├── controllers/
- │ ├── driversController.ts # Rotas de pilotos
- │ └── teamsController.ts # Rotas de equipes
- ├── utils/
- │ ├── findById.ts # Busca genérica por ID
- │ ├── parse.ts # Conversão segura de valores
- │ └── response.ts # Padronização de respostas JSON
- └── server.ts # Arquivo principal do servidor


---

## 🚀 Como rodar o projeto

1. **Instale as dependências**
```bash
npm install

## Inicie o servidor

# bash
npm run dev

##📡 Rotas disponíveis

| Método | Rota           | Descrição                     |
| ------ | -------------- | ----------------------------- |
| GET    | `/teams`       | Lista todas as equipes        |
| GET    | `/drivers`     | Lista todos os pilotos        |
| GET    | `/drivers/:id` | Retorna um piloto pelo seu ID |

## 🛠️ Tecnologias utilizadas

- Fastify

- TypeScript

- Node.js
