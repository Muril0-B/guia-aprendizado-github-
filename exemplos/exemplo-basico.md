# Exemplo Básico — Resolvendo um Sistema de Equações do 1º Grau

Este exemplo aplica, de forma prática, os conceitos apresentados em [`docs/01-introducao.md`](docs/01-introducao.md) e [`docs/02-conceitos.md`](docs/02-conceitos.md). Para mais exercícios, veja [`docs/03-exercicios.md`](docs/03-exercicios.md).

## O problema

Uma loja vende dois produtos, A e B. Um cliente comprou 3 unidades de A e 2 unidades de B, pagando R$ 26,00. Outro cliente comprou 1 unidade de A e 4 unidades de B, pagando R$ 18,00. Qual é o preço de cada produto?

## Montando o sistema

Chamando o preço do produto A de **x** e o preço do produto B de **y**, as duas compras se traduzem em duas equações:

```
3x + 2y = 26
x + 4y = 18
```

Como as duas equações têm as mesmas incógnitas (x e y) e precisam ser verdadeiras ao mesmo tempo, elas formam um sistema de equações do 1º grau — exatamente o tipo de sistema descrito na introdução.

## Resolvendo pelo método da substituição

Isolando x na segunda equação:

```
x = 18 − 4y
```

Substituindo essa expressão na primeira equação:

```
3(18 − 4y) + 2y = 26
54 − 12y + 2y = 26
54 − 10y = 26
−10y = 26 − 54
−10y = −28
y = 2,8
```

Substituindo y = 2,8 de volta em x = 18 − 4y:

```
x = 18 − 4(2,8)
x = 18 − 11,2
x = 6,8
```

**Solução:** x = 6,8 e y = 2,8, ou seja, o produto A custa R$ 6,80 e o produto B custa R$ 2,80.

## Conferindo a solução

Substituindo (6,8; 2,8) nas duas equações originais:

```
3(6,8) + 2(2,8) = 20,4 + 5,6 = 26   ✓
6,8 + 4(2,8) = 6,8 + 11,2 = 18      ✓
```

As duas igualdades são verdadeiras, confirmando que o par (6,8; 2,8) é a solução do sistema.