## Iniciante em Programação F2T2 - ONE
O caminho das pedras para entrar no universo da programação e começar com a criação de sites utilizando as linguagens populares CSS, HTML e JavaScript.

#### Conheça esta Formação!
Se você não conhece nada de programação e desenvolvimento de software, mas deseja entrar nessa área onde o mercado de trabalho está superaquecido, a formação Iniciante em programação é para você!

Você vai criar suas primeiras páginas web, utilizando **HTML, CSS, JS e assim aprender lógica de programação** junto com as linguagens de programação mais utilizadas no mundo.

Se você trabalha em outras áreas como marketing digital, experiência do usuário (UX), design, ou áreas correlatas, essa formação te ajudará a entender melhor como a área de tecnologia funciona e, assim, você consegue se comunicar melhor com a área de desenvolvimento.


## Tarefas:

#### A cara do Creeper

O Johann é um menino de 11 anos e adora jogar Minecraft. Minecraft é aquele jogo onde você constrói um mundo com blocos, como se fosse um Lego virtual. Ele gosta tanto que pediu um pôster de uma das personagens principais do jogo: o Creeper.

O Creeper na verdade é um monstro (que explode ao se aproximar de um jogador).

Segue o tamanho (largura, altura) em pixels de cada retângulo:

Retângulo 1: 350, 300 (cabeça).
Retângulos 2 e 3: 90, 90 (olhos).
Retângulo 4: 70, 100 (nariz).
Retângulos 5 e 6: 40, 110 (parte da boca).
O seu canvas deve ter o tamanho de 600 x 400 pixels.

#### Esquadro

Repare que isso é nada mais do que dois triângulos, um dentro do outro. Lembrando também que desenhar um triângulo é diferente de um retângulo, pois é preciso desenhar linha por linha. Em outras palavras, a API é diferente!

<h3><strong>Medidas:</strong></h3>
<h4>Triângulo externo/maior:</h4>
<p>Canto superior esquerda: 50,50</p>
<p>Canto inferior esquerda: 50,400</p>
<p>Canto inferior direito: 400,400</p>
<hr>
<h4>Triângulo infeior/menor:</h4>
<p>Canto superior esquerda: 100,175</p>
<p>Canto inferior esquerda: 100,350</p>
<p>Canto inferior direito: 275,350</p>

#### Ordem e Progresso

Que tal desenhar a nossa bandeira? Tirando as estrelas e o dizer "Ordem e Progresso", sabemos tudo para desenhar a bandeira do Brasil: Talvez você esteja pensando que não aprendemos a criar um losango, mas repare que o losango amarelo pode ser representado através de dois triângulos:

Ou seja, temos um retângulo verde (green), dois triângulos amarelos (yellow) e um circulo azul escuro (darkblue).

Nos exercícios anteriores já praticamos como desenhar retângulos e triângulos.

#### Programa 2

Desenhando quadrados

#### Desenhando círculo

Desenhando um flor

#### Desenhando fração

Desenhando fração com os quadrados 

#### Gráfico de barras

Através de gráficos podemos expressar visualmente dados ou valores numéricos, e assim facilitar a nossa compreensão. Gráficos ajudam a entender o relacionamento entre valores e facilitam tirar conclusões.

#### Esquadro 2

Criando um esquadro ao desenhar dois triângulo um dentro do outro.

#### Programa 3

Aprendemos a interagir com o usuário, por exemplo, desenhando uma bolinha azul toda vez que ele clicar no canvas, nossa tela!

#### Trocando de cor

Permitir que o usuário altere a cor da bolinha que é desenhada na tela. As cores serão obrigatoriamente blue, red e green.

#### Era uma vez uma bolinha que virou um bolão

Quando clicarmos na tela pressionando a tecla SHIFT, vamos desenhar uma bolinha acrescida de 20 ao seu raio. Se soltarmos a tecla e clicarmos, ela voltará com seu raio que hoje é 10.

#### Era uma vez um bolão que quase explodiu!

Nesse código que é a seguinte: toda vez que o usuário clicar na tela com o SHIFT pressionado, vamos somar 10 ao valor do raio atual. Sendo assim, mesmo soltando o SHIFT as próximas bolinhas utilizarão o mesmo valor de raio. Se clicarmos diversas vezes segurando SHIFT teremos uma bola cada vez maior.

#### O bolão que deseja emagrecer!

Você deve ter ficado tão incomodado quanto eu, porque a bolinha só cresce até tomar conta da tela inteira. Uma das coisas que podemos melhorar é limitar o tamanho de crescimento das bolinhas, ou seja, quero combinar com você que o raio não pode ultrapassar 40. Além disso, se o usuário clicar na tela com a tecla ALT pressionada, o raio deve diminuir 5. Para saber se a tecla ALT está pressionada, fazemos evento.altKey. ATENÇÃO: o decremento do raio deverá ser de 5 em 5 e o tamanho mínimo da bolinha deve ser de 10 que é o tamanho original.
IMPORTANTE: SE VOCÊ USA LINUX, USE evento.ctrlKey no lugar de evento.altKey. Isso porque o ALT no linux ativa o menu.

#### Desenhando com o mouse

