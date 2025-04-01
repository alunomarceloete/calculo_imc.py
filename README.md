# Cálculo de IMC (Índice de massa corporal) utilizando a linguagem python.

# Código utilizado
nome = input('Digite o seu nome: ')
peso = float(input('Informe seu peso: '))
altu = float(input('Informe sua altura: '))
calc = peso / altu**2
print('Seu IMC é: ', calc)
