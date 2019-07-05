# programacion-basica
 
PYTHON  
Lenguaje de programación creado por Guido Van Rossum a principios de los años 90. Es un lenguaje similar a C pero con una sintaxis muy limpia y que favorece un código legible.

SCRIPT  
Es aquel que se utiliza un programa intermediario que se interpreta en un lugar de copiar el código a lenguaje maquina.

TERMINAL Y CÓDIGOS   
Para entrar a la terminal, escriba el comando "python" , para salir usamos "exit ()" . Existen dos formas de ejecutar un código: mediante una sesión interactiva (línea a línea) con la interpretación o la forma habitual, escribir el código en un archivo de código fuente y ejecutando. Ejemplos de códigos:

             print ("Hola mundo")
comando ---- print 
argumento (cadena de texto) ------- ("Hola mundo")

    mi-cadena= "Tengo hambre y faltan 60 min para salir"
        print(mi-cadena)
        
variable ---- mi-cadena 
valor --------- "Tengo hambre y faltan 60 min para salir"

Para hacer comentarios se usa # .Para salto de linea \ n. ejercicio: crear un programa que despliegue su nombre y su dirección.

TIPOS DE VARIABLES   

cadena de texto --- stringo (Jenifer)

numero ------------ interger (23)

concatenar = unir varias variables del tipo "cadena" en una sola. mi archivo .py ------ dir = lista de archivos 
cd = en el escritorio



ejercicio: escribe un programa que le pregunte al usuario por su nombre. El programa debe responder con un mensaje de: Hola + el nombre. comando = entrada



Escribe un programa que le pregunte al usuario el largo y el ancho de su cuarto. Una vez que los valores han sido leídos el programa debe calcular y desplegar el área de la habitación. El largo y el ancho deben ser convertidos a números flotantes. Incluya las unidades en su mensaje de salida.



FLOTANTE VARIABLE: variable que puede guardar datos numéricos con punto decimal. Se utiliza float () e int (): para un número a ser entero.



ejercicio: en algunos lugares un depósito pequeño es un agregado a los contenedores de basura para hacer que las personas recíprocamente botellas de mascota. Actualmente el municipio paga $ 1.00 si se deposita una botella de mascota básica de 1L o menos y $ 2.50 se deposita una botella de mascota básica de mas de 1L. Escriba un programa que le pregunte al usuario por el número de botellas de 1L o menos y por el número de botellas de + 1L y que despliegue al final lo que se va a pagar al usuario por haber reciclado las botellas. e5



Los tipos de datos básicos se dividen en: números, como: entero o interger (3), punto flotante o float (1.75), complejos o complex (7 + 5j) * cadenas de texto o string "Hola mundo" Para poder conocer el tipo de dato de una variable usaríamos la instrucción type ()

int ---- para almacenar una cantidad de números grande.

float ---- números con decimal abarca números negativos y positivos

suma -------------  (+) ejemplo 3 + 2  
resta ------------  (-) ejemplo 4-7  
negación ---------- (-) ejemplo -7  
multiplicación ---- (*) ejemplo 2 (*) 3  
exponente -------- (**) ejemplo 2 (**) 6  
división ---------- (/) ejemplo 3.5 / 2  
división entera -- (//) ejemplo 3.5 // 2  
módulo ------------ (%) ejemplo 7% 2 

import --- para poder usar una biblioteca y módulos de python

ejercicio: escriba un programa que lea 2 números enteros y la guía en las variables ay b. El programa debe calcular y mostrar: suma de ayb, resta de bya, producto de ayb, consiente de cuando está dividido por b, residuo de cuando está dividido por b, resultado de "a" a la "b" y el resultado de log10













CONDICIONAL if    

    if comparación condición
        identacion(4 espacios) # código a ejecutar en 
                               caso de que la condición sea 
                              verdadera
                              
¿A = b?       | a == b   
¿a no es = b? | a! = b   
¿a> b?        | a> b   
¿a = b?       | a> = b   
¿a = b?       | a <= b   
¿a <b?        | a <b  
 
if else

    if comparación o condición
    identacion # código a ejecutar en caso de que 
                 la condición sea verdadera
    else
     identacion # código a ejecutar en caso de que 
                 la condición sea falsa 
                 
ejercicio



BUCLES   
permite ejecutar un mismo fragmento de código un cierto número de veces mientras se cumple una determinada condición. mientras que --- (mientras que) se cumpla la condición.

    while condición:
    identacion Fragmento-de-código-que-se-repite
    
ejercicio



CICLO if ... in    
"if" se utiliza para recorrer una secuencia. ejemplo

    secuencia = ["uno","dos,"tres"]
        for elemento in secuencia:
            print(print)
            
ejercicios



FUNCIONES     
Fragmento de código con un nombre asociado que realiza una serie de tareas y devuelve un valor, también permite reutilizar códigos.

ejercicio



GRÁFICOS   
Para el manejo de los gráficos se utiliza un módulo que permite crear figuras y patrones.

PROGRAMACIÓN ORIENTADA A OBJETOS   
Paradigma de la programación en el que los conceptos del mundo real para nuestros problemas se modelan a través de clases y objetos, y en nuestro programa conciste en una serie de interacción con los objetos.

CLASES Y OBJETOS    
Un objeto es una entidad que agrupa un estado y una relación relacionada. El estado del objeto se define a través de las variables llamadas de los atributos, mientras que la funcionalidad se modela a través de las funciones de los mismos. Una clase no es más que una plantilla genérica de la cualidad de los objetos; es la plantilla que define los atributos y métodos de los objetos de una clase. Se define con la palabra clase seguida del nombre de la clase, seguido de: ya continuación se identifica el cuerpo de la clase.

ejemplo

    class automovil:
        def __init__(self, atributo)
        self.atributo = atributo
    def arranca(self)
