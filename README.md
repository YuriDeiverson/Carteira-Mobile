# 💸 Finanças Pessoais App

Aplicativo mobile para gerenciamento de transações financeiras, com autenticação segura, backend em produção e banco de dados na nuvem.

<div align="center">
<img src="https://github.com/user-attachments/assets/14d4a2f5-da15-4d34-92e8-6bd8b9a25a42" width="250px"/>
<img src="https://github.com/user-attachments/assets/b7f5cd02-1cbe-4677-ac01-f23d57ee25f2" width="250px"/>
<img src="https://github.com/user-attachments/assets/ae8ce870-a486-4af1-bb96-d32701bec07e" width="250px"/>
<img src="https://github.com/user-attachments/assets/abcd70f2-da95-4534-b38f-f6cd5f528b46" width="250px"/>
<img src="https://github.com/user-attachments/assets/60fedb23-1e82-46d0-8f76-c1e11ace97ff" width="250px"/>
</div>
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
