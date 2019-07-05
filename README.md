# programacionBasica
enseñar lo basico de la programación 

# ¿Qué es Python?


Python es un lenguaje de scripting independiente de plataforma y orientado a objetos, preparado para realizar cualquier tipo de programa, desde aplicaciones Windows a servidores de red o incluso, páginas web. Es un lenguaje interpretado, lo que significa que no se necesita compilar el código fuente para poder ejecutarlo, lo que ofrece ventajas como la rapidez de desarrollo e inconvenientes como una menor velocidad. 

###Print
El primer programa que vamos a escribir en Python es el clásico"Hola mundo" y en este lenguaje es tan simple como:

print("Hola mundo")

Crea un programa que despliegue su nombre y su dirección, tal que y como lo veria en un sobre de una carta: 

nombre='Gonzalez Ramos Anibal'

calle='Carrera Naucalpan Toluca #794'

colonia='San Rafael Chamapa'

municipio='Naucalpan'

estado='Estado de Mexico'

cp=53660

print(nombre +'\n'+ calle +'\n'+ colonia +'\n'+ municipio +'\n'+ estado +'\n' cp)

###input

input se utiliza para que el programa haga una pregunta y luego con un mensaje de 

Hola + nombre 

La variable de un tipo flotante puede guardar datos numéricos con punto decimal para forzar una variable que sea flotante ocupando el formato:

ejemplos:

1.- n=int(input('numero :'))


s=int((n*(n+1))/2)

print('El resultado es ', s)

2.- w=int(input('Indique el numero de widget :'))

g=int(input('Indique el numero de gizmos :'))

p1=w*75

p2=g*112

pt=int(p1+p2)

print('El peso total de los productos adquiridos es de ', pt , 'gramos')

###Float 

argo=float(input('Cual es el largo de una cancha de fubol? '))

ancho=float(input('Cual es el ancho de una chancha de futbol? '))

area_metros=largo*ancho

area=float(area_metros*0.000247105)

print('El area de la cancha de futbol es de', area, 'en acres')

ejemplos:

1.- s=float(input('Indique la cantidad de saldo que tiene la cuenta :'))

s1=float(s*0.4)+s

s2=float((s*0.4)*2)+s

s3=float((s*0.4)*3)+s

print(' El saldo que se tendra en la primer aunalidad es de ', s1 , 'pesos','\n',
'El saldo que se tendra en la segunda aunalidad es de ', s2, 'pesos','\n',
'El saldo que se tendra en la tercera aunalidad es de ', s3, 'pesos')

2.- import math
r=float(input('Indique el radio de un circulo :'))

p=math.pi

a=p*(r**2)

v=((4/3)*p*(r**3))

print('El area de un circulo es ',"{:.2f}".format(a),'\n', 'El volumen de una esfera es ',"{:.2f}".format(v))

3.- #ESCRIBA UN PREOGRAMA QUE LE DIGA AL USUARIO EL NUMERO DE DIAS, HORAS, MINUTOS Y SEGUNDOS, EL PREOGRAMA DEBE CALCULAR Y DESPLEGAR EL NUMERO DE SEGINDOS TOTALES

print('Llene los siguientes datos.')

d=float(input('Cuantos dias '))

h=float(input('Cuantas horas '))

m=float(input('Cuantos minutos '))

s=float(input('Cuantos segundos '))

t=s+(m*60)+(h*3600)+(d*86400)

print('El tiempo en segundos es',t)



##Condicional if

La forma mas facil de una sentencia condicional en el "if" en el ingles si seguido de la condicon a evaluar, dos puntos(:) y en la siguiente linea indicando el numero en ejecutar es caso que se cumpla dicha condición 

entero=int(input('Introdusca un numero entero: '))

par=entero%2

if par == 0:

    print('El numero par es')

else:

    print('El numero no par es')

ejemplos:

1.- entero=int(input('Introdusca un numero entero: '))

par=entero%2

if par == 0:

    print('El numero par es')

else:

    print('El numero no par es')

2.- casilla=str(input('escoje una casilla? :'))

if casilla == ('a1'):
      print('casilla negra')

elif casilla == ('a3'):
      print('casilla negra')

