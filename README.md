# Lista de Exercícios em C++

Exercícios resolvidos e inspirados no site [Python Brasil](https://wiki.python.org.br/ListaDe1_Estrutura_Sequencial) e implementado em C++.

- [Estruturas sequenciais](#estruturas-sequenciais)
- [Estruturas de Decisao](#estruturas-de-decisao)
- [Estruturas de Repeticao](#estruturas-de-repeticao)
- [Listas](#listas)

### Estruturas sequenciais

#### [Exercicio 01](1_Estrutura_Sequencial/01_alo_mundo.cpp)

Faça um Programa que mostre a mensagem "Alo mundo" na tela.

#### [Exercicio 02](1_Estrutura_Sequencial/02_imprime_numero.cpp)

Faça um Programa que peça um número e então mostre a mensagem O número
informado foi [número].

#### [Exercicio 03](1_Estrutura_Sequencial/03_soma_numeros.cpp)

Faça um Programa que peça dois números e imprima a soma.

#### [Exercicio 04](1_Estrutura_Sequencial/04_media_notas.cpp)

Faça um Programa que peça as 4 notas bimestrais e mostre a média.

#### [Exercicio 05](1_Estrutura_Sequencial/05_metros_centimetros.cpp)

Faça um Programa que converta metros para centímetros.

#### [Exercicio 06](1_Estrutura_Sequencial/06_area_circulo.cpp)

Faça um Programa que peça o raio de um círculo, calcule e mostre sua área.

#### [Exercicio 07](1_Estrutura_Sequencial/07_area_quadrado.cpp)

Faça um Programa que calcule a área de um quadrado, em seguida mostre o dobro
desta área para o usuário.

#### [Exercicio 08](1_Estrutura_Sequencial/08_salario.cpp)

Faça um Programa que pergunte quanto você ganha por hora e o número de horas
trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês.

#### [Exercicio 09](1_Estrutura_Sequencial/09_fahrenheit_celsius.cpp)

Faça um Programa que peça a temperatura em graus Farenheit, transforme e mostre
a temperatura em graus Celsius.
C = (5 \* (F-32) / 9).

#### [Exercicio 10](1_Estrutura_Sequencial/10_celsius_fahrenheit.cpp)

Faça um Programa que peça a temperatura em graus Celsius, transforme e mostre
em graus Farenheit.

#### [Exercicio 11](1_Estrutura_Sequencial/11_operacoes_numericas.cpp)

Faça um Programa que peça 2 números inteiros e um número real.
Calcule e mostre:
o produto do dobro do primeiro com metade do segundo.
a soma do triplo do primeiro com o terceiro.
o terceiro elevado ao cubo.

#### [Exercicio 12](1_Estrutura_Sequencial/12_peso_ideal.cpp)

Tendo como dados de entrada a altura de uma pessoa,
construa um algoritmo que calcule seu peso ideal,
usando a seguinte fórmula: (72.7\*altura) - 58

#### [Exercicio 13](1_Estrutura_Sequencial/13_peso_ideal_sexo.cpp)

Tendo como dado de entrada a altura (h) de uma pessoa,
construa um algoritmo que calcule seu peso ideal,
utilizando as seguintes fórmulas:
Para homens: (72.7*h) - 58
Para mulheres: (62.1*h) - 44.7

#### [Exercicio 14](1_Estrutura_Sequencial/14_excesso_peixe.cpp)

João Papo-de-Pescador, homem de bem, comprou um microcomputador para controlar
o rendimento diário de seu trabalho.

Toda vez que ele traz um peso de peixes maior que o estabelecido pelo
regulamento de pesca do estado de São Paulo (50 quilos) deve pagar uma multa
de R$ 4,00 por quilo excedente.

João precisa que você faça um programa que leia a variável peso
(peso de peixes) e calcule o excesso.

Gravar na variável excesso a quantidade de quilos além do limite
e na variável multa o valor da multa que João deverá pagar.
Imprima os dados do programa com as mensagens adequadas.

#### [Exercicio 15](1_Estrutura_Sequencial/15_salario_tributario.cpp)

Faça um Programa que pergunte quanto você ganha por hora e o número de horas
trabalhadas no mês.

Calcule e mostre o total do seu salário no referido mês,
sabendo-se que são descontados 11% para o Imposto de Renda,
8% para o INSS e 5% para o sindicato, faça um programa que nos dê:
salário bruto.
quanto pagou ao INSS.
quanto pagou ao sindicato.
o salário líquido.
calcule os descontos e o salário líquido, conforme a tabela abaixo:

    + Salário Bruto : R$
    - IR (11%) : R$
    - INSS (8%) : R$
    - Sindicato ( 5%) : R$
    = Salário Liquido : R$

Obs.: Salário Bruto - Descontos = Salário Líquido.

#### [Exercicio 16](1_Estrutura_Sequencial/16_quantidade_tintas.cpp)

Faça um programa para uma loja de tintas.
O programa deverá pedir o tamanho em metros quadrados da área a ser pintada.

Considere que a cobertura da tinta é de 1 litro para cada 3 metros
quadrados e que a tinta é vendida em latas de 18 litros, que custam R$ 80,00.

Informe ao usuário a quantidades de latas de tinta
a serem compradas e o preço total.

#### [Exercicio 17](1_Estrutura_Sequencial/17_quantidade_tintas_extensa.cpp)

Faça um Programa para uma loja de tintas.

O programa deverá pedir o tamanho em metros quadrados da área a ser pintada.

Considere que a cobertura da tinta é de 1 litro para cada 6 metros quadrados
e que a tinta é vendida em latas de 18 litros, que custam R$ 80,00
ou em galões de 3,6 litros, que custam R$ 25,00.

Informe ao usuário as quantidades de tinta a serem compradas
e os respectivos preços em 3 situações:

    comprar apenas latas de 18 litros;
    comprar apenas galões de 3,6 litros;
    misturar latas e galões, de forma que o preço seja o menor.
        Acrescente 10% de folga e sempre arredonde os valores para cima,
        isto é, considere latas cheias.

#### [Exercicio 18](1_Estrutura_Sequencial/18_tempo_download.cpp)

Faça um programa que peça o tamanho de um arquivo para download (em MB) e a
velocidade de um link de Internet (em Mbps), calcule e informe o tempo
aproximado de download do arquivo usando este link (em minutos).

### Estruturas de Decisao

#### [Exercicio 01](2_Estrutura_Decisao/01_maior.cpp)

Faça um Programa que peça dois números e imprima o maior deles.

#### [Exercicio 02](2_Estrutura_Decisao/02_positivo_negativo.cpp)

Faça um Programa que peça um valor e mostre na tela se o valor é positivo
ou negativo.

#### [Exercicio 03](2_Estrutura_Decisao/03_verifica_sexo.cpp)

Faça um Programa que verifique se uma letra digitada é "F" ou "M".
Conforme a letra escrever: F - Feminino, M - Masculino, Sexo Inválido.

#### [Exercicio 04](2_Estrutura_Decisao/04_vogal_consoante.cpp)

Faça um Programa que verifique se uma letra digitada é
vogal ou consoante.

#### [Exercicio 05](2_Estrutura_Decisao/05_media_aluno.cpp)

Faça um programa para a leitura de duas notas parciais de um aluno.
O programa deve calcular a média alcançada por aluno e apresentar:

    A mensagem "Aprovado", se a média alcançada for maior ou igual a sete;
    A mensagem "Reprovado", se a média for menor do que sete;
    A mensagem "Aprovado com Distinção", se a média for igual a dez;

#### [Exercicio 06](2_Estrutura_Decisao/06_maior2.cpp)

Faça um Programa que leia três números e mostre o maior deles.

#### [Exercicio 07](2_Estrutura_Decisao/07_maior_menor.cpp)

Faça um Programa que leia três números e mostre o maior e o menor deles.

#### [Exercicio 08](2_Estrutura_Decisao/08_compara_produtos.cpp)

Faça um programa que pergunte o preço de três produtos e informe qual produto
você deve comprar, sabendo que a decisão é sempre pelo mais barato.

#### [Exercicio 09](2_Estrutura_Decisao/09_ordem_decrescente.cpp)

Faça um Programa que leia três números e mostre-os em ordem decrescente.

#### [Exercicio 10](2_Estrutura_Decisao/10_turno.cpp)

Faça um Programa que pergunte em que turno você estuda.
Peça para digitar M-matutino ou V-Vespertino ou N- Noturno.
Imprima a mensagem "Bom Dia!", "Boa Tarde!" ou "Boa Noite!" ou "Valor Inválido!", conforme o caso.

#### [Exercicio 11](2_Estrutura_Decisao/11_salario_tabajara.cpp)

As Organizações Tabajara resolveram dar um aumento de salário aos seus colaboradores e
lhe contraram para desenvolver o programa que calculará os reajustes.
Faça um programa que recebe o salário de um colaborador e o reajuste segundo o seguinte critério,
baseado no salário atual:

    salários até R$ 280,00 (incluindo) : aumento de 20%
    salários entre R$ 280,00 e R$ 700,00 : aumento de 15%
    salários entre R$ 700,00 e R$ 1500,00 : aumento de 10%
    salários de R$ 1500,00 em diante : aumento de 5% Após o aumento ser realizado, informe na tela:
    o salário antes do reajuste;
    o percentual de aumento aplicado;
    o valor do aumento;
    o novo salário, após o aumento.

#### [Exercicio 12](2_Estrutura_Decisao/12_folha_pagamento.cpp)

Faça um programa para o cálculo de uma folha de pagamento, sabendo que os descontos são do Imposto
de Renda, que depende do salário bruto (conforme tabela abaixo) e 3% para o Sindicato e que o FGTS
corresponde a 11% do Salário Bruto, mas não é descontado (é a empresa que deposita).

O Salário Líquido corresponde ao Salário Bruto menos os descontos. O programa deverá pedir ao usuário o valor da sua hora
e a quantidade de horas trabalhadas no mês.

Desconto do IR: Salário Bruto até 900 (inclusive) - isento Salário Bruto até 1500 (inclusive) - desconto de 5% Salário Bruto até 2500 (inclusive) - desconto de 10% Salário Bruto acima de 2500 - desconto de 20%

Imprima na tela as informações, dispostas conforme o exemplo abaixo. No exemplo o valor da hora é 5 e a quantidade de hora é 220.

    Salário Bruto: (5 * 220)        : R$ 1100,00
    (-) IR (5%)                     : R$   55,00
    (-) INSS ( 10%)                 : R$  110,00
    FGTS (11%)                      : R$  121,00
    Total de descontos              : R$  165,00
    Salário Liquido                 : R$  935,00

#### [Exercicio 13](2_Estrutura_Decisao/13_dia_semana.cpp)

Faça um Programa que leia um número e exiba o dia correspondente da semana.
(1-Domingo, 2- Segunda, etc.), se digitar outro valor deve aparecer valor inválido.

#### [Exercicio 14](2_Estrutura_Decisao/14_media_conceitos.cpp)

As Organizações Tabajara resolveram dar um aumento de salário aos seus colaboradores e
lhe contraram para desenvolver o programa que calculará os reajustes.
Faça um programa que recebe o salário de um colaborador e o reajuste segundo o seguinte critério,
baseado no salário atual:

O algoritmo deve mostrar na tela as notas, a média, o conceito correspondente e a mensagem
“APROVADO” se o conceito for A, B ou C ou “REPROVADO” se o conceito for D ou E.

    Média de Aproveitamento  Conceito
    Entre 9.0 e 10.0        A
    Entre 7.5 e 9.0         B
    Entre 6.0 e 7.5         C
    Entre 4.0 e 6.0         D
    Entre 4.0 e zero        E

#### [Exercicio 15](2_Estrutura_Decisao/15_triangulo.cpp)

Faça um Programa que peça os 3 lados de um triângulo. O programa deverá informar se os valores podem ser
um triângulo. Indique, caso os lados formem um triângulo, se o mesmo é: equilátero, isósceles ou escaleno.

Dicas: - Três lados formam um triângulo quando a soma de quaisquer dois lados for maior que o terceiro; - Triângulo Equilátero: três lados iguais; - Triângulo Isósceles: quaisquer dois lados iguais; - Triângulo Escaleno: três lados diferentes;

#### [Exercicio 16](2_Estrutura_Decisao/16_equacao_segundo_grau.cpp)

Faça um programa que calcule as raízes de uma equação do segundo grau, na forma ax2 + bx + c.
O programa deverá pedir os valores de a, b e c e fazer as consistências, informando ao usuário nas seguintes situações:

    a) Se o usuário informar o valor de A igual a zero, a equação não é do segundo grau e o programa não deve fazer pedir os demais valores, sendo encerrado;
    b) Se o delta calculado for negativo, a equação não possui raizes reais. Informe ao usuário e encerre o programa;
    c) Se o delta calculado for igual a zero a equação possui apenas uma raiz real; informe-a ao usuário;
    d) Se o delta for positivo, a equação possui duas raiz reais; informe-as ao usuário;

#### [Exercicio 17](2_Estrutura_Decisao/17_ano_bissexto.cpp)

Faça um Programa que peça um número correspondente a um determinado ano e em seguida informe se este ano é ou não bissexto.

#### [Exercicio 18](2_Estrutura_Decisao/18_verifica_data.cpp)

Faça um Programa que peça uma data no formato dd/mm/aaaa e determine se a mesma é uma data válida.

#### [Exercicio 19](2_Estrutura_Decisao/19_decomposicao_numerica.cpp)

Faça um Programa que leia um número inteiro menor que 1000 e imprima a quantidade de centenas, dezenas e unidades do mesmo.

Observando os termos no plural a colocação do "e", da vírgula entre outros. Exemplo:

    - 326 = 3 centenas, 2 dezenas e 6 unidades
    - 12 = 1 dezena e 2 unidades Testar com: 326, 300, 100, 320, 310,305, 301, 101, 311, 111, 25, 20, 10, 21, 11, 1, 7 e 16

#### [Exercicio 20](2_Estrutura_Decisao/20_media_tres_notas.cpp)

Faça um Programa para leitura de três notas parciais de um aluno. O programa deve calcular a média alcançada por aluno e apresentar:

    a) A mensagem "Aprovado", se a média for maior ou igual a 7, com a respectiva média alcançada;
    b) A mensagem "Reprovado", se a média for menor do que 7, com a respectiva média alcançada;
    c) A mensagem "Aprovado com Distinção", se a média for igual a 10.

