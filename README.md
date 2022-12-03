<h1 align="center">
  Rocketnotes API
</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-instalação-e-execução">Instalação e Execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-deploy">Deploy</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- JavaScript
- NodeJS
- Express
- SQlite

## 💻 Projeto

Essa API foi desenvolvida para suprir de Back-end da aplicação [Rocketnotes](https://github.com/AlanRehfeldt/ExplorerStage09-Rocketnotes).

### ⚙️ Recursos da API

- [x] Cadastro e autenticação de usuários com geração de JwToken;
- [x] Autenticação de usuários com JwToken;
- [x] Permite usuário cadastrar-se e atualizar seu perfil (incluindo imagem de avatar);
- [x] Validação de e-mails no cadastro, não é possível cadastrar dois usuários com mesmo e-mail;
- [x] Para atualizar a senha, o usuário deve informar a senha antiga e a nova senha;
- [x] Permite o usuário cadastrar e deletar notas com links e tags;
- [x] Faz a listagem das notas com seus respectivos links e tags;
- [x] Permite o usuário fazer buscas por título de nota e tags;

## 👨‍💻 Instalação e execução

1. Abra o terminal do seu computador. 
3. Faça um clone desse repositório rodando: <br> `git clone https://github.com/AlanRehfeldt/ExplorerStage08-API_notes`;
4. Entre na pasta rodando pelo terminal: `cd ExplorerStage08-API_notes`;
5. Rode `npm i` para instalar as dependências do projeto;
6. Informar variáveis de ambiente no arquivo .env;
7. Rode `npm run dev` para iniciar o servidor de desenvolvimento;
8. Rode `npm run migrate` para criar tabelas no banco de dados.

## 🔗 Deploy
Aplicação hospedada e rodando no [Netlify](https://explorer-rocketnotes.netlify.app)

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---

Feito por Alan Rehfeldt :wave: 
