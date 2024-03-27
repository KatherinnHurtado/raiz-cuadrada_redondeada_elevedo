# raiz-cuadrada_redondeada_elevada
#En este repositorio encontraras un codigo que elige un numero entre: 1 y 1000 de forma aleatoria, en donde: si el numero es par le hallara la raiz y la redondeara al entero mas cercano, pero si es impar, elevara el numero al cuadrado 
print('-------------------------------------------------')

import random 
WF = random.randint(1,1000)
print("The randomly selected number is: ")
print(WF)
print('-------------------------------------------------')

if WF % 2 == 0:
    print("The number is even: ")
    
else:
    print("The number is odd: ")

print('-------------------------------------------------')

if WF % 2 == 0:
    print("The square root of the number is: ")
    import math
    WF = math. sqrt(WF)
    print(WF)
    print('-------------------------------------------------')
    
    print("The number rounded to the nearest integer is: ")
    print(round(WF,0))
    print('-------------------------------------------------')

else: 
    print("The number squared results in: ")
    print(pow(int(WF),2)) 