#### [Exercicio 21](2_Estrutura_Decisao/21_caixa_eletronico.cpp)

Faça um Programa para um caixa eletrônico.

O programa deverá perguntar ao usuário a valor do saque e depois informar
quantas notas de cada valor serão fornecidas.

As notas disponíveis serão as de 1, 5, 10, 50 e 100 reais.
O valor mínimo é de 10 reais e o máximo de 600 reais.

O programa não deve se preocupar com a quantidade de notas existentes na
máquina.

Exemplo 1:
Para sacar a quantia de 256 reais, o programa fornece duas notas de 100,
uma nota de 50, uma nota de 5 e uma nota de 1;

Exemplo 2:
Para sacar a quantia de 399 reais, o programa fornece três notas de 100,
uma nota de 50, quatro notas de 10, uma nota de 5 e quatro notas de 1.

#### [Exercicio 22](2_Estrutura_Decisao/22_par_impar.cpp)

Faça um Programa que peça um número inteiro e determine se ele é par ou impar.
Dica: utilize o operador módulo (resto da divisão).

#### [Exercicio 23](2_Estrutura_Decisao/23_inteiro_decimal.cpp)

Faça um Programa que peça um número e informe se o número é inteiro ou decimal.
Dica: utilize uma função de arredondamento.

#### [Exercicio 24](2_Estrutura_Decisao/24_tres_operacoes.cpp)

