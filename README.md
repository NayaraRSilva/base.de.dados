# base.de.dados
Criando uma tabela de dados no PGADMIN4

Abrir o programa PGADMIN 
Databases com botão direito clica CREATE - Database
Inserir nome: "BASE DE DADOS"
Clicar SAVE
Procurar nome do base: "BASE DE DADOS"
Clica com botão direito QUERY TOOL 
inserir o codigo abaixo pra criar a tabela

CREATE TABLE produtos(
codigo SERIAL, 
nome  VARCHAR (50) NOT NULL,
valor NUMERIC (10,2) NOT NULL, 
quantidade NUMERIC (10,2) NOT NULL, 
	PRIMARY KEY (codigo)
);
