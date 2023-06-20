# Exercicio036.py

valor = float(input('Didite o valor da casa: '))
salario = float(input('Digite salario: '))
anos = int(input('Quantos anos quer pagar: '))

prestacao = valor / (anos *12)
minimo = salario * 30 / 100
if prestacao <= minimo:
    print('Aprovado')
print('Prestação de:',prestacao)