Faça um Programa que leia 2 números e em seguida pergunte ao usuário qual
operação ele deseja realizar.

O resultado da operação deve ser acompanhado de uma
frase que diga se o número é:
par ou ímpar;
positivo ou negativo;
inteiro ou decimal.

#### [Exercicio 25](2_Estrutura_Decisao/25_detetive.cpp)

Faça um programa que faça 5 perguntas para uma pessoa sobre um crime.
As perguntas são:
"Telefonou para a vítima?"
"Esteve no local do crime?"
"Mora perto da vítima?"
"Devia para a vítima?"
"Já trabalhou com a vítima?"

O programa deve no final emitir uma classificação sobre a participação
da pessoa no crime.

Se a pessoa responder positivamente a 2 questões ela deve ser classificada
como "Suspeita", entre 3 e 4 como "Cúmplice" e 5 como "Assassino".
Caso contrário, ele será classificado como "Inocente".

#### [Exercicio 26](2_Estrutura_Decisao/26_posto_gasolina.cpp)

Um posto está vendendo combustíveis com a seguinte tabela de descontos:
Álcool:
até 20 litros, desconto de 3% por litro
acima de 20 litros, desconto de 5% por litro
Gasolina:
até 20 litros, desconto de 4% por litro
acima de 20 litros, desconto de 6% por litro

Escreva um algoritmo que leia o número de litros vendidos,
o tipo de combustível (codificado da seguinte forma: A-álcool, G-gasolina),
calcule e imprima o valor a ser pago pelo cliente sabendo-se que o preço do
litro da gasolina é R$ 2,50 o preço do litro do álcool é R$ 1,90.

#### [Exercicio 27](2_Estrutura_Decisao/27_macas_morangos.cpp)

Uma fruteira está vendendo frutas com a seguinte tabela de preços:

                      Até 5 Kg           Acima de 5 Kg

Morango R$ 2,50 por Kg R$ 2,20 por Kg
Maçã R$ 1,80 por Kg R$ 1,50 por Kg

Se o cliente comprar mais de 8 Kg em frutas ou o valor total da compra
ultrapassar R$ 25,00, receberá ainda um desconto de 10% sobre este total.

Escreva um algoritmo para ler a quantidade (em Kg) de morangos e a quantidade
(em Kg) de maças adquiridas e escreva o valor a ser pago pelo cliente.

#### [Exercicio 28](2_Estrutura_Decisao/28_hipermercado_tabajara.cpp)

O Hipermercado Tabajara está com uma promoção de carnes que é imperdível.
Confira:

                      Até 5 Kg           Acima de 5 Kg

File Duplo R$ 4,90 por Kg R$ 5,80 por Kg
Alcatra R$ 5,90 por Kg R$ 6,80 por Kg
Picanha R$ 6,90 por Kg R$ 7,80 por Kg

Para atender a todos os clientes, cada cliente poderá levar apenas um dos tipos
de carne da promoção, porém não há limites para a quantidade de carne
por cliente.

Se compra for feita no cartão Tabajara o cliente receberá ainda um desconto de
5% sobre o total da compra.

Escreva um programa que peça o tipo e a quantidade de carne comprada pelo
usuário e gere um cupom fiscal, contendo as informações da compra:
tipo de carne
quantidade de carne
preço total
tipo de pagamento
valor do desconto
valor a pagar.

