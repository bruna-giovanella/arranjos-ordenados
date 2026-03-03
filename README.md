# arranjos-ordenados

Título: 01 - Arranjos Ordenados

Instruções: Implemente a estrutura de dados ArranjoOrdenado capaz de lidar com números inteiros de maneira crescente e decrescente. Adicione os testes unitários para garantir a corretude da estrutura.

1. Realize o experimento científico sobre a operação inserção considerando a ordenação crescente e a ordenação decrescente. Segue a metodologia.

 

Para cada execução e tipo de ordenação:

Condições iniciais:

Uma nova estrutura de dados ArranjoOrdenado  para inteiros vazio e com uma capacidade de 100.000 elementos.
Inserir os elementos de maneira crescente.
Inserir os elementos de maneira decrescente.
Inserir os elementos de maneira aleatória. Utilize a classe java.util.Random.
Procedimentos:

Obter o tempo inicial, T1. Utilize System.nanoTime().
Realizar a inserção dos elementos.
Obter o tempo final, T2.
Calcular o tempo total, Total = T2 - T1.
Salvar o tempo total.
Após as 100 execuções:

Calcular o tempo médio.
Calcular o desvio padrão.
Salvar as informações
 

2. Realize o experimento sobre a operação exclusão considerando a ordenação crescente e a ordenação decrescente. Segue a metodologia.

Para cada execução e tipo de ordenação:

Condições iniciais:

Uma nova estrutura de dados ArranjoOrdenado  para números ordenados cheia e com uma capacidade de 100.000 elementos.
Inserir os elementos de maneira crescente.
Inserir os elementos de maneira decrescente.
Inserir os elementos de maneira aleatória. Utilize a classe java.util.Random. Obs: Guarde os números armazenados para realizar a exclusão sem gerar exceções.
Procedimentos:

Obter o tempo inicial, T1. Utilize System.nanoTime().
Realize a exclusão dos 100.000 números.
Obter o tempo final, T2.
Calcular o tempo total, Total = T2 - T1.
Salvar o tempo total.
Após as 100 execuções:

Calcular o tempo médio.
Calcular o desvio padrão.
Salvar as informações
Extra: Comparar os dois algoritmos de inserção

 

3. Tabule os resultados obtidos. Por exemplo:

Inserção	Ordenação crescente	Ordenação decrescente
Inserção em maneira crescente	10+/-0.3434	10+/-0.3434
Inserção em maneira decrescente	10+/-0.3434	10+/-0.3434
Inserção em maneira aleatória	10+/-0.3434	10+/-0.3434
 

Extra: Realizar o teste de Wilcoxon.

 

4. Crie uma apresentação (power point) com os resultados obtidos. A apresentação deverá conter.

A estrutura de dados ArranjoOrdenado. A classe em formato da UML.
Como implementou na estrutura de dados a ordenação de maneira crescente ou decrescente. (pequenos trechos chaves do código).
Resultados obtidos.
Análise e conclusão dos resultados obtidos.
 

5. Entregar na ferramenta o link para o repositório no github com o código e apresentação.

 

6. Avaliação

O código da estrutura de dados ArranjoOrdenado.
O código do experimento realizado.
O uso de testes unitários (JUnit)
A apresentação
7. Na próxima aula, será sorteado 2-3 pessoas para apresentar os resultados obtidos.

