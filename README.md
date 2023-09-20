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
Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.

```letra: str
letra = str(input("ingrese una letra cualquiera(solo 1 caracter): "))

if ord(letra)%2==0:      #ord devuelve el código ASCII de cualquier caracter. Si el módulo entre el código y 2 es 0, entonces:
  print(letra + " pertenece a un código ASCII par")
else:                    #Si no:
  print(letra + " pertenece a un código ASCII impar")
```
     
Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

```
caracter: str
caracter = str(input("ingrese un caracter: "))
if 48<= ord(caracter)<=57:                 #Los códigos ASCII del 48 al 57 pertenecen a los dígitos (Números del 0 al 9)
  print("Usted ha ingresado un dígito")    #Si el caracter ingresado está dentro del rango, entonces se trata de un dígito
else:                                      #De lo contrario:
  print("Usted no ha ingresado un dígito")
```
     