### Estruturas de Repeticao

#### [Exercicio 01](3_Estrutura_Repeticao/01_nota_valida.cpp)

Faça um programa que peça uma nota, entre zero e dez.
Mostre uma mensagem caso o valor seja inválido e continue pedindo até que o
usuário informe um valor válido.

#### [Exercicio 02](3_Estrutura_Repeticao/02_usuario_senha.cpp)

Faça um programa que leia um nome de usuário e a sua senha e não aceite a senha
igual ao nome do usuário, mostrando uma mensagem de erro e voltando a
pedir as informações.

#### [Exercicio 03](3_Estrutura_Repeticao/03_valida_informacoes.cpp)

Faça um programa que leia e valide as seguintes informações:
Nome: maior que 3 caracteres;
Idade: entre 0 e 150;
Salário: maior que zero;
Sexo: 'f' ou 'm';
Estado Civil: 's', 'c', 'v', 'd';

#### [Exercicio 04](3_Estrutura_Repeticao/04_crescimento_populacao.cpp)

Supondo que a população de um país A seja da ordem de 80000 habitantes com uma
taxa anual de crescimento de 3% e que a população de B seja 200000 habitantes
com uma taxa de crescimento de 1.5%.

Faça um programa que calcule e escreva o número de anos necessários para que a
população do país A ultrapasse ou iguale a população do país B, mantidas as
taxas de crescimento.

#### [Exercicio 05](3_Estrutura_Repeticao/05_crescimento_populacao_input.cpp)

Altere o programa anterior permitindo ao usuário informar as populações e as
taxas de crescimento iniciais. Valide a entrada e permita repetir a operação.

#### [Exercicio 06](3_Estrutura_Repeticao/06_imprime_vinte_numeros.cpp)

Faça um programa que imprima na tela os números de 1 a 20, um abaixo do outro.
Depois modifique o programa para que ele mostre os números um ao lado do outro.

#### [Exercicio 07](3_Estrutura_Repeticao/07_maior_numero.cpp)

Faça um programa que leia 5 números e informe o maior número.

#### [Exercicio 08](3_Estrutura_Repeticao/08_soma_media.cpp)

Faça um programa que leia 5 números e informe a soma e a média dos números.

#### [Exercicio 09](3_Estrutura_Repeticao/09_impares_ate_50.cpp)

Faça um programa que imprima na tela apenas os números ímpares entre 1 e 50.

#### [Exercicio 10](3_Estrutura_Repeticao/10_imprime_intervalo.cpp)

Faça um programa que receba dois números inteiros e gere os números inteiros
que estão no intervalo compreendido por eles.

#### [Exercicio 11](3_Estrutura_Repeticao/11_intervalo_com_soma.cpp)

Altere o programa anterior para mostrar no final a soma dos números.

#### [Exercicio 12](3_Estrutura_Repeticao/12_gerador_tabuada.cpp)

Desenvolva um gerador de tabuada, capaz de gerar a tabuada de qualquer número
inteiro entre 1 a 10.
O usuário deve informar de qual numero ele deseja ver a tabuada.
A saída deve ser conforme o exemplo abaixo:
Tabuada de 5:
5 X 1 = 5
5 X 2 = 10
...
5 X 10 = 50

#### [Exercicio 13](3_Estrutura_Repeticao/13_potenciacao.cpp)

Faça um programa que peça dois números, base e expoente,
calcule e mostre o primeiro número elevado ao segundo número.
Não utilize a função de potência da linguagem.

#### [Exercicio 14](3_Estrutura_Repeticao/14_pares_impares.cpp)

Faça um programa que peça 10 números inteiros, calcule e mostre a quantidade de
números pares e a quantidade de números impares.

#### [Exercicio 15](3_Estrutura_Repeticao/15_fibonacci_1.cpp)

A série de Fibonacci é formada pela seqüência 1,1,2,3,5,8,13,21,34,55,...
Faça um programa capaz de gerar a série até o n−ésimo termo.

#### [Exercicio 16](3_Estrutura_Repeticao/16_fibonacci_ate_500.cpp)

A série de Fibonacci é formada pela seqüência 0,1,1,2,3,5,8,13,21,34,55,...
Faça um programa que gere a série até que o valor seja maior que 500.

#### [Exercicio 17](3_Estrutura_Repeticao/17_fatorial.cpp)

Faça um programa que calcule o fatorial de um número inteiro fornecido pelo
usuário. Ex.: 5!=5.4.3.2.1=120

#### [Exercicio 18](3_Estrutura_Repeticao/18_maior_menor_soma.cpp)

Faça um programa que, dado um conjunto de N números, determine o menor valor,
o maior valor e a soma dos valores.

#### [Exercicio 19](3_Estrutura_Repeticao/19_maior_menor_soma_menores_que_mil.cpp)

Altere o programa anterior para que ele aceite apenas números entre 0 e 1000.

#### [Exercicio 20](3_Estrutura_Repeticao/20_fatorial_ate_16.cpp)

Altere o programa de cálculo do fatorial, permitindo ao usuário calcular o
fatorial várias vezes e limitando o fatorial a números inteiros positivos e
menores que 16.

#### [Exercicio 21](3_Estrutura_Repeticao/21_primo.cpp)

Faça um programa que peça um número inteiro e determine se ele é ou não um
número primo. Um número primo é aquele que é divisível somente por ele mesmo
e por 1.

#### [Exercicio 22](3_Estrutura_Repeticao/22_primo_divisores.cpp)

Altere o programa de cálculo dos números primos, informando, caso o número não
seja primo, por quais número ele é divisível.

#### [Exercicio 23](3_Estrutura_Repeticao/23_primeiros_primos.cpp)

Faça um programa que mostre todos os primos entre 1 e N sendo N um número
inteiro fornecido pelo usuário.

O programa deverá mostrar também o número de divisões que ele executou para
encontrar os números primos.

Serão avaliados o funcionamento, o estilo e o número de testes (divisões)
executados.

#### [Exercicio 24](3_Estrutura_Repeticao/24_media_notas.cpp)

Faça um programa que calcule o mostre a média aritmética de N notas.

#### [Exercicio 25](3_Estrutura_Repeticao/25_media_idades.cpp)

Faça um programa que peça para n pessoas a sua idade, ao final o programa
deverá verificar se a média de idade da turma varia entre 0 e 25,26 e 60 e
maior que 60; e então, dizer se a turma é jovem, adulta ou idosa, conforme a
média calculada.

