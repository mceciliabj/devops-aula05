# Arquitetura

* As funções relacionadas ao gerenciamento das casas do
jogo da velha ficarão no módulo **jogovelha.py**.

* O estado de cada casa do jogo será representada por uma 
string: "." para casa vazia; "X" para casa ocupada pelo 1º
jogador; "O" ára casa ocupada pelo 2º jogdador

* A função inicializar () retornará uma lista 3x3, onde cada
posição conterá uma string para indicar o estado de uma 
casa do jogo. A função retornará todoas as casas 
inicialmente vazias. 