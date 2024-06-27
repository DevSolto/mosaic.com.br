
# Mosaic

Mosaic é uma aplicação completa de gerenciamento de projetos colaborativos, projetada para facilitar o acompanhamento do progresso de projetos e tarefas por equipes de estudantes e profissionais. A aplicação consiste em um backend robusto construído com Fastify, Prisma, TypeScript e JWT para autenticação segura, bem como um frontend responsivo utilizando Next.js e Tailwind CSS.

## Índice

- [Instalação](#instalação)
- [Configuração](#configuração)
- [Uso](#uso)
- [Backend](#backend)
- [Frontend](#frontend)
- [Mobile](#mobile)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Milestones](#milestones)

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/mosaic.git
   cd mosaic
   ```

## Configuração

### Backend

1. Navegue até o diretório do backend:
   ```bash
   cd backend
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Crie um arquivo `.env` na raiz do backend e adicione as variáveis de ambiente necessárias:
   ```dotenv
   DATABASE_URL="postgresql://user:password@localhost:5432/mydatabase"
   JWT_SECRET="seu_segredo_super_secreto"
   ```

4. Configure o Prisma e execute as migrações:
   ```bash
   npx prisma migrate dev --name init
   ```

5. Inicie o servidor backend:
   ```bash
   npm run dev
   ```

### Frontend

1. Navegue até o diretório do frontend:
   ```bash
   cd frontend
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Crie um arquivo `.env.local` na raiz do frontend e adicione as variáveis de ambiente necessárias:
   ```dotenv
   NEXT_PUBLIC_API_URL=http://localhost:3000
   ```

4. Inicie o servidor de desenvolvimento do frontend:
   ```bash
   npm run dev
   ```

O frontend estará rodando em `http://localhost:3000`.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

1. Fork este repositório.
2. Crie um branch para sua feature ou correção de bug (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`).
4. Push para o branch (`git push origin feature/nova-feature`).
5. Abra um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
