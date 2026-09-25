# Sistema Biblioteca (2021)

[Conheça meu portfólio e minha trajetória profissional](PORTFOLIO.md) · [LinkedIn](https://www.linkedin.com/in/danilo-silva-campos-1b7609109/)

Projeto acadêmico de gestão de biblioteca desenvolvido em Python e Django. O código preserva a estrutura original para mostrar modelagem e organização da aplicação; não representa uma versão pronta para produção em 2026.

## Funcionalidades presentes no código

- Cadastro de obras, autores e categorias.
- Cadastro de usuários, tipos de usuário e períodos.
- Registro de empréstimos com data de empréstimo e retorno.
- Autenticação e área administrativa com páginas HTML.

## Estrutura

- `acervo/`: modelos, rotas, visualizações e páginas do catálogo.
- `usuarios/`: cadastro e classificação de usuários.
- `emprestimos/`: registros e páginas de empréstimo.
- `home/`: entrada, autenticação e layout.
- `bibliotecaProjectQA/`: configuração e rotas gerais.

## Tecnologias e limites

A versão original usava Django 2.1.15 e SQL Server por meio de `sql_server.pyodbc`. O projeto depende de pacotes e arquivos estáticos de terceiros presentes no ambiente original, que não acompanham esta publicação. Por isso, não apresento o código como instalação executável imediata. Uma atualização exigiria revisar dependências, autenticação, testes e configuração do banco.

As credenciais do material de 2021 foram removidas. A configuração lê `DJANGO_SECRET_KEY`, `DB_HOST`, `DB_USER` e `DB_PASSWORD` do ambiente. O banco de dados e o ambiente virtual não foram publicados.
