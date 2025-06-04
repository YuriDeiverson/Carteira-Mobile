# 💸 Finanças Pessoais App

Aplicativo mobile para gerenciamento de transações financeiras, com autenticação segura, backend em produção e banco de dados na nuvem.

## 📱 Tecnologias Utilizadas

### Frontend (Mobile)
- **React Native** (Expo)
- **TypeScript**
- **Clerk** para autenticação
- **FlatList** e **ScrollView** para renderização de listas
- **Hooks personalizados** para gerenciamento de transações

### Backend (API)
- **Node.js + TypeScript**
- **Drizzle ORM** (row-based SQL)
- **Banco de Dados Neon (PostgreSQL)**
- **Clerk Auth Middleware**

## 🔐 Funcionalidades

- Login e autenticação com Clerk
- Cadastro de transações (entrada/saída)
- Exibição de saldo atual
- Listagem de transações por usuário
- Exclusão de transações com confirmação
- Resumo financeiro por usuário

## 📦 Estrutura do Projeto

📁 app/

├── api/

│ └── transactions/

│ ├── create.ts

│ ├── get.ts

│ └── route.ts

├── hooks/

│ └── useTransactions.ts

├── components/

│ ├── BalanceCard.tsx

│ ├── TransactionItem.tsx

│ └── PageLoader.tsx

├── pages/

│ ├── index.tsx

│ └── create.tsx