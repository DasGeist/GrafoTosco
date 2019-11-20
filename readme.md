# Visualizador simples de grafos

Essa é uma coleção de gambiarras que usei para visualisar alguns grafos para um certo projeto.

Agora são gambiarras públicas.

Use por sua conta e risco.

Como usar:

* Baixe a página principal/clone o repositório.
* Substitua a definição da variável conn=[alguma array] por uma especificação do seu grafo no seguinte formato:
    *  conn=[[nó],[nó],[nó]]
    * nó = ["nome do nó", [índice ao qual conecta, tamanho da aresta],[...],[...],...] OU
    * nó = [[...],[...],[...],...]

Exemplos:
* Lista: conn=[["a",[1,1]],["b",[0,1],[2,1]],["c",[1,1]]]
* Lista circular: conn=[["a",[1,1],[2,1]],["b",[0,1],[2,1]],["c",[1,1],[0,1]]]