# reto_4

Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
```
numero_entero: int
numeros_vocales = [97, 101, 105, 111, 117]  #Lista de números que corresponden al código ASCII de vocales minúsculas

a = int(input("Ingrese un número entero cualquiera: "))
if a in numeros_vocales:                    #Si "a" corresponde a cualquiera de esos números entonces:
  print("El número " + str(a) + " equivale a una vocal minúscula en código ASCII")
else:                                       #Si no:
  print("El número " + str(a) + " no equivale a una vocal minúscula en código ASCII")
```
     
