# SepararDigitos
A função pede que o usuário digite um numero de 4 dígitos, realiza as operações e ai mostra esse numero de quatro dígitos, numero por numero para o usuário.

# Explicação:
Lembrete: Como salva eles como inteiro, o numero depois da virgula é ignorado.
numero = 1234;

--Unidade
Primeiramente faz o numero % com 10 que pega o ultimo digito do numero e salva esse digito.
1234 % 10 = 4

Em seguida / por 10 para "eliminar" esse digito já salvo.
1234 / 10 = 123

--Dezena
O que sobra faz % com 10 que pega o ultimo digito do numero e salva esse digito.
123 % 10 = 3

Em seguida / por 10 para "eliminar" esse digito já salvo.
123 / 10 = 12

--Centena
O que sobra faz % com 10 que pega o ultimo digito do numero e salva esse digito.
12 % 10 = 2

Em seguida / por 10 para "eliminar" esse digito já salvo.
12 / 10 = 1

--Unidade de Milhar
O que sobra faz % com 10 que pega o ultimo digito do numero e salva esse digito.
1 % 10 = 1

Em seguida / por 10 para "eliminar" esse digito já salvo.
1 / 10 = 1
