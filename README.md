# atividade-4
fatorial recursiva

import random

def fatorial(n):

    if n == 0 or n == 1:
        return 1
    else:
        return n * fatorial(n - 1)

numero_aleatorio = random.randint(1, 100)

print("Número aleatório:", numero_aleatorio)

resultado = fatorial(numero_aleatorio)

print(f'O fatorial de {numero_aleatorio} é {resultado}')
