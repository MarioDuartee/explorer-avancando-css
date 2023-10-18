Explicação e resumo.

Nesse capitulo usamos Grid, Media query, variaveis no css e clamp.

Com grid usamos as propriedades:
grid-template-area, onde define cada a posição e tamanho de cada item que logo sera chamado atraves da propriedade grid-area.

Já nas Media query, começamos com uma pagina desenvolvida para dispositivos com telas menores que 640px, e então chamamos: @Media(min-width: 640px), para ajustar algumas coisas para alem desse tamanho.

As variaveis são declaradas na pseudoclass ":root", elas são chamadas atraves de dois hífens seguidos do nome escolhido para aquela variavel: --variavel-A: 40px.
Para chamar a variavel em seguida se chama, por exemplo: font-size: var(--varivel-A)

Já a função clamp() ela aceita três propriedades, menor, normal e maior. Ela pode ser usada quando queremos que algo se ajuste ao tamanho da janela, em tempo real, com a largura que estamos ajustando. A sintaxe da clamp é:
clamp(200px, 40%, 400px);
clamp(20rem, 30vw, 70rem);
clamp(10vw, 20em, 100vw);