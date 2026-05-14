# calculadoraprint("ola, mundo!")
nome = input("digite seu nome: ")
print("bem-vindo,",nome)
num1 = float(input("digite o primeiro numero: "))
num2 = float(input("digite o segundo numero: "))
soma = num1 + num2
sub = num1 - num2
mult = num1 * num2
print("soma:", soma)
print("subtração:", sub)
print("multiplicação:", mult)
if num2 != 0:
  div = num1 / num2
  print("divisão:", div)
else:
  print("não é possivel dividir por zero")