O desafio agora é o seguinte. Se andarmos com o ponteiro do mouse sobre a tela enquanto o botão esquerdo é pressionado, vamos desenhar um círculo. Isso significa que enquanto não soltarmos o botão esquerdo, desenharemos um círculo ao lado do outro, que na verdade dará um efeito que estamos passando um pincel na tela. Se soltarmos o botão esquerdo, o ato de mover o mouse sob a tela não deverá desenhar nada. No final, queremos um efeito parecido com ferramentas como Paint Brush ou Photoshop, que permite o usuário desenhar na tela.

#### Desenhando com o mouse com infinitas cores

Agora, vamos adicionar um input em nossa página logo após o canvas. No mundo HTML, existe o input do tipo color, que ao ser clicado exibe uma paleta de cores para podermos selecionar;

#### Acertando o alvo

O alvo é feito a partir de três círculos, todos com as mesmas coordenadas x e y, mas que possuem raios diferentes. Começamos desenhando primeiro do maior para o menor, se tivéssemos feito ao contrário o círculo maior vermelho seria desenhado em cima dos demais.

#### Animações simples

Temos uma esfera viajando do canto superior esquerdo da tela, até o canto superior direito. Para que a animação fique mais rápida, basta alterar o segundo parâmetro de setInterval, deixaremos como 10;

#### Tudo que vai volta

Altere o código para que o círculo, assim que chegar no canto direito da tela, volte. No final, o círculo deve ficar indo e voltando eternamente. Existem várias formas de se conseguir esse resultado, assim como tudo no universo da programação. 

#### Pulso

Sua tarefa será fazer uma bolinha pulsar, ou seja, seu raio deve ter tamanho mínimo de 20 e tamanho máximo de 30. Sendo assim, de 20 até 30, o raio deve ser incrementado de um em um e quando o valor do raio ultrapassar o máximo, ele deve sofrer um decremento de um. Contudo, fique alerta, pois se o raio se tornar menor que 20, devemos voltar a incrementá-lo e assim por diante. Para um efeito mais pomposo, use 20 milissegundos na taxa de atualização da tela.

#### Movendo a bolinha pelo teclado

Então, esse exercício tem duas partes. A primeira eu lhe ensinarei como capturar as arrow keys, ou seja, aquelas teclas que são setas, geralmente usadas em joguinhos para andar com algo pela tela. Na segunda parte, vem o desafio de lógica que você deve implementar.
Identificando qual tecla foi pressionada
Em JavaScript, existe o evento onkeydown, que permite identificar qual tecla está pressionada. Esse evento é o único capaz de identificar também as setas do teclado. Contudo, até agora todos os eventos que associamos foi com nossa tela, mas dessa vez quem deve responder ao evento é document. E document, nosso oráculo que sabe tudo o que a página possui, é o cara que fica escutando ao teclado. Então, vou alterar o código e criar a função leDoTeclado e associá-la ao document através do evento onkeydown;

#### Trocando bandeiras

Vamos usar as bandeiras do Brasil e da Alemanha. A ideia é homenagear a final de futebol masculino das Olimpíadas e claro, aprender e praticar mais lógica de programação.

## Prints:

![Print do programa sobre API](/LOGICA%202/imgs/print.png)

##### A cara do Creeper
![Print do Creeper](/LOGICA%202/imgs/print1.png)

##### Esquadro
![Print Esquadro](/LOGICA%202/imgs/print2.png)

##### Ordem e progresso
![Print Ordem e progresso](/LOGICA%202/imgs/print3.png)

##### Programa 2
![Programa 2](/LOGICA%202/imgs/programa2.png)

##### Desenhando círculo
![Desenhando círculo](/LOGICA%202/imgs/desenhandoCirculo.png)

##### Desenhando fração
![Desenhando fração](/LOGICA%202/imgs/DesenhandoFracao.png)

##### Desenhando gráfico de barras
![Desenhando gráfico de barras](/LOGICA%202/imgs/graficodebarras.png)

##### Desenhando esquadro 2
![Desenhando esquadro 2](/LOGICA%202/imgs/esquadro2.png)

##### Programa 3 
![Programa 3](/LOGICA%202/imgs/print4.png)

##### Trocando de cor 
![Trocando cor](/LOGICA%202/imgs/print5.png)

##### Era uma vez uma bolinha que virou um bolão 
![Era uma vez uma bolinha que virou um bolão](/LOGICA%202/imgs/print6.png)

##### Era uma vez um bolão que quase explodiu
![Era uma vez uma bolinha que virou um bolão](/LOGICA%202/imgs/print7.png)

##### O bolão que deseja emagrecer!
![O bolão que deseja emagrecer](/LOGICA%202/imgs/print8.png)

##### Desenhando com o mouse
![Desenhando com o mouse](/LOGICA%202/imgs/print9.png)

##### Desenhando com o mouse com infinitas cores
![Desenhando com o mouse com infinitas cores](/LOGICA%202/imgs/print10.png)

##### Acertando o alvo
![Acertando o alvo](/LOGICA%202/imgs/print11.png)

##### Animações simples
![Animações simples](/LOGICA%202/imgs/print12.png) 

##### Tudo que vai volta
![Tudo que vai volta](/LOGICA%202/imgs/print13.png) 

##### Pulso
![Pulso](/LOGICA%202/imgs/print14.png) 

##### Movendo a bolinha pelo teclado
![Movendo a bolinha pelo teclado](/LOGICA%202/imgs/print15.png) 

#####  Trocando bandeiras 
![Trocando bandeiras](/LOGICA%202/imgs/print16.png) 