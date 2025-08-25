// No painel de SQL

CREATE DATABASE cadastro;

// Depois dentro do cadastro, para criar as tabelas conforme necessidade

CREATE TABLE usuarios (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    idade INT NOT NULL,
    telefone VARCHAR(20) NOT NULL,
    email VARCHAR(100) NOT NULL
);

// SERVIDOR utilizado para rodar php - WAMP
http://localhost/phpmyadmin/