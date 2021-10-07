# Python Game

Esse é um jogo matematico feito em **python**.
Ele usa a classe Calcular que importa a blibioteca **random**.

O usuario começa o jogo escolhendo a dificuldade.
`Informe o nível de dificulade desejado [1, 2, 3 ou 4]:`

Depois de selecionada, o programa gera uma operação que varia com a dificuldade da mesma. Essa sendo uma como exemplo:
`891 - 267 = ?`

Se o usuario acertar, aparecerá a seguinte mensagem `Resposta correta!`, junto com o *score* do usuario até ali.

Se o usuario errar, aparecerá `Resposta errada!` e embaixo a resposta correta.

~~~bash
Informe o resultado para a seguinte operacação: 
1 * 10 = ?
0
Resposta errada!
1 * 10 = 10
~~~

Após isso o programa perguntará se o jogador quer ou não continuar `Deseja continuar no jogo? [1 - sim, 0 - não]`

E digitando `0` o programa acaba. 
