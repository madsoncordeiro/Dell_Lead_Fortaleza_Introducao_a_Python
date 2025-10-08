# Aula 1.2 - Atribuindo valores a variáveis corretamente

Durante a aula, você aprendeu como fazer entrada e saída de dados, além de como ler strings e convertê-los para números. Nesta oficina, você deve construir um programa Python que faz a leitura do nome, da idade, do peso e da altura de uma pessoa, e calcula o Índice de Massa Corporal (IMC) dela. O IMC é uma medida internacionalmente aceita, que calcula se uma pessoa pode ter problemas de peso ou não. Sabendo disso, o IMC é calculado da seguinte forma:

IMC = peso/(altura*altura)

ou

IMC = peso/altura2

Ambas as fórmulas são iguais. Dessa forma, seu programa vai ajudar os usuários a calcularem o IMC deles. Ele deve receber como entrada de dados, o nome da pessoa, o peso e a altura. Depois, ele deve calcular o IMC e apresentar este valor na tela para o usuário. Logo abaixo está o cálculo do IMC já pronto para você utilizá-lo. Assumindo que as variáveis com os valores numéricos de peso e altura foram nomeadas como peso_float e altura_float, o código para calcular o IMC é:

altura_ao_quadrado = altura_float * altura_float
imc = peso_float / altura_ao_quadrado

Após este cálculo, imprima uma linha contendo o IMC da pessoa.

DESAFIO: foi discutido em aula como converter de uma string, ou seja, o tipo str, para um float. Como fazer o caminho inverso, converter de um float para str? Reflita um pouco e tente não só apresentar o valor numérico como escrever algum texto que auxilie a leitura do usuário.