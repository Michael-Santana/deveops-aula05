# Arquitetura
* as funções relacionadas ao gerenciamento das casas do jogo da velha ficarão no modulo **jogovelha.py**.

* O estado de cada casa do jogo será representada por uma string: "."
para casa vazia; "X" para casa ocupada pelo 1º jogador; "o" para casa ocupada pelo 2º jogador

* A função inicializar() rernará uma lista 3x3, onde cada posição conterá uma string para indicar o estado de uma casa do jogo. A função retornará todas as casas inicialmente vazias.