elif casilla == ('a5'):
      print('casilla negra')

elif casilla == ('a7'):
      print('casilla negra')

elif casilla == ('b2'):
      print('casilla negra')

elif casilla == ('b4'):
      print('casilla negra')

elif casilla == ('b6'):
      print('casilla negra')

elif casilla == ('b8'):
      print('casilla negra')

elif casilla == ('c1'):
      print('casilla negra')

elif casilla == ('c3'):
      print('casilla negra')

elif casilla == ('c5'):
      print('casilla negra')

elif casilla == ('c7'):
      print('casilla negra')

elif casilla == ('d2'):
      print('casilla negra')

elif casilla == ('d4'):
      print('casilla negra')

elif casilla == ('d6'):
      print('casilla negra')

elif casilla == ('d8'):
      print('casilla negra')

elif casilla == ('e1'):
      print('casilla negra')

elif casilla == ('e3'):
      print('casilla negra')

elif casilla == ('e5'):
      print('casilla negra')

elif casilla == ('e7'):
      print('casilla negra')

elif casilla == ('f2'):
      print('casilla negra')

elif casilla == ('f4'):
      print('casilla negra')

elif casilla == ('f6'):
      print('casilla negra')

elif casilla == ('f8'):
      print('casilla negra')

elif casilla == ('g1'):
      print('casilla negra')

elif casilla == ('g3'):
      print('casilla negra')

elif casilla == ('g5'):
      print('casilla negra')

elif casilla == ('g7'):
      print('casilla negra')

elif casilla == ('h2'):
      print('casilla negra')

elif casilla == ('h4'):
      print('casilla negra')

elif casilla == ('h6'):
      print('casilla negra')

elif casilla == ('h8'):
      print('casilla negra')


else:
      print('casilla blanca')






#Bucles

mientras las condiciones permitan ejecuytar distintos fragmentos de codigo dependiendo de ciertas condiciones, los bubles permiten ejecutar un mismo fragmento un cierto numero de vecs muestras se cumpla una determinada condición 

#While

El bucle while (mientras) ejecuta un fragmento de codigo mientras se cumpla la condición. El bucle while tiene la siguiente estructura 

edad=0

while edad<19:

    print("tienes"+,edad)

print("fin del programa")
 
#Break 
rompe el ciclo del bucle 

llave='0123'

pasword=''

while True :

    pasword=input('inserte su pasword:')

    if pasword== llave:

        print('felicidades, entraste al sistema')
        break

    else:

        print('pasword incorrecto')

        print('intente de nuevo')    


print('fin de programa')

ejemplos:

1.-edad=0
while edad < 19 :

    print('Tienes ', edad )

    edad=edad+1

print('fin de programa') 

2.-llave='0123'

pasword=''

while pasword !=llave:

    print('pasword incorrecto')

    pasword=input('inserte su pasword:')
    

print('felicidades, entraste al sistema')




##Ciclos for...in

En Python for se utiliza como una forma generica sobre una secuencia, es decir recorrer una secuencia 

secuencia=["uno","dos","tres"]
 
for elemento in secuencia:

   print(elemento)

ejemplo:

Escriba un programa que despliegue una tabla de comverción de temperatiras para grados celcius y grados faraigain.La tabla debe de contenerse filas para todas las temperaturas desde 0 a 100 grados celcius en multiplos de 10 grados celcius.

for celcius in range(0,101,10):

    farenheit = (1.8*celcius)+32

    print(celcius,'gC','|',farenheit,'gF')

2.-for precio in range(4,201,5):

    precio=(precio+0.95)

    descuento = (precio*0.60)

    preciof=(precio-descuento)

    print(precio,'$','|',"{:.2f}".format(descuento),'|',"{:.2f}".format(preciof,'$'))

3.-def areaTriangulo(base,altura):

    return (base*altura)/2.

area=areaTriangulo(2.4,4.3)

area1=areaTriangulo(5.4,3.2)

area2=areaTriangulo(5.4,4.2)

print(area,'\n',area1,'\n',area2)

4.-def tarifa(k):

    tarifa = 7.25+(7*k)

    if tarifa < 40:

        tarifa=40

    return tarifa
    
