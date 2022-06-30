# Codigo1010becrowd
linha1= input(print("Digite o código, a quantidade e o valor da peça que deseja adquirir")).split()
linha2= input(print("Digite o outro código, a quantidade e o valor da peça que deseja adquirir")).split()

codg1=(linha1[0])
quantd1=(linha1[1])
valor1=(linha1 [2])
codg2=(linha2 [0])
quantd2=(linha2 [1])
valor2=(linha2 [2])
total = (int(quantd1) * float(valor1)) + (int(quantd2) * float(valor2))
print("Valor a ser pago: R$ %0.2f" %total
#na variáveis das linhas eu fiz com que a pessoa que fosse utilzar a programção declarasse o código da peça, a quantidade da mesma e o valor da peça separando estes números por meio do split.
# posteriormente eu fiz a associação das três variáveis coma a linha específica dos números utilizando o "[]".
# e por último, usando outra variável eu fiz a junção dos valores utilizando o int para o inteiro e o float para o valor decimal utilizando a operação da multiplicação. Depois disso utlizei o print para informar o valor dado no final.
