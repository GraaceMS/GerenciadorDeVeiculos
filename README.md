CREATE DATABASE gerenciador_de_veiculos;

USE gerenciador_de_veiculos;

CREATE TABLE veiculos (
    id INT(6) UNSIGNED AUTO_INCREMENT PRIMARY KEY,
    marca VARCHAR(30) NOT NULL,
    modelo VARCHAR(30) NOT NULL,
    ano YEAR(4) NOT NULL,
    placa VARCHAR(8) NOT NULL,
    preco DECIMAL(10,2) NOT NULL
);

INSERT INTO veiculos (marca, modelo, ano, placa, preco) 
VALUES ('Ford', 'Fusion', 2018, 'ABC-1234', 95000.00);

