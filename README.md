import random

numero_secreto = random.randint(1, 2)

print("Adivina el número entre 1 y 2:")
adivinanza = int(input())

if adivinanza == numero_secreto:
    print("¡Felicidades! Adivinaste el número.")
else:
    print(f"Lo siento, has perdido. El número era {numero_secreto}.")
    3
