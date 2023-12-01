# apuntes-python
Mis apuntes de python.

## Función "Print"
La función `print()` se encarga de imprimir por pantalla.

Por ejemplo:
```python
print("Hola qué tal?")
```
Podemos concatenar cadenas de caracteres.
```python
print("Hola", "qué tal?")
print("Hola" + "Dani")
```

## Función "Input"
La función `input()` nos permite introducir información a través del teclado. Podemos utilizarlo sin indicar nada dentro de los paréntesis.
```python
print("Introduce tu nombre")
input()
```
Si escribimos dentro de los paréntesis, podemos mostrar indormación antes de escribir:
```python
input("Introduce tu nombre")
```

## Variables
Las variables nos permiten guardar en ellas información. Hay muchos tipos de variables.

* **Enteros**: 5
* **Strings**: "Jordi"
* **Booleanos**: True, False

Las variables tienen un nombre que las identifica. Por ejemplo:
```python
Edad = 20
Nombre = "Jordi"
Vivo = True
```
Para imprimir una variable, indicamos su nombre si comillas:
```python
nombre = "Jordi"
print(nombre)
```
El signo igual asigna un valor a la variable.

Un ejemplo completo:
```python
nombre = input("Cuál es tu nombre? ")
```
Si queremos convertir el resultado de un input en un número utilizamos la función:
```python
edad = int(input("Dime tu edad: "))
print(edad + 5)
```

## Condicionales
Para decidir ejecutar o no un bloque de código en función de si se cumple o no una condición, utilizamos: `if`:
```python
edad = 18
if edad >= 18:
    print("Es mayor de edad.")
```
También podemos usar `else` para cuando la condición no se cumpla:
```python
edad = 18
if edad >= 18:
    print("Es mayor de edad.")
else:
    print("Es menor de edad.")
```

## Bucles
Los bucles nos permiten repetir un bloque de código más de una vez.

Un ejemplo es el bucle `for`:
```python
for numero in (0, 5):
    print(numero)
```

También podemos recorrer una lista:
```python
alumnos = ["Pepe", "Manolo", "Juan"]
for alumno in alumnos:
    print(alumno)
```

## Funciones
Las funciones nos permiten guardar un bloque de código con un nombre para llamarlas cuando queramos.

Recordad que las funciones terminan en paréntesis:
`sumar()`, `jugar()`, etc.

Ejemplo:
```python
def calcular():
    
```