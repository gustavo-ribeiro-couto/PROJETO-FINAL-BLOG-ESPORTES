# PROJETO FINAL-BLOG-ESPORTES
<h1 align="center">BLOG-ESPORTES</h1>
<h2 align="center">Uma iniciativa tecnológica</h2>


<h3 align="center">Sobre o projeto</h3>
<br>
Projeto final do curso Programadores Cariocas, realizado em dupla, com a finalidade de implementar o aprendizado do módulo 5 em uma aplicação - um site -. O projeto em questão se chama "BLOG-ESPORTES" e foi baseado em uma iniciativa da dupla, visando a questão de propocionar o usuario a se manter imformado sobre o mundo do esporte. Portanto, optamos por criar um site interativo onde o admnistrador pode adicionar uma lenda do futebol ou até criar uma.
<br>

<div align="center">
    <h1 align="center">Passo a passo para rodar o projeto</h1>
    <br>
    

Abrir xampp e ativar o Mysql

abrir o Workbench e crie esse banco de dados

e Digitar este código;

1-create database blog_de_esporte;

2-use blog_de_esporte;

3-create table lendas(
id int primary key auto_increment not null,
nome varchar(100),
posicao varchar(100)
);

4-select * from lendas;

abra o VSCODE 

abra o terminal integrado 

coloque o comando: npm install
para baixar a pasta node_modules

logo após

coloque o comando: npm start
para iniciar o servidor: localhost:3000

para visualizar o projeto coloque no navegador e digite: localhost:3000

para visualizar o crud faça login na pagina do administrador localizada no footer da pagina.

<h3> As Rotas criadas foram</h3>

- Inicio/Home
- Brasileiros
- Futebol
- Seleções
- Varieades
- Tela de Login
- Tela de Cadastro
- Adicionar lendas
- Exibir lendas
- Editar lendas
    
    <h1>Colaboradores</h1>
    - ANA CAROLINA
    - GUSTAVO RIBEIRO <a href="https://www.linkedin.com/in/gustavo-ribeiro-a3410124a/">Acesse meu Github</a>
