<p align = "center">
  <img src="https://github.com/miguelsrrobo/Interpretador_em_rust/blob/main/banner.png" alt="Rinha logo" width="200%" />
</p>

# Interpretador em rust para o Rinha de compiladores

Esse projeto é uma implementação para a primeira [Rinha de Compiladores](https://github.com/aripiprazole/rinha-de-compiler/tree/main).

# Live

A primeira versão funcional do interpretador foi feita em uma live stream do Navarro:
[![Rinha de Compiladores em Rust](.github/live.png)](https://www.youtube.com/live/FbCdhicY3sk)
https://www.youtube.com/live/FbCdhicY3sk

# Introdução

O ideal da rinha é fazer um interpretador ou compilador que rode em uma maquina com 2 núcleos e 2G de RAM.

O interpretador ou compilador deve trabalhar com "árvore sintática abstrata" que está armazenada no formato JSON. Essa árvore sintática abstrata foi gerada pelos organizadores do Rinha usando uma ferramenta específica disponível no repositorio do [Rinha de Compiladores](https://github.com/aripiprazole/rinha-de-compiler/tree/main)..

A responsabilidade na tarefa é receber esse JSON que contém a árvore abstrata e, em seguida, interpretar ou compilar o programa de acordo com as informações fornecidas na árvore abstrata.

Simplificando:

* Foi disponibilizado um JSON com uma árvore dentro
* Foi roda o JSON

# Como foi testado

Para testar o programa foi usado o arquivo files/fib.rinha e gerar com o programa que foi disponibilizado para um JSON ou poderia usar diretamente o JSON que está em files/fib.json.
