# Teste de conhecimento full stack

![bug](https://picode-public.s3.amazonaws.com/undraw_fixing_bugs_w7gi.svg)

Olá, neste projeto iremos avaliar seu conhecimento em desenvolvimento web.
Seu objetivo será criar uma aplicação, para que uma biblioteca escolar consiga ter um melhor controle sobre os livros que estão em posse dos alunos.

## Front-end

### **Página para listagem de livros**

A página deve conter um input para realizar busca de livros, a busca pode ser feita por título e autor.

Cada registro nessa página deve conter informações sobre o estado do livro. Tais como:

- Quantidade de exemplares em posse de alunos, disponíveis e total.
- Título.
- Autor.
- Quantidade de paǵinas.

Ao clicar em um registro, deve surgir um modal para edição. O usuário deve conseguir editar as seguintes informações:

- Título do livro
- Nome do autor
- Quantidade de exemplares
- Quantidade de páginas
- Quantidade de exemplares em posse de alunos

Essa página também precisa ter a opção de **cadastrar** um novo livro, as informações necessárias para criar um novo registro são.

- Título do livro
- Nome do autor
- Quantidade de exemplares
- Quantidade de páginas

_(Sugestão: Componentize e reutilize o modal de edição)_

---

## Back-end

### **End-points**

Para este projeto, a API precisa conter apenas 4 endpoints.

- `POST /book` _- Cadastra um novo livro._
- `GET /books` _- Lista os livros cadastrados._
- `PATCH /book/:id` _- Atualiza o livro com o id correspondente._
- `DELETE /book/:id` _- Remove o livro com o id correspondente._

### **Regras de negócio**

- Não pode haver mais de um livro com o mesmo nome

**_OBS_: Faça tratamento de erros.**

---

## Extra

Essa parte não é obrigatória, mas será um diferencial se você implementar.

- Cadastro de alunos
- Vínculo entre livro e aluno
- Histórico de todos alunos que já estiveram o livro.
- Design responsivo para mobile

---

**_Sugerimos que utilize as seguintes tecnologias:_**

### **Front-end**

- [ReactJS](https://reactjs.org/)
- [NextJS](https://nextjs.org/)
- [Styled Components](https://styled-components.com/)

### **Back-end**

- [NodeJS](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [PostgreSQL](https://www.postgresql.org/)

### Utilize **[TypeScript](https://www.typescriptlang.org/)**

---

## O que será avaliado?

- A legibilidade do seu código
- Sua capacidade de abstrair e estruturar suas funções e componentes.
- A sua entrega de acordo com o prazo e funcionalidades propostas.

**Ao finalizar, crie um repositório público no github com o projeto, e envie o link para o nosso email: `devs@picode.com.br` com o assunto _Desafio full stack_.**

**Faça o seu melhor e não se preocupe em deixar tudo perfeito, nós não esperamos isso.**

**Seja criativo com o design, pense na UX, lembre-se que é uma aplicação para uma biblioteca escolar...**

**Boa sorte !!**

![logo](https://picode-public.s3.amazonaws.com/picode-logo.svg)
