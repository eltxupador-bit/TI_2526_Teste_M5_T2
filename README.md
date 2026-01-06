# Ficha de Avaliação - Folha de Cálculo - Turno 2

## Instruções

* Esta avaliação é individual.

* Podes rever os exercícios previamente realizados.

* Faz um ***fork*** deste repositório.

![alt text](img/image.png)

* No teu ***fork***, edita o ficheiro **README.md**

![alt text](img/image-1.png)

* Utiliza os espaços indicados para responderes às questões.

* Não desformates o ficheiro.

* Quando terminares, realiza um ***Commit***

![alt text](img/image-2.png)

## Exercícios

1. Explica para que serve o sinal = numa folha de cálculo.
Indica duas situações em que se deve usar uma fórmula.
(3 valores)

        Resposta: O sinal = serve para indicar ao programa que o conteúdo da célula é uma fórmula ou função , e não apenas texto ou um número estático.
Situação 1: Para realizar cálculos aritméticos (ex: somar o total de despesas).
Situação 2: Para automatizar a atualização de dados (ex: calcular o IVA sempre que o preço base muda).

2. O que acontece a uma fórmula quando é copiada para outra célula?
Explica a tua resposta usando o conceito de referências de células.
(3 valores)

        Resposta: Quando uma fórmula é copiada , as suas referências relativas ajustam-se automaticamente de acordo com a nova posição (coluna/linha). Isso acontece porque o programa interpreta a morada da célula não como um ponto fixo , mas como uma distância relativa à célula onde a fórmula está escrita.

3. Observa a seguinte fórmula, escrita na célula E4:

        =C4*$A$1

    a) Que tipo de referência é usada em A1? (1 valor)

        Resposta: É uma referência absoluta (identificada pelos símbolos $).

    b) O que acontece à referência C4 se a fórmula for copiada para E5? (1 valor)

        Resposta: A referência altera-se para C5 (ajusta uma linha para baixo).

4. Explica o que é a formatação condicional e indica duas regras que podem ser aplicadas a uma tabela.
(3 valores)

        Resposta: É uma ferramenta que altera automaticamente o aspeto visual de uma célula (cor , tipo de letra) com base no seu valor ou conteúdo.
Regra 1: Pintar de vermelho as notas inferiores a 10.
Regra 2: Realçar com fundo verde valores superiores a 500€ num inventário.

5. Para que serve um filtro automático numa folha de cálculo?
Dá um exemplo prático relacionado com um inventário ou lista de dados.
(2 valores)

        Resposta: Serve para ocultar temporariamente os dados que não pretendemos ver, mantendo apenas os que cumprem certos critérios.
Exemplo: Num inventário de uma loja filtrar apenas os produtos que têm "Stock Zero" para saber o que encomendar.

6. Completa a frase corretamente (2 valores):

    Ordenar dados serve para ____________, enquanto filtrar dados serve para _____________.

        Resposta 1: organizar a informação numa sequência lógica (A-Z ou crescente).
        Resposta 2: mostrar apenas os dados que cumprem um critério específico.

7. Para que serve um gráfico numa folha de cálculo?
Escolhe um tipo de gráfico e refere uma situação concreta em que possa ser usado.
(3 valores)

        Resposta: Um gráfico serve para visualizar e interpretar dados de forma rápida e intuitiva , facilitando a análise de tendências.
Tipo: Gráfico de Setas (Queijo/Circular).
Situação: Mostrar a percentagem de votos de cada candidato numa eleição escolar.

8. Escreve a fórmula necessária para calcular a prestação mensal de um empréstimo de 1000 €, a pagar em 24 meses, com taxa anual de 4%.
Não é necessário calcular o valor final.
(2 valores)

        Resposta: Para calcular a prestação mensal , usamos a função =PGTO() ou =PMT(). Nota que a taxa anual deve ser dividida por 12 meses.
