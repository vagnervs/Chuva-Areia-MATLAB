# Simulação-Chuva-Areia-MATLAB
# Matriz cheia de 0 e 1 distribuídos aleatoriamente, formando um efeito de chuva.
O Projeto consiste em simular a formação de um monte de areia. Para isso, usa-se um autômato celular 2D de dois estados (0,1) assim definidos: lugar vazio (0), grão de areia (1).
Criou-se uma matriz “A” (99 x 99), completa de zeros, onde é adicionado o número “1”, na linha 1, nas três colunas centrais que representam a chuva de areia. O próximo passo é ler essa matriz de 4 em 4 posições, a fim de identificar as localizações dos “0” e “1”, de forma que, se na matriz criada for encontrado algum quadro igual ao da matriz condição (representada pela primeira figura acima), então essa posição lida na matriz “A” (99 x 99) se tornará a respectiva resposta da matriz condição. 
Logo, como resultado temos respresentação de uma Pirâmide de Areia.
