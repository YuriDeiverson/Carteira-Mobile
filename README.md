# 💸 Finanças Pessoais App

Aplicativo mobile para gerenciamento de transações financeiras, com autenticação segura, backend em produção e banco de dados na nuvem.

[🔗 Protótipo UI/UX no Figma](https://www.figma.com/proto/ZxVQflfiq2Vsxk9PUti7VR/Banco-APP?node-id=0-1&t=KwrM2aodexrPRf4n-1)


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

##  🐞 Em Desenvolvimento

- Corrigir erro onde transactions retorna vazio após adição

- Migrar ScrollView de volta para FlatList quando resolvido

- Melhorar validação de entrada de dados

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
