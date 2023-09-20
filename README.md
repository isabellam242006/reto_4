# RETO 4

*- 1. Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.*
```
numero_entero: int
numeros_vocales = [97, 101, 105, 111, 117]  #Lista de números que corresponden al código ASCII de vocales minúsculas

a = int(input("Ingrese un número entero cualquiera: "))
if a in numeros_vocales:                    #Si "a" corresponde a cualquiera de esos números entonces:
  print("El número " + str(a) + " equivale a una vocal minúscula en código ASCII")
else:                                       #Si no:
  print("El número " + str(a) + " no equivale a una vocal minúscula en código ASCII")
```
*- 2. Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.*

```letra: str
letra = str(input("ingrese una letra cualquiera(solo 1 caracter): "))

if ord(letra)%2==0:      #ord devuelve el código ASCII de cualquier caracter. Si el módulo entre el código y 2 es 0, entonces:
  print(letra + " pertenece a un código ASCII par")
else:                    #Si no:
  print(letra + " pertenece a un código ASCII impar")
```
     
*- 3. Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.*

```
caracter: str
caracter = str(input("ingrese un caracter: "))
if 48<= ord(caracter)<=57:                 #Los códigos ASCII del 48 al 57 pertenecen a los dígitos (Números del 0 al 9)
  print("Usted ha ingresado un dígito")    #Si el caracter ingresado está dentro del rango, entonces se trata de un dígito
else:                                      #De lo contrario:
  print("Usted no ha ingresado un dígito")
```
*- 4. Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación*:

-**Positivo**: *"El número x es positivo"*

-**Negativo**: *"El número x es negativo"*

-**Cero (0)**: *"El número x es el neutro para la suma"*

```
x : float
x = float(input("Ingrese un número cualquiera: "))
if x > 0:
  print("el número " + str(x) + " es positivo")
elif x == 0:
  print("el número " + str(x) + " es neutro para la suma")
else:
  print("el número " + str(x) + " es negativo")
```
*- 5. Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.*

```
centro_x: float
centro_y: float
radio: float
coordenada_x : float
coordenada_y : float

centro_x = float(input("Ingrese un número para la coordenada x del centro del círculo: "))
centro_y = float(input("Ingrese un número para la coordenada y del centro del círculo: "))
radio = float(input("Ingrese un número positivo para el radio del círculo: "))
coordenada_x = float(input("Ingrese un número para una coordenada x cualquiera: "))
coordenada_y = float(input("Ingrese un número para una coordenada y cualquiera: "))

if ((coordenada_x - centro_x)**2 + (coordenada_y - centro_y)**2)**0.5 < radio:  #Si la distancia entre el centro y el punto es menor que el radio, entonces:
                     print("El punto está dentro del círculo")
else:                                                                           #Si no:
                     print("El punto no está dentro del círculo")
```
*- 6. Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.*

```
a: float
b: float
c: float

a = float(input("ingrese una longitud(número positivo): "))
b = float(input("ingrese otra longitud(número positivo): " ))
c = float(input("ingrese una tercera longitud(número positivo): "))

if a + b > c and a + c > b and b + c > a :  #Si se cumple que la suma de dos longitudes es mayor que la tercera longitud, entonces:
  print("Se puede formar un triángulo")
else:                                       #Si no:
  print("No se puede formar un triángulo")
```

     