k=float(input('Cuantos kilometros vas a recorrer'))

b=tarifa(k)

print (b)

5.- def producto(envio):

    producto = 150+45*(envio-1)

    if envio==1:

        return 150

    elif envio==0:

        return 0

    return producto

envio=float(input('Cuantos articulos vas a pedir? '))

b=producto(envio)

print (b)



##Funciones 

Una función es un fragmento de código con un nombre asociado que realiza una serie de tareas y devuelve un valor. Además de ayudarnos en programas y depurar dividiendo el programa en partes los programas también permiten reutilizar código

Las funciones ayudan al programador a dividir el programa en diversas piezas que pueden ser rehusadas. También ayudan al programador a concentrarse 
en una pequeña parte del programa a la ves. Como resultado al escribir funciones es una parte importante del desarrollo del software. En nuestro caso debemos aprender a:


Definir una función para usarlo después 

Pasos uno o más valores a una función 

Desarrollar un numero complejo en una función 

Llamar a una función que previamente hayamos definido    


#Programación orientada a objetos 

Programación orientada a objetos el cual es un paradigma de programación en el que los conceptos del mundo real relevantes para nuestros problemas se modelan a través de clases y objetos, y en el que nuestro programa consiste en una serie de interacción de los objetos 

##Clases y objetos:
Un objeto es una entidad que agrupa un estado y una funcionalidad relacionada. 
El estado del objeto se define a través de variables llamadas atributos, mientras que la funcionalidad se modela a través de funciones a las que se les conoce con el nombre de métodos del objeto 

Un ejemplo ejemplo podría ser un coche en el que tendríamos atributos como la marca, el numero de puertas o el color y métodos como arrancar y parar, o bien cualquier otra combinación de atributos y métodos, según lo que fuera relevante para nuestro programa. 

###Clase:

Una clase no es más que una plantilla genética de la cual insistía en los objetos los objetos; En la pantalla que define que atributos y métodos tendrían los objetos de esa clase 

En Python la clase se define mediante las palabras class clave class seguido del nombre de ka clase, ejemplo  class automóvil seguido de los dos putnos y a continuación dentado el cuerpo de la clase 

class Automovil:

    def __init__(self,color)

        self.color=color

def arranca(self): 

ejemplos:

1.- import turtle
a=int(input('Introdizca el numero de circulos que desea:'))

ventana = turtle.Screen ()

ventana.bgcolor("black")

ventana.title("Hola Kary bebe")

kary = turtle.Turtle()

kary.shape("turtle")

kary.color ("green")

kary.pensize (2)

kary.speed(8)

for i in range(a):
  
  kary.penup()

  kary.setpos(0,-(i*10))

  kary.pendown()

  kary.circle(i*10)
  
ventana.mainloop()

