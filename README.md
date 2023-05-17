# funcion con parametros 

#funcion para multiplicar dos numeros:
def multiplicacion(valor1, valor2):
    resultado = valor1 * valor2
    return resultado

#funcion para sumar dos numeros:
def suma(num1, num2):
    resultado = num1 + num2
    return resultado

#funcion para sacar el promedio de dos numeros:
def promedio (a, b):
    suma = a + b
    resultado = suma / 2
    return resultado

#funcion para convertir grados Fahrenheit a celsius:
def convertir(fahrenheit):
    celsius = (fahrenheit - 32) * 5/9
    return celsius

#funcion para calcular el factorial de un numero:
def factorial(numero):
    if numero == 0:
        return 1
    else:
        return numero * factorial (numero - 1)
    

# funcion sin parametos:
 

 #funcion para imprimir el mensaje "Te quiero :)"
def imprimir_mensaje ():
    print("Te quiero :)")

#funcion para el mensaje "Bienvenido/a a Python"
def bienvenida():
    print("Bienvenido/a a Python")

#funcion para imprimir la fecha y hora actual:
def fecha_hora_hoy():
    import datetime
    now= datetime.datetime.now()
    print("fecha y hora actual", now)

#función para imprimir una lista de numeros del 1 al 10
def imprimir():
    for i in range (1,11):
        print(i)

#función para imprimir un triangulo de asteriiscos:
def imprimir_triangulo():
    for i in range (1,6):
        print("*")

imprimir_triangulo()

#función con parametros predeterminados:


#función que calcula el área de un rectángulo:
def area_rectangulo(base=4, altura=6):
    return base * altura

#función que imprime un mensaje:
def saludar(nombre="Profe"):
    print("Hola", nombre, "¡bienvenida!")

#función que eleva un número a una potencia:
def potencia(numero, exponente=2):
    return numero**exponente

#función que calcula el descuento aplicado un precio:
def calcular_descuento(precio, porcentaje_descuento=10)
    descuento  =precio * porcentaje_descuento / 100
    return descuento 

#función que suma 5 numeros:
def sumar(a=6, b=8, c=3, d=9, e=2):
    return a+b+c+d+e