#### [Exercicio 26](3_Estrutura_Repeticao/26_eleicao.cpp)

Numa eleição existem três candidatos.
Faça um programa que peça o número total de eleitores.
Peça para cada eleitor votar e ao final mostrar o número de votos
de cada candidato.

#### [Exercicio 27](3_Estrutura_Repeticao/27_media_alunos.cpp)

Faça um programa que calcule o número médio de alunos por turma.
Para isto, peça a quantidade de turmas e a quantidade de
alunos para cada turma.
As turmas não podem ter mais de 40 alunos.

#### [Exercicio 28](3_Estrutura_Repeticao/28_media_cds.cpp)

Faça um programa que calcule o valor total investido por um colecionador em sua
coleção de CDs e o valor médio gasto em cada um deles.
O usuário deverá informar a quantidade de CDs e o valor para em cada um.

#### [Exercicio 29](3_Estrutura_Repeticao/29_tabela_199.cpp)

O Sr. Manoel Joaquim possui uma grande loja de artigos de R$ 1,99,
com cerca de 10 caixas.

Para agilizar o cálculo de quanto cada cliente deve pagar ele desenvolveu uma
tabela que contém o número de itens que o cliente comprou e ao lado
o valor da conta.

Desta forma a atendente do caixa precisa apenas contar quantos itens o cliente
está levando e olhar na tabela de preços.

Você foi contratado para desenvolver o programa que monta esta
tabela de preços, que conterá os preços de 1 até 50 produtos,
conforme o exemplo abaixo:

    Lojas Quase Dois - Tabela de preços
    1 - R$ 1.99
    2 - R$ 3.98
    ...
    50 - R$ 99.50

#### [Exercicio 30](3_Estrutura_Repeticao/30_preco_pao.cpp)

O Sr. Manoel Joaquim acaba de adquirir uma panificadora e pretende implantar a
metodologia da tabelinha, que já é um sucesso na sua loja de 1,99.

Você foi contratado para desenvolver o programa que monta a tabela de preços de
pães, de 1 até 50 pães, a partir do preço do pão informado pelo usuário,
conforme o exemplo abaixo:

    Preço do pão: R$ 0.18
    Panificadora Pão de Ontem - Tabela de preços
    1 - R$ 0.18
    2 - R$ 0.36
    ...
    50 - R$ 9.00

#### [Exercicio 31](3_Estrutura_Repeticao/31_caixa_registradora.cpp)

O Sr. Manoel Joaquim expandiu seus negócios para além dos negócios de 1,99 e
agora possui uma loja de conveniências.

Faça um programa que implemente uma caixa registradora rudimentar.

O programa deverá receber um número desconhecido de valores referentes aos
preços das mercadorias.

Um valor zero deve ser informado pelo operador para indicar o final da compra.

O programa deve então mostrar o total da compra e perguntar o valor em dinheiro
que o cliente forneceu, para então calcular e mostrar o valor do troco.

Após esta operação, o programa deverá voltar ao ponto inicial, para registrar a
próxima compra.

A saída deve ser conforme o exemplo abaixo:
Lojas Tabajara
Produto 1: R$ 2.20
Produto 2: R$ 5.80
Produto 3: R$ 0
Total: R$ 9.00
Dinheiro: R$ 20.00
Troco: R$ 11.00

#### [Exercicio 32](3_Estrutura_Repeticao/32_fatorial_descritiva.cpp)

Faça um programa que calcule o fatorial de um número inteiro fornecido pelo usuário.
Ex.: 5!=5.4.3.2.1=120. A saída deve ser conforme o exemplo abaixo:
Fatorial de: 5
5! = 5 . 4 . 3 . 2 . 1 = 120

#### [Exercicio 33](3_Estrutura_Repeticao/33_temperaturas.cpp)

O Departamento Estadual de Meteorologia lhe contratou para desenvolver um
programa que leia as um conjunto indeterminado de temperaturas,
e informe ao final a menor e a maior temperaturas informadas,
bem como a média das temperaturas.

#### [Exercicio 36](3_Estrutura_Repeticao/36_tabuada.cpp)

Desenvolva um programa que faça a tabuada de um número qualquer inteiro que
será digitado pelo usuário, mas a tabuada não deve necessariamente iniciar em 1
e terminar em 10, o valor inicial e final devem ser informados também pelo
usuário, conforme exemplo abaixo:

    Montar a tabuada de: 5
    Começar por: 4
    Terminar em: 7

    Vou montar a tabuada de 5 começando em 4 e terminando em 7:
    5 X 4 = 20
    5 X 5 = 25
    5 X 6 = 30
    5 X 7 = 35

Obs: Você deve verificar se o usuário não digitou o final menor que o inicial.

#### [Exercicio 37](3_Estrutura_Repeticao/37_academia.cpp)

Uma academia deseja fazer um senso entre seus clientes para descobrir o mais
alto, o mais baixo, a mais gordo e o mais magro, para isto você deve fazer um
programa que pergunte a cada um dos clientes da academia seu código,
sua altura e seu peso.

O final da digitação de dados deve ser dada quando o usuário digitar 0 (zero)
no campo código.

Ao encerrar o programa também deve ser informados os códigos e valores do
clente mais alto, do mais baixo, do mais gordo e do mais magro, além da média
das alturas e dos pesos dos clientes.

#### [Exercicio 38](3_Estrutura_Repeticao/38_salario_funcionario.cpp)

Um funcionário de uma empresa recebe aumento salarial anualmente.

Sabe-se que:
Esse funcionário foi contratado em 1995, com salário inicial de R$ 1.000,00;
Em 1996 recebeu aumento de 1,5% sobre seu salário inicial;
A partir de 1997 (inclusive), os aumentos salariais sempre correspondem ao
dobro do percentual do ano anterior.

Faça um programa que determine o salário atual desse funcionário.
Após concluir isto, altere o programa permitindo que o usuário digite o salário
inicial do funcionário.

#### [Exercicio 39](3_Estrutura_Repeticao/39_alunos.cpp)

Faça um programa que leia dez conjuntos de dois valores,
o primeiro representando o número do aluno e o segundo representando
a sua altura em centímetros.

Encontre o aluno mais alto e o mais baixo.

Mostre o número do aluno mais alto e o número do aluno mais baixo,
junto com suas alturas.

