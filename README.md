# TrabalhoGrafos

A biblioteca de grafos a ser desenvolvida deve ser capaz de representar e manipular grafos orientados.

## Implementação da representação de grafos: Listas de adjacência

Cada vértice do grafo deve armazenar um valor de tipo genérico. 

## Funcionalidades 

**A classe grafo deve prover métodos que permitam:**

+ Adicionar um vértice ao grafo: receba um objeto do tipo genérico T e, caso não exista no grafo um vértice com o valor passado, acrescente um vértice ao grafo contendo o objeto recebido;

+ Adicionar uma aresta ao grafo: receba dois objetos do tipo T (origem e destino) e um valor float, obtenha os vértices referentes aos valores passados e crie uma aresta entre os dois vértices obtidos e tendo o peso passado;

+ Calcular a árvore geradora mínima: o método deve computar a árvore geradora mínima, imprimindo na tela cada uma das arestas (vértice de origem, vértice de destino e peso) que vão compor a árvore geradora mínima. Ao fim deve imprimir a soma total dos pesos das arestas da árvore geradora mínima. Além disso, seu método deve retornar um grafo formado pelos vértices e arestas que compõem a árvore geradora mínima. Você pode optar por implementar o algoritmo Prim ou Kruskal;

+ Calcular o caminho mínimo entre dois vértices: receba dois objetos do tipo T, e caso existam vértices com os dois valores, calcule a menor distância entre eles, imprimindo o caminho percorrido e a distância total obtida.

Para realizar a ordenação topológica desse grafo, um método eficiente é 
empregar uma pesquisa em profundidade (DFS). O algoritmo de ordenação topológica consiste em inserir os vértices no início de uma lista à medida que são concluídos.
Isso resulta em uma ordenação linear dos vértices, onde, se há uma aresta do vértice v1 para o vértice v2, v1 aparecerá antes de v2 na ordenação. Esta técnica é particularmente útil em cenários nos quais é 
vital estabelecer uma sequência ordenada de eventos.

## Link para o relatório
[Implementação de Grafos](https://docs.google.com/document/d/1zxiVaxygUfCQvWpLY5ubUX-0PmQnUbE1/edit?usp=sharing&ouid=110692527634638338468&rtpof=true&sd=true)
