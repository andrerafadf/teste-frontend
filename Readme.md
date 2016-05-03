# Seja bem-vindo(a) ao teste de front-end.

## Preparando o ambiente

- Localize a pasta "Projetos" em sua área de trabalho. Nela, clone o projeto "Teste frontend" localizado [aqui](http://10.61.201.6:7990/projects/DEM/repos/teste-frontend/browse):

    Utilize a senha "123456";

- Na pasta frontend instale as dependências do projeto com o comando `npm install`;

    Após o término do download das dependências, podem existir mensagens `WARN`, mas não se assuste. Aguarde o término da instalação, o que pode demorar um pouco.

- Enquanto as dependências estão sendo instaladas, entre no site do Bootstrap e faça o download do framework. Então, adicione os arquivos em pastas organizadas dentro do projeto;

- Quando as dependências estiverem instaladas utilize o comando `npm start`. O Chrome abrirá na página `localhost:3000`, que será sua página frontend.



- O servidor backend estará em `localhost:8000`, as respostas das requisições estão todas em JSON. Na rota `/csrf` você encontrará um token, que deverá estar em todos os formulários do projeto com o nome de `_token` ou as requisições serão rejeitadas;

- As seguintes rotas estão disponíveis:

	- `POST: /post` _Salva um post_;
	- `GET: /posts` _Recupera todos os posts_;
	- `GET: /post/{id}` _Recupera as informações de um post_;
	- `PUT: /post/{id}` _Altera as informações de um post_;
	- `DELETE: /post/{id}` _Exclui o post_.

Obs.: Considere "{id}" como um índice numérico.

*Utilizando as informações acima, suas missão é desenvolver um blog simples. Sinta-se a vontade para criar, use sua imaginação. Em caso de dúvidas, não hesite em chamar. Aqui todo conhecimento é compartilhado e o trabalho feito em equipe. \o/*

___
### E aí, vamos começar?

- Crie um branch no git chamado `teste_frontend`.
- Desenvolva o layout do blog;
- Desenvolva o tema do blog;
- Deve ser possível criar, editar, deletar e listar os posts do blog;
- Envie o branch para o repositório remoto.