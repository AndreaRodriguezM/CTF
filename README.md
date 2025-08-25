---HERRAMIENTAS PARA EL MANEJO DE ERRORES EN LENGUAJE PYTHON---

#Tema: Otras herramientas para el manejar errores Parte 2
#Andrea Rodríguez Macias
#Computación Tolerante a Fallas

#Ejemplo 1 (usando try-except personalizado)
En este ejemplo en Python se pide que se ingrese un número escrito solo con caracteres, por ejemplo: cuatro, dos, uno 
Si se ingresa el numero con números enteros o flotantes, el programa muestra el mensaje de que se ingresaron los datos incorrectamente
es decir, genera un ValueError personalizado.

#Ejemplo 2 (usando try-except personalizado-zerodivisionerror)
En este ejemplo se aplica algo muy similar al primer ejemplo, pero en este caso se pide que se ingrese un numero entero solo con números (enteros) y se realiza una división
Si se ingresa un valor invalido, se genera el ValueError asi como si se ingresa el valor 0 se activa el ZeroDivisionError
