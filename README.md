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

O seu interpretador ou compilador deve trabalhar com algo chamado "árvore sintática abstrata" que está armazenada no formato JSON. Essa árvore sintática abstrata será gerada por nós usando uma ferramenta específica disponível neste repositório.

Sua responsabilidade na tarefa é receber esse JSON que contém a árvore abstrata e, em seguida, interpretar ou compilar o programa de acordo com as informações fornecidas na árvore abstrata.

Simplificando:

* Nós te damos um JSON com uma árvore dentro
* Voce roda o JSON
* Voce fica feliz que apareceu o resultado.


