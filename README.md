# Target Sistemas Teste Tecnico - RB

1) Observe o trecho de código abaixo:

int INDICE = 13, SOMA = 0, K = 0;
```
enquanto K < INDICE faça {
K = K + 1;
SOMA = SOMA + K;
}

imprimir(SOMA);
```

Ao final do processamento, qual será o valor da variável SOMA?

```
SOMA = 91
```

2) Dado a sequência de Fibonacci, onde se inicia por 0 e 1 e o próximo valor sempre será a soma dos 2 valores anteriores (exemplo: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34...), escreva um programa na linguagem que desejar onde, informado um número, ele calcule a sequência de Fibonacci e retorne uma mensagem avisando se o número informado pertence ou não a sequência.



IMPORTANTE:

Esse número pode ser informado através de qualquer entrada de sua preferência ou pode ser previamente definido no código;



3) Descubra a lógica e complete o próximo elemento:


a) 1, 3, 5, 7, ___
```
R: 9
```
b) 2, 4, 8, 16, 32, 64, ____
```
R: 128
```
c) 0, 1, 4, 9, 16, 25, 36, ____
```
R: 49
```
d) 4, 16, 36, 64, ____
```
R: 100
```
e) 1, 1, 2, 3, 5, 8, ____
```
R: 13
```
f) 2, 10, 12, 16, 17, 18, 19, ____
```
R: 200
```


4 - Dois veículos (um carro e um caminhão) saem respectivamente de cidades opostas pela mesma rodovia. O carro de Ribeirão Preto em direção a Franca, a uma velocidade constante de 110 km/h e o caminhão de Franca em direção a Ribeirão Preto a uma velocidade constante de 80 km/h. Quando eles se cruzarem na rodovia, qual estará mais próximo a cidade de Ribeirão Preto?

IMPORTANTE:

a) Considerar a distância de 100km entre a cidade de Ribeirão Preto <-> Franca.

b) Considerar 2 pedágios como obstáculo e que o caminhão leva 5 minutos a mais para passar em cada um deles e o carro possui tag de pedágio (Sem Parar)

c) Explique como chegou no resultado.

```
Ao se cruzarem ambos estarão na mesma distância, a 60,94km 
de Ribeirão Preto.

Raciocínio:

Caminhão: 100km / 80km = 1,25h (75 min) + 0,17h (10 min)
= 1,42h (85 min)

100 / 1,42 = 70,42km/h

Carro: 110km/h

Velocidade relativa: 110km/h + 70,42km/h = 180,42km

A distância que os objetos percorrem até se encontrarem é 
igual à distância inicial entre eles, que é de 100 km. 
Assim, podemos escrever a equação:

distância = velocidade relativa × tempo

100 = 180,42 x t

t = 100 / 180,42 = 0,554 horas

Distância percorrida pelo carro = 110 km/h × 0,554 h
Distância percorrida pelo carro = 60,94 km
Distância percorrida pelo caminhão = velocidade B × tempo
Distância percorrida pelo caminhão = 70,42 km/h × 0,554 h
Distância percorrida pelo caminhão = 39,08 km

Logo o carro e o caminhão se encontram a uma distância de
60,94km de Ribeirão Preto.

```

5) Escreva um programa que inverta os caracteres de um string.



IMPORTANTE:

a) Essa string pode ser informada através de qualquer entrada de sua preferência ou pode ser previamente definida no código;

b) Evite usar funções prontas, como, por exemplo, reverse;