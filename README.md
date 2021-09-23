import numpy
import random
numeros1=set()
numeros2=set()
for n in range (0,5):
    num=numpy.random.randint(10)
    num1=numpy.random.randint(10)
    n+=1
    numeros1.add(num)
    numeros2.add(num1)
union=numeros1.union(numeros2)
inter=numeros1.intersection(numeros2)
dif=numeros1.difference(numeros2)
dif_sim=numeros1.symmetric_difference(numeros2)
print("el conjunto 1 es: ",numeros1)
print("el conjunto 2 es: ",numeros2)
print("la union de los conjuntos es: ",union)
print("la interseccion de los conjuntos es: ",inter)
print("la diferencia de los conjuntos es: ", dif)
print("la diferencia simetrica de los conjuntos es: ", dif_sim)