#### [Exercicio 40](3_Estrutura_Repeticao/40_acidentes_cidades.cpp)

Foi feita uma estatística em cinco cidades brasileiras para coletar dados sobre
acidentes de trânsito.

Foram obtidos os seguintes dados:
Código da cidade;
Número de veículos de passeio (em 1999);
Número de acidentes de trânsito com vítimas (em 1999).

Deseja-se saber:
Qual o maior e menor índice de acidentes de transito
e a que cidade pertence;
Qual a média de veículos nas cinco cidades juntas;
Qual a média de acidentes de trânsito nas cidades com menos de
2.000 veículos de passeio.

#### [Exercicio 41](3_Estrutura_Repeticao/41_tabela_juros.cpp)

Faça um programa que receba o valor de uma dívida e mostre uma tabela com os
seguintes dados: valor da dívida, valor dos juros, quantidade de parcelas e
valor da parcela.

Os juros e a quantidade de parcelas seguem a tabela abaixo:
Quantidade de Parcelas % de Juros sobre o valor inicial da dívida
1 0
3 10
6 15
9 20
12 25

Exemplo de saída do programa:
Valor da Dívida Valor dos Juros Quantidade de Parcelas Valor da Parcela
R$ 1.000,00 0 1 R$ 1.000,00
R$ 1.100,00 100 3 R$ 366,00
R$ 1.150,00 150 6 R$ 191,67

#### [Exercicio 42](3_Estrutura_Repeticao/42_numeros_intervalo.cpp)

Faça um programa que leia uma quantidade indeterminada de números positivos e
conte quantos deles estão nos seguintes intervalos:
[0-25], [26-50], [51-75] e [76-100].

A entrada de dados deverá terminar quando for lido um número negativo.

#### [Exercicio 43](3_Estrutura_Repeticao/43_lanchonete.cpp)

O cardápio de uma lanchonete é o seguinte:
Especificação Código Preço
Cachorro Quente 100 R$ 1,20
Bauru Simples 101 R$ 1,30
Bauru com ovo 102 R$ 1,50
Hambúrguer 103 R$ 1,20
Cheeseburguer 104 R$ 1,30
Refrigerante 105 R$ 1,00
Faça um programa que leia o código dos itens pedidos e as quantidades
desejadas.

Calcule e mostre o valor a ser pago por item (preço \* quantidade) e o total
geral do pedido.

Considere que o cliente deve informar quando o pedido deve ser encerrado.

#### [Exercicio 44](3_Estrutura_Repeticao/44_eleicao.cpp)

Em uma eleição presidencial existem quatro candidatos.
Os votos são informados por meio de código.
Os códigos utilizados são:
1, 2, 3, 4 - Votos para os respectivos candidatos
(você deve montar a tabela ex: 1 - Jose/ 2- João/etc)
5 - Voto Nulo
6 - Voto em Branco

Faça um programa que calcule e mostre:
O total de votos para cada candidato;
O total de votos nulos;
O total de votos em branco;
A percentagem de votos nulos sobre o total de votos;
A percentagem de votos em branco sobre o total de votos.

Para finalizar o conjunto de votos tem-se o valor zero.

#### [Exercicio 45](3_Estrutura_Repeticao/45_gabarito.cpp)

Desenvolver um programa para verificar a nota do aluno em uma prova com 10
questões, o programa deve perguntar ao aluno a resposta de cada questão e ao
final comparar com o gabarito da prova e assim calcular o total de acertos e a
nota (atribuir 1 ponto por resposta certa).

Após cada aluno utilizar o sistema deve ser feita uma pergunta se outro aluno
vai utilizar o sistema.

Após todos os alunos terem respondido informar:
Maior e Menor Acerto;
Total de Alunos que utilizaram o sistema;
A Média das Notas da Turma.
Gabarito da Prova:
01 - A
02 - B
03 - C
04 - D
05 - E
06 - E
07 - D
08 - C
09 - B
10 - A

Após concluir isto você poderia incrementar o programa permitindo que o
professor digite o gabarito da prova antes dos alunos usarem o programa.

#### [Exercicio 46](3_Estrutura_Repeticao/46_salto.cpp)

Em uma competição de salto em distância cada atleta tem direito a cinco saltos.
No final da série de saltos de cada atleta, o melhor e o pior resultados são
eliminados.

O seu resultado fica sendo a média dos três valores restantes.
Você deve fazer um programa que receba o nome e as cinco distâncias alcançadas
pelo atleta em seus saltos e depois informe a média dos saltos conforme a
descrição acima informada (retirar o melhor e o pior salto e depois
calcular a média).

Faça uso de uma lista para armazenar os saltos.
Os saltos são informados na ordem da execução, portanto não são ordenados.
O programa deve ser encerrado quando não for informado o nome do atleta.
A saída do programa deve ser conforme o exemplo abaixo:
Atleta: Rodrigo Curvêllo

    Primeiro Salto: 6.5 m
    Segundo Salto: 6.1 m
    Terceiro Salto: 6.2 m
    Quarto Salto: 5.4 m
    Quinto Salto: 5.3 m

    Melhor salto:  6.5 m
    Pior salto: 5.3 m
    Média dos demais saltos: 5.9 m

    Resultado final:
    Rodrigo Curvêllo: 5.9 m

#### [Exercicio 47](3_Estrutura_Repeticao/47_ginastica.cpp)

Em uma competição de ginástica, cada atleta recebe votos de sete jurados.
A melhor e a pior nota são eliminadas.
A sua nota fica sendo a média dos votos restantes.

Você deve fazer um programa que receba o nome do ginasta e as notas dos sete
jurados alcançadas pelo atleta em sua apresentação e depois informe a sua
média, conforme a descrição acima informada (retirar o melhor e o pior salto e
depois calcular a média com as notas restantes).

As notas não são informados ordenadas.
Um exemplo de saída do programa deve ser conforme o exemplo abaixo:
Atleta: Aparecido Parente
Nota: 9.9
Nota: 7.5
Nota: 9.5
Nota: 8.5
Nota: 9.0
Nota: 8.5
Nota: 9.7

    Resultado final:
    Atleta: Aparecido Parente
    Melhor nota: 9.9
    Pior nota: 7.5
    Média: 9,04

#### [Exercicio 48](3_Estrutura_Repeticao/48_numero_invertido.cpp)

Faça um programa que peça um numero inteiro positivo e em seguida mostre este
numero invertido.
Exemplo:
12376489
=> 98467321

