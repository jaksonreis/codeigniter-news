 ## CODE IGNITER4
 
 # Projeto

Este projeto foi desenvolvido com o intuito de buscar notícias no banco de dados MySQL e listar , permitindo tambem cadastrar novas notícias.

Este é um projeto da documentação oficial do <b>CodeIgniter 4</b>.

## Introdução ao CodeIgniter
Este projeto foi inicializado com o [Composer](https://codeigniter4.github.io/userguide/installation/installing_composer.html) .

## Tecnologias e bibliotecas usadas no desenvolvimento

[PHP](https://www.php.net/docs.php) </br>
[CodeIgniter](https://codeigniter4.github.io/userguide/index.html) </br>

## Como instalar o projeto

Baixe o projeto no github, renomeie o nome do arquivo <b>env</b> para <b>.env</b>, altere as configurações do banco de dados MYSQL, crie a tabela utilizando o comando:

CREATE TABLE news (
    id INT UNSIGNED NOT NULL AUTO_INCREMENT,
    title VARCHAR(128) NOT NULL,
    slug VARCHAR(128) NOT NULL,
    body TEXT NOT NULL,
    PRIMARY KEY (id),
    KEY slug (slug)
);

Logo após adicione o registro:

INSERT INTO news VALUES
(1,'Elvis sighted','elvis-sighted','Elvis was sighted at the Podunk internet cafe. It looked like he was writing a CodeIgniter app.'),
(2,'Say it isn\'t so!','say-it-isnt-so','Scientists conclude that some programmers have a sense of humor.'),
(3,'Caffeination, Yes!','caffeination-yes','World\'s largest coffee shop open onsite nested coffee shop for staff only.');

 e coloque os arquivos deste projeto no servidor.


<hr>


<span style="text-align:end;">Desenvoldido por <b>Jakson Reis</b>.<span>