2.- class Coche(object):

    def __init__(self,gasolina):

        self.gasolina = gasolina

    def arrancar(self):

        if self.gasolina > 0:

            print('Arranca')

        else:

            print('No Arranca')

    def conducir(self):

        if self.gasolina > 0:

            self.gasolina = self.gasolina - 1

            print('Quedan ', self.gasolina,' 

litros')

        else:

            print('No se mueve')

vocho = Coche(5)

tsuru = Coche(3)

vocho.arrancar()

vocho.conducir()

vocho.conducir()

vocho.conducir()

vocho.conducir()

vocho.conducir()

vocho.conducir()

3.- class Triangulo(object):

    def __init__(self,angulo1,angulo2,angulo3):

        self.angulo1 = angulo1

        self.angulo2 = angulo2

        self.angulo3 = angulo3

    def ChecarAngulo(self):

        if self.angulo1+self.angulo2+self.angulo3 == 180:
            print('Es un triangulo')

        else:

            print('No es un triangulo')

miTriangulo=Triangulo(90,30,60)

miTriangulo.ChecarAngulo()

##turtle 
facil de aprender para los alumnos para que puedan ver como utilizar las bibliotecas y usar los graficos 

ejemplos:

1.- import turtle

ventana=turtle.Screen()

ventana.bgcolor('green')

ventana.title('Funciones')

omar = turtle.Turtle()

d = 50

omar.forward(d)

omar.left(90)

omar.forward(d)

omar.left(90)

omar.forward(d)

omar.left(90)

omar.forward(d)

omar.left(90)

ventana.mainloop()

2.- import turtle

ventana=turtle.Screen()

ventana.bgcolor('green')

ventana.title('Funciones')

omar = turtle.Turtle()

d = 50

for i in range(4):

    omar.forward(d)

    omar.left(90)

ventana.mainloop()

3.- import turtle

def dibujar_cuadro(tur, d):

    for i in range(4):

        tur.forward(d)

        tur.left(90)

ventana=turtle.Screen()

ventana.bgcolor('green')

ventana.title('Funciones')

omar = turtle.Turtle()

kary = turtle.Turtle()

dibujar_cuadro(omar, 50)

dibujar_cuadro(kary, 200)

ventana.mainloop()

4.- import turtle

def dibujar_cuadro(tur, d):

    for i in ['red','purple','blue','yellow']:

        tur.color(i)

        tur.forward(d)

        tur.left(90)

ventana=turtle.Screen()

ventana.bgcolor('green')

ventana.title('Funciones')

omar = turtle.Turtle()

kary = turtle.Turtle()

dibujar_cuadro(omar, 50)

dibujar_cuadro(kary, 200)

ventana.mainloop()

5.- import turtle

def dibujar_multiples_cuadro(tur, d):

    for i in ['red','purple','blue','yellow']:

        tur.color(i)

        tur.forward(d)

        tur.left(90)

ventana=turtle.Screen()

ventana.bgcolor('black')

ventana.title('Funciones')

omar = turtle.Turtle()

omar.pensize(3)

d=20

for i in range(50):

    dibujar_multiples_cuadro(omar, d)

    d = d+10

    omar.forward(10)

    omar.right(18)

ventana.mainloop()

6.- import turtle


def dibujar_cuadro_seguir(tur, p):

    for i in range(4):

        tur.forward(20)

        tur.left(90)
    

ventana=turtle.Screen()

ventana.bgcolor('blue')

ventana.title('funciones')

omar=turtle.Turtle()

omar.pensize(5)

omar.speed(2)

p=30

for i in range(5):

    dibujar_cuadro_seguir(omar, 5)

    omar.penup()

    omar.setpos(p,0)

    omar.pendown()

    p=p+30

7.- import turtle

def dibujar (tur,d):

    for i in range(4):

        tur.color('blue')

        tur.forward(d)

        tur.left(90)
     
     
ventana=turtle.Screen()

ventana.bgcolor('black')

ventana.title('funciones')

alex=turtle.Turtle()
alex.pensize(3)

alex.speed(20)

m=-10

for i in range(20,1591,20):

    dibujar(alex,i)

    alex.penup()

    alex.goto(m,m)

    alex.pendown()

    m=m-10

ventana.mainloop()

8.- import turtle

def dibujar_cuadro(tur, d):
    
    for i in range(8):

        tur.forward(d)

        tur.left(45)
        
ventana=turtle.Screen()

ventana.bgcolor('white')

ventana.title('funciones')

a=turtle.Turtle()

dibujar_cuadro(a, 50)

ventana.mainloop()

9.- import turtle

def dibujar_cuadro_caracol(tur, d):

    for i in  ['red','blue','green','yellow']:

        tur.color(i)

        tur.forward(d)

        tur.left(90)

ventana=turtle.Screen()

ventana.bgcolor('black')

ventana.title('funciones')

alex=turtle.Turtle()

alex.pensize(2)

alex.speed(100)

d=100

for i in range(20):

    dibujar_cuadro_caracol(alex, d)
    
    alex.forward(10)

    alex.right(18)

    alex.setpos(0, 0)

ventana.mainloop()

10.- import turtle

def cuadrado(tur, d):

    f=90

    for i in  range(500):

        tur.color('blue') 

        tur.forward(d)

        tur.left(f)

        d=d+5

        f=f+0.02
        
ventana=turtle.Screen()

ventana.bgcolor('black')

ventana.title('funciones')

d=15

alex=turtle.Turtle()

alex.speed(25)

cuadrado(alex, d)

ventana.mainloop()