#### [Exercicio 49](3_Estrutura_Repeticao/49_serie.cpp)

Faça um programa que mostre os n termos da Série a seguir:
S = 1/1 + 2/3 + 3/5 + 4/7 + 5/9 + ... + n/m.
Imprima no final a soma da série.

#### [Exercicio 50](3_Estrutura_Repeticao/50_serie2.cpp)

Sendo H= 1 + 1/2 + 1/3 + 1/4 + ... + 1/N,
Faça um programa que calcule o valor de H com N termos.

### Listas

#### [Exercicio 01](4_Listas/01_cinco_numeros.cpp)

Faça um Programa que leia um vetor de 5 números inteiros e mostre-os.

#### [Exercicio 02](4_Listas/02_dez_numeros.cpp)

Faça um Programa que leia um vetor de 10 números reais
e mostre-os na ordem inversa.

#### [Exercicio 03](4_Listas/03_notas.cpp)

Faça um Programa que leia 4 notas, mostre as notas e a média na tela.

#### [Exercicio 04](4_Listas/04_consoantes.cpp)

Faça um Programa que leia um vetor de 10 caracteres,
e diga quantas consoantes foram lidas. Imprima as consoantes.

#### [Exercicio 05](4_Listas/05_numeros_pares_impares.cpp)

Faça um Programa que leia 20 números inteiros e armazene-os num vetor.
Armazene os números pares no vetor PAR e os números IMPARES no vetor impar.
Imprima os três vetores.

#### [Exercicio 06](4_Listas/06_notas_dez_alunos.cpp)

Faça um Programa que peça as quatro notas de 10 alunos,
calcule e armazene num vetor a média de cada aluno, imprima o
número de alunos com média maior ou igual a 7.0.

#### [Exercicio 07](4_Listas/07_vetor_inteiros.cpp)

Faça um Programa que leia um vetor de 5 números inteiros,
mostre a soma, a multiplicação e os números.

#### [Exercicio 08](4_Listas/08_idade_altura.cpp)

Faça um Programa que peça a idade e a altura de 5 pessoas,
armazene cada informação no seu respectivo vetor.
Imprima a idade e a altura na ordem inversa a ordem lida.

#### [Exercicio 09](4_Listas/09_soma_quadrados.cpp)

Faça um Programa que leia um vetor A com 10 números inteiros,
calcule e mostre a soma dos quadrados dos elementos do vetor.


#### [Exercicio 10](4_Listas/10_tres_vetores.cpp)

Faça um Programa que leia dois vetores com 10 elementos cada.
Gere um terceiro vetor de 20 elementos, cujos valores deverão ser
compostos pelos elementos intercalados dos dois outros vetores.

#### [Exercicio 11](4_Listas/11_quatro_vetores.cpp)

Altere o programa anterior, intercalando 3 vetores de 10 elementos cada.

#### [Exercicio 12](4_Listas/12_alunos_altos.cpp)

Foram anotadas as idades e alturas de 30 alunos.
Faça um Programa que determine quantos alunos com mais de 13 anos
possuem altura inferior à média de altura desses alunos.

#### [Exercicio 13](4_Listas/13_temperaturas.cpp)

Faça um programa que receba a temperatura média de cada mês do ano e
armazene-as em uma lista. Após isto, calcule a média anual das 
temperaturas e mostre todas as temperaturas acima da média anual, 
se em que mês elas ocorreram
(mostrar o mês por extenso: 1 – Janeiro, 2 – Fevereiro, . . . ).

#### [Exercicio 14](4_Listas/14_detetive.cpp)

Utilizando listas faça um programa que faça 5 perguntas
para uma pessoa sobre um crime.

As perguntas são:

    a) "Telefonou para a vítima?"
    b) "Esteve no local do crime?"
    c) "Mora perto da vítima?"
    d) "Devia para a vítima?"
    e) "Já trabalhou com a vítima?"

O programa deve no final emitir uma classificação sobre a
participação da pessoa no crime. Se a pessoa responder positivamente
a 2 questões ela deve ser classificada como "Suspeita",
entre 3 e 4 como "Cúmplice" e 5 como "Assassino".
Caso contrário, ele será classificado como "Inocente".

#### [Exercicio 15](4_Listas/15_relatorio_notas.cpp)

Faça um programa que leia um número indeterminado de valores,
correspondentes a notas, encerrando a entrada de dados quando for
informado um valor igual a -1 (que não deve ser armazenado).

Após esta entrada de dados, faça:

a) Mostre a quantidade de valores que foram lidos;
b) Exiba todos os valores na ordem em que foram informados, um ao lado do outro;
c) Exiba todos os valores na ordem inversa à que foram informados, um abaixo do outro;
d) Calcule e mostre a soma dos valores;
e) Calcule e mostre a média dos valores;
f) Calcule e mostre a quantidade de valores acima da média calculada;
g) Calcule e mostre a quantidade de valores abaixo de sete;
h) Encerre o programa com uma mensagem;


#### [Exercicio 16](4_Listas/16_vendedores.cpp)

Utilize uma lista para resolver o problema a seguir.
Uma empresa paga seus vendededores com base em comissoes. O vendedor
recebe $200 por semana mais 9 por cento de suas vendas brutas daquela semana.
Por exemplo, um vendedor que teve vendas brutas e $3000 em uma semana
recebe $200 mais 9 por cento de $3000, ou seja, um total de $470.
Escreva um programa (usando um array de contadores) que determine
quantos vendedores receberam salários nos seguintes intervalos de valores:

    a) $200 - $299
    b) $300 - $399
    c) $400 - $499
    d) $500 - $599
    e) $600 - $699
    f) $700 - $799
    g) $800 - $899
    h) $900 - $999
    i) $1000 em diante

Desafio: Crie uma fórmula para chegar na posição da lista a partir do salário,
sem fazer vários ifs aninhados.

#### [Exercicio 17](4_Listas/17_saltos.cpp)

Em uma competição de salto em distância cada atleta tem direito a cinco saltos.
O resultado do atleta será determinado pela média dos cinco valores restantes.
Você deve fazer um programa que receba o nome e as cinco distâncias alcançadas
pelo atleta em seus saltos e depois informe o nome, os saltos e a média dos saltos.

