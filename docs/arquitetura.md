#Arquitetura

* As funções relacionadas ao gerenciamento das casas do jogo da velha ficarão no modulo **jogovelha.py**

* O estado de cada casa do jogo sera representada por uma string: "." para casa vazia; "X" para casa ocupada pelo 1º jogador / "O" para casa ocupada pelo 2º jogador.

* A função inicializar() retornará uma lista 3x3, onde cada posisão contera uma string para indicar o estado de uma casa do jogo. A função retornara todas as casas inicialmente vazias.