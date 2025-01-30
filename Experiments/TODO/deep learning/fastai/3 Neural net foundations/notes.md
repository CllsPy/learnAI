Uma rede neural é uma série de cálculos matemático que faz uma multiplicação dos valores de entrada (imagens de gatinhos) por número, que chamamos de parâmetros outra coisa que uma rede neural faz é transformar valores negativos em “0’s”.

Isso se chama layer, e a saída de cada layer vira a entrada do próximo e isso acontece a todos eles.

Inicialmente cada parâmetro que multiplica os valores de entrada são aleatórios, mas podemos “melhorar” eles com algo chamado gradient descent.

Um tensor é como um vetor, ele guarda vários valores e com várias dimensões.

Com Pytorch é possível começar com valores randômicos e com um método chamado grad e um loop podemos ir encontrando valores cada vezes menores entre os pontos e a linha que trançamos para ter a menor perda possível.

Um valor importante nesse cálculo computacional é a “taxa-de-aprendizado”  é um valor pequeno que determina a velocidade na qual estamos indo em direção ao menos valor (loss).

Se o loop for muito grande em algum momento começamos a perder a qualidade do treino, porque vamos passar do menor valor possível (é preciso ter cuidado com isso).

![image](https://github.com/CllsPy/Learn_AI_From_Scratch/assets/96326019/6ebfcb4d-ee05-4ead-ab47-0e542bab2a82)

Uma rede neural por outro lado pode entender função bem mais complexas e como foi dito em dois passos importante:

- Multiplicação de matrizes

- Valores negativos viram zero

Existem uma série de coisas que podemos fazer com as redes neurais, como por exemplo usar convolução ao invés de multiplicar matrizes para evitar cálculos desnecessário, efetuar os cálculos na GPU ao invés da CPU ou quem sabe ao invés de começar com dados aleatórios podemos começar com dados que outro modelos aprendeu antes (transfer-learning).