O programa deve ser encerrado quando não for informado o nome do atleta.
A saída do programa deve ser conforme o exemplo abaixo:

    Atleta:             Rodrigo Curvêllo
    Primeiro Salto:     6.5m
    Segundo Salto:      6.1m
    Terceiro Salto:     6.2m
    Quarto Salto:       5.4m
    Quinto Salto:       5.3m

    Resultado final:

    Atleta:             Rodrigo Curvêllo
    Saltos: 6.5 - 6.1 - 6.2 - 5.4 - 5.3
    Média dos saltos: 5.9m

#### [Exercicio 18](4_Listas/18_melhor_atleta.cpp)

Uma grande emissora de televisão quer fazer uma enquete entre
os seus telespectadores para saber qual o melhor jogador após cada jogo.
Para isto, faz-se necessário o desenvolvimento de um programa,
que será utilizado pelas telefonistas, para a computação dos votos.
Sua equipe foi contratada para desenvolver este programa utilizando
a linguagem de programação C++. Para computar cada voto, a telefonista
digitará um número, entre 1 e 23, correspondente ao numero da camisa
do jogador igual zero, indica que a votação foi encerrada. Se um número
inválido for digitado, o programa deve ignorá-lo, mostrando uma breve mensagem
de aviso, e voltando a pedir outro número.
Após o final da votação, o programa deverá exibir:

    a) O total de votos computados;
    b) Os números e respectivos jogadores que receberam votos;
    c) O percentual de votos de cada um destes jogadores;
    d) O número do jogador escolhido como o melhor jogador da partida, juntamente com o
    número de votos e o percentual de votos dados a ele.

#### [Exercicio 19](4_Listas/19_sistemas_operacionais.cpp)

Uma empresa de pesquisas precisa tabular os resultados de seguinte
enquete feita a uma grande quantidade de organizações:

"Qual o melhor Sistema Operacional para uso em servidores?"

As possíveis respostas são:

    1 - Windows Server
    2 - Unix
    3 - Linux
    4 - Netware
    5 - Mac OS
    6 - Outro

Você foi contratado para desenvolver um programa que leia o resultado da
enquete e informe ao final o resultado da mesma. O programa deverá
ler os valores até ser informado o valor 0, que encerra a entrada de dados.
Não deverão ser aceitos valores além dos válidos para o programa (0 a 6).
Os valores referentes a cada uma das opções devem ser armazenados num vetor.
Após os dados terem sido completamente informados, o programa deverá calcular
o percentual de cada um dos concorrentes e informar o vencedor da enquete.

#### [Exercicio 20](4_Listas/20_abono_tabajara.cpp)

As Organizações Tabajara resolveram dar um abono aos seus colaboradores
em reconhecimento ao bom resultado alcançado durante o ano que passou.
Para isto contratou você para desenvolver a aplicação que servirá como
uma projeção de quanto será gasto com o pagamento deste abono.

Após reuniões envolvendo a diretoria executiva, a diretoria financeira
e os representantes do sindicato laboral, chegou-se a seguinte forma de cálculo:

I) Cada funcionário receberá o equivalente a 20% do seu salário bruto de dezembro;

O piso do abono será de 100 reais, isto é, aqueles funcionários cujo salário
for muito baixo, recebem este valor mínimo. Neste momento, não se deve ter
nenhuma preocupação com colaboradores com menor tempo de casa, descontos,
impostos ou outras particularidades. Seu programa deverá permitir a digitação
do salário de um número indefinido (desconhecido) de salários. Um valor de
salário igual a 0 (zero) encerra a digitação. Após a entrada de todos os dados
o programa deverá calcular o valor do abono concedido a cada colaborador,
de acordo com a regra definida acima. Ao final, o programa deverá apresentar:

    a) O salário de cada funcionário, juntamente com o valor do abono;
    b) O número total de funcionário processados;
    c) O valor total a ser gasto com o pagamento do abono;
    d) O número de funcionários que receberá o valor mínimo de 100 reais;
    e) O maior valor pago como abono;

#### [Exercicio 21](4_Listas/21_consumo_carros.cpp)

Faça um programa que carregue uma lista com os modelos de cinco carros
(exemplo de modelos: FUSCA, GOL, VECTRA etc). Carregue uma outra lista
com o consumo desses carros, isto é, quantos quilômetros cada um desses
carros faz com um litro de combustível. Calcule e mostre:

a) O modelo do carro mais econômico;
b) Quantos litros de combustível cada um dos carros cadastrados consome para percorrer
uma distância de 1000 quilômetros e quanto isso custará, considerando que a gasolina custe
R$ 2,25 o litro.

#### [Exercicio 22](4_Listas/22_mouses.cpp)

Sua organização acaba de contratar um estagiário para trabalhar no Suporte
de Informática, com a intenção de fazer um levantamento nas sucatas encontradas
nesta área. A primeira tarefa dele é testar todos os cerca de 200 mouses que
se encontram lá, testando e anotando o estado de cada um deles,
para verificar o que se pode aproveitar deles.

Foi requisitado que você desenvolva um programa para registrar este levantamento.
O programa deverá receber um número indeterminado de entradas, cada uma contendo:

    a) Um número de identificação do mouse;
    b) O tipo de defeito: (necessita da esfera, necessita de limpeza, necessita troca do
    cabo ou conector quebrado ou inutilizado);
    c) Uma identificação igual a zero encerra o programa.


#### [Exercicio 23](4_Listas/23_espaco_disco.cpp)

A ACME Inc, uma empresa de 500 funcionários, está tendo problemas de
espaço em disco no seu servidor de arquivos. Para tentar resolver este
problema, o Administrador de Rede precisa saber qual o espaço ocupado
pelos usuários, e identificar os usuários com maior espaço ocupado.
Através de um programa, baixado da Internet, ele conseguiu
gerar o seguinte arquivo, chamado "usuarios.txt":

    alexandre (456123789 bytes)
    anderson  (1245698456 bytes)
    antonio   (123456456 bytes)
    carlos    (91257581 bytes)
    cesar     (987458 bytes)
    rosemary  (789456125 bytes)

Neste arquivo, o nome do usuário possui 15 caracteres. A partir deste arquivo, você deve criar
um programa que gere um relatório, chamado "relatorio.txt".

#### [Exercicio 24](4_Listas/24_dados.cpp)

Faça um programa que simule um lançamento de dados.
Lance o dado 100 vezes e armazene os resultados em um vetor.
Depois, mostre quantas vezes cada valor foi conseguido.

Dica: Use um vetor de contadores (1-6) e uma função para gerar
numeros aleatórios, simulando os lançamentos dos dados.

