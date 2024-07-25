# Ágora

## 📜 Descrição

Ágora é uma aplicação FullStack projetada para oferecer uma plataforma completa de aprendizado online. A plataforma proporciona uma experiência fluida tanto para alunos quanto para instrutores, permitindo a criação, gerenciamento e acesso a cursos de maneira eficiente.

**Nota:** [Visualização Ao Vivo](https://agora-client-azure.vercel.app/) disponível para visualização.

## 📸 Imagens do Projeto

_Exemplo da Página Home_  
<img src="https://private-user-images.githubusercontent.com/134077780/352152347-a6c22ca6-c710-498c-988a-2f087e70073e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjE5MTgxODUsIm5iZiI6MTcyMTkxNzg4NSwicGF0aCI6Ii8xMzQwNzc3ODAvMzUyMTUyMzQ3LWE2YzIyY2E2LWM3MTAtNDk4Yy05ODhhLTJmMDg3ZTcwMDczZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDcyNVQxNDMxMjVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zMzNlNzI0YWM3YWZjMTE2MzI0MjBmZTIxMjI0ZjM4MmUyYmQ4ZjhjNzEzODM1ZDU3YWRjODk0ODljNmNkNDY5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.JkfIw6tcY8iGcsGbBZ90FumMwavgc6yhaL-_x08JmUU" width="600" height="1300" alt="Página Home">

_Exemplo da Página Dashboard_  
<img src="https://private-user-images.githubusercontent.com/134077780/351864416-a3516340-8393-4c0f-9f6b-701c125956fe.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjE4NTE2NzAsIm5iZiI6MTcyMTg1MTM3MCwicGF0aCI6Ii8xMzQwNzc3ODAvMzUxODY0NDE2LWEzNTE2MzQwLTgzOTMtNGMwZi05ZjZiLTcwMWMxMjU5NTZmZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNzI0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDcyNFQyMDAyNTBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00NTQyNmE4ZDFiZTU0M2M0YzdmZTA0NjJjZTJlZmEwMjlkNWY4ODIyZjYyM2Q1OTZlZTc1ZDAyZDZiNDRlMzE5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.mTIou8VG96-NbwmAL1eEaqO4EmxgIGFjVVj2Jm-3TPw" width="600" height="400" alt="Página Dashboard">

_Exemplo da Página de Compras do Curso_  
<img src="https://private-user-images.githubusercontent.com/134077780/351869840-7bd0a3f0-c9c5-4be2-8f30-f54c7b25f4a9.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjE4NTI5MjMsIm5iZiI6MTcyMTg1MjYyMywicGF0aCI6Ii8xMzQwNzc3ODAvMzUxODY5ODQwLTdiZDBhM2YwLWM5YzUtNGJlMi04ZjMwLWY1NGM3YjI1ZjRhOS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNzI0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDcyNFQyMDIzNDNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hOTBkNzM2NDMzM2NhYmRmZWQ1ZDhhYWE2MTI0ZGRjMTRlNGQ4NjZkZjU2MTNmYTlmYTVkYTdiZTRjMTI1ZjRlJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.ILKGoorv9A8zfEqF0Gf5iac6s-67bGB8fQRKB4za5GA" width="600" height="700" alt="Página de Compras do Curso">

_Exemplo da Página para Alunos que Compraram o Curso_  
<img src="https://private-user-images.githubusercontent.com/134077780/351870162-353565ac-fc3f-48f1-ae1a-4c0ad0e3ef8e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjE5MTY4OTQsIm5iZiI6MTcyMTkxNjU5NCwicGF0aCI6Ii8xMzQwNzc3ODAvMzUxODcwMTYyLTM1MzU2NWFjLWZjM2YtNDhmMS1hZTFhLTRjMGFkMGUzZWY4ZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNzI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDcyNVQxNDA5NTRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yZjlmMGM1ZWZjZThiNjRiZDFiZGE5Yjc0Yzc1NTdiZDBmMWQyODNiOGUwMGJkNzM4NGEzOTY0MmJmNmRiMTBhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.fVJODTAnvKsfUG-Iy5t5lKAAnu63XzU80ea_RacJqJw" width="600" height="400" alt="Página do Curso">

## 🔨 Funcionalidades Principais

1. **Autenticação e Usuário**

   - Login seguro usando NextAuth.
   - Gerenciamento de perfil com upload de avatar via Cloudinary.

2. **Página Home**

   - Pesquisa de cursos com opções de filtro por categoria.
   - Exibição de cursos em destaque e feedback de alunos.
   - Área de Perguntas Frequentes (FAQ) para esclarecer dúvidas comuns.

3. **Compra e Acesso a Cursos**

   - Compra de cursos utilizando Stripe, com acesso completo a conteúdo, materiais e áreas de interação após a compra.

4. **Dashboard Administrativo**

   - Painel para administradores gerenciarem cursos, usuários e categorias, com acesso a analytics e customização.

5. **Notificações em Tempo Real**
   - Notificações imediatas para usuários usando Socket.io.

## 👩‍💻 Tecnologias Utilizadas

### Frontend

- [Next.js](https://nextjs.org/) - Framework React para renderização do lado do servidor.
- [Typescript](https://www.typescriptlang.org/) - Linguagem de programação que adiciona tipagem estática ao JavaScript.
- [RTK Query](https://redux-toolkit.js.org/rtk-query/overview) - Ferramenta para consulta de dados eficiente.
- [Socket.io](https://socket.io/) - Biblioteca para aplicações web em tempo real.
- [Redux](https://redux.js.org/) - Ferramenta de gerenciamento de estado.
- [Tailwind CSS](https://tailwindcss.com/) - Framework de CSS para estilização.
- [Material UI](https://mui.com/) - Componentes React para desenvolvimento web rápido e fácil.
- [Formik](https://formik.org/) - Biblioteca para construção de formulários em React.
- [Yup](https://github.com/jquense/yup) - Biblioteca JavaScript para validação e análise de valores.
- [Toast](https://react-hot-toast.com/) - Biblioteca de notificações para React.
- [NextAuth](https://next-auth.js.org/) - Autenticação para aplicações Next.js.
- [React Pro Sidebar](https://github.com/azouaoui-med/react-pro-sidebar) - Componente React para navegação lateral.
- [VdoCipher](https://www.vdocipher.com/) - Hospedagem e streaming de vídeos seguros.

### Backend

- [Node.js](https://nodejs.org/) - Ambiente de execução JavaScript.
- [MongoDB](https://www.mongodb.com/) - Banco de dados NoSQL.
- [Mongoose](https://mongoosejs.com/) - ODM para MongoDB.
- [Redis](https://redis.io/) - Armazenamento de estrutura de dados em memória.
- [Cloudinary](https://cloudinary.com/) - Serviço de armazenamento de mídia na nuvem.
- [Stripe](https://stripe.com/) - Plataforma de processamento de pagamentos online.

## 📁 Executando Localmente

### Backend

1. Clone o repositório:
   ```bash
   git clone https://github.com/oMiguelwnl/server.git
   cd server
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Crie um arquivo `.env` e adicione suas variáveis de ambiente:
   ```env
   PORT=8000
   ORIGIN=http://localhost:3000,
   ```
4. Inicie o servidor:
   ```bash
   npm run dev
   ```

### Frontend

1. Clone o repositório:
   ```bash
   git clone https://github.com/oMiguelwnl/agora-client.git
   cd agora-frontend
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Crie um arquivo `.env.local` e adicione suas variáveis de ambiente:
   ```env
   NEXT_PUBLIC_SERVER_URL=http://localhost:8000/api/v1/
   ```
4. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

## 🤝 Contribuindo

Contribuições são bem-vindas! Por favor, abra uma issue ou envie um pull request para quaisquer alterações.

## 👩‍💻 Desenvolvedor

<img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/134077780?v=4" width="100px;" alt="Foto do Desenvolvedor"/>

<div align="left">
  <a href="https://www.linkedin.com/in/miguel-rafael-almeida/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo"  />
  </a>
</div>
