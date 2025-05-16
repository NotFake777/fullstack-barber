# 💈 Fullstack Barber

Projeto Fullstack para gerenciamento de barbearias, agendamento de serviços e administração de usuários.

## 🚀 Tecnologias Utilizadas

- **Next.js** (React)
- **TypeScript**
- **Prisma ORM**
- **PostgreSQL**
- **TailwindCSS**
- **NextAuth.js** (autenticação)
- **Supabase** (opcional, pode ser usado localmente)

## ⚙️ Como rodar o projeto localmente

1. **Clone o repositório**
   ```bash
   git clone https://github.com/SEU_USUARIO/fullstack-barber.git
   cd fullstack-barber
   ```

2. **Instale as dependências**
   ```bash
   npm install
   # ou
   yarn
   ```

3. **Configure o banco de dados**
   - Crie um banco PostgreSQL chamado `fullstack-barber` (ou altere o nome no `.env`).
   - Configure a variável `DATABASE_URL` no arquivo `.env`:
     ```
     DATABASE_URL=postgresql://USUARIO:SENHA@localhost:5432/fullstack-barber
     ```

4. **Rode as migrations do Prisma**
   ```bash
   npx prisma migrate dev
   ```

5. **(Opcional) Popule o banco com dados de exemplo**
   ```bash
   npx prisma db seed
   ```

6. **Inicie o servidor de desenvolvimento**
   ```bash
   npm run dev
   # ou
   yarn dev
   ```

7. **Acesse no navegador**
   ```
   http://localhost:3000
   ```

## 📝 Funcionalidades

- Cadastro e login de usuários (Google OAuth)
- Listagem de barbearias
- Busca de barbearias
- Agendamento de serviços
- Visualização de agendamentos
- Interface responsiva

## 📂 Estrutura do Projeto

- `app/` - Páginas e componentes do Next.js
- `prisma/` - Schema do banco de dados e seeds
- `app/_lib/` - Configurações do Prisma e autenticação

## 🛠️ Scripts Úteis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npx prisma migrate dev` - Aplica as migrations no banco
- `npx prisma db seed` - Popula o banco com dados de exemplo

## 📄 Licença

Este projeto está sob a licença MIT.

---

Feito com 💈 por [Seu Nome](https://github.com/SEU_USUARIO)
