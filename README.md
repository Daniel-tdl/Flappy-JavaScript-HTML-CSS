# Flappy-JavaScript-HTML-CSS
Jogo de Flappy Bird 
 
Este joguinho foi criado para mostrar como utilizar o Javascript para manipular o HTML.

Basicamente utilizamos o CSS e o HTML apenas para montar a estrutura básica da aplicação, a mágica acontece de verdade no Javascript.
No JS é que criamos os elementos necessários para o jogo funcionar.
Utilizamos funções construtoras para reaproveitar código e o mais legal é que se preocupamos com a performance da aplicação, reaproveitando o objeto de barreira (div) e não criando várias barreiras (divs) conforme o progresso do jogo.

Para o joguinho funcionar basta pressionar qualquer tecla para o pássaro subir e soltar para descer, as barreiras como já disse são aproveitadas para não criar várias divs e com isso deixar o jogo lento, para isso foram criadas 4 barreiras iniciais e depois conforme o jogo vai progredindo e as barreiras vão sumindo da tela, as mesmas são realocados no final da fila novamente.

