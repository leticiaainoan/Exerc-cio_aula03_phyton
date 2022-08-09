# Exerc-cio_aula03_phyton

import math

peso = float(input(
    "Digite seu peso"
))

altura = float(input(
    "Digite suaaltura"
))


print("o peso digitado foi %s,A altura digitada %s" %(peso,altura))

imc = peso/altura**2 

print(imc < 17, "Muito abaixo do peso")

print(imc > 17 and imc < 18.5,"Abaixo do peso normal")

print(imc > 18.5 and imc < 25,"Peso dentro do normal")

print(imc > 25 and imc < 30,"Peso acima do normal")

print(imc > 30,"peso muito acima do normal")
