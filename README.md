# ATIVIDADES-PHP

QUESTÃO 01 –  Crie uma página php simples que percorra números do  número 1 ao número 100. Ao abrir a página a mesma deve imprimir quais  números são múltiplos de 3, quais números são múltiplos 5 e quais números são múltiplos de 3 e 5.

QUESTÃO 02 -  Crie uma página PHP onde o usuário precisa informar um número qualquer. O código deve retornar se o número digitado é par ou ímpar.

QUESTÃO 03 –  Crie uma página PHP onde o usuário digite uma palavra ou texto. Retorne em tela a quantidade de caracteres que a string digitada possui.

QUESTÃO 04 -  Crie uma página PHP que contenha uma calculadora simples. O usuário deverá informar os elementos a serem manipulados e  escolher dentre as ações de soma, subtração, divisão, multiplicação e raiz quadrada. O resultado da operação matemática deve ser exibido em tela.

QUESTÃO 05 –  Utilizando o código desenvolvido no Trabalho Pratico II, faça a tratativa do formulário de feedback no PHP e exiba em tela os dados coletados do usuário.

QUESTÃO 06 -  utilizando o Trabalho Prático III realize as seguintes ações:
• Ao salvar um post, grave suas informações no banco. - INSERT
• Ao curtir uma publicação marque-a como curtida no banco de dados 
(coluna curtida 0 = Não, 1 = Sim). – UPDATE
• Ao excluir uma publicação, exclua-a do banco. – DELETE
• Ao carregar a página, se houver publicações salvas, exiba-as em tela -

SELECT
ESQUEMA DO BANCO
CREATE DATABASE IF NOT EXISTS xuitter_db;
USE xuitter_db;
CREATE TABLE IF NOT EXISTS publicacoes (
 id INT AUTO_INCREMENT PRIMARY KEY,
 texto VARCHAR (255) NOT NULL,
 data_criacao TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
 curtida BOOLEAN DEFAULT FALSE
);
