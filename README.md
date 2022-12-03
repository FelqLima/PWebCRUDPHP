# PWebCRUDPHP
Unipê 2022.2 SPI
Programação Web, CRUD em PHP

Felipe Quaresma
RGM 31170234.


--========================--


Banco de dados para teste:

CREATE DATABASE aulaprogweb;

USE aulaprogweb;

CREATE TABLE tab_pessoa (
    cod_pessoa int not null Primary Key AUTO_INCREMENT,
    nome varchar(100),
    cpf varchar(14),
    email varchar(50)
);
