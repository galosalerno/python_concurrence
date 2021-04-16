# Concurrencia en Python

## Video Clase 2 - Codigo Fuente
```
procesosEjemplo.py
procesosEjemplo2.py
threadsEjemplo.py
globalVarsEjemplo.py
globalContador.py
```

## Ejercicio:

```
textoAnimado.py
```
El siguente programa, utiliza el [Interfaces gráficas de usuario Tk (tkinter)](https://docs.python.org/es/3/library/tk.html) para generar animaciones de texto.
Las animaciones consisten en un caracter que se repite a lo largo de una línea, a una determinada velocidad.

Leer y analizar el código y tratar de deducir que hace cada bloque.

## Preguntas (responder en el campus):

1. Como podría modidificar el caracter a imprimir en las lineas animadas?
2. Como podría modificar la velocidad a la que se escriben los caracteres?
3. Las animaciones de esta versión se ejecutan en forma Secuencial: explique por que.
4. Modificar el código de modo que las animaciones se ejecuten en forma concurrente utilizando Threads.
5. Como modificaría el código para utiliar Procesos en lugar de Threads. Que diferencias habría al ejecutarlo?
   Bonus: Implementar el punto 5 en codigo que funcione.

# 1 Cambiando el parametro que recibe la funcion crearAnimacion(10,10, 'X') - el valor del tercer parametro define el caracter a mostrar por pantalla.
# 2 El valor de la variable retardo es el encargador de decirle cuanto tiempo "dormir" al proceso. El mismo es utilizado en la funcion time.sleep
# 3 Se ejecutan de forma secuencial ya que hay una unica funcion y es llamada una atras de otra, pero hasta que no termina la anterior no puede ejecutarse la que sigue.
# 4 ECHO EN CODIGO
# 5 
<sub>[Daniel Buaon - unahur-progra-concu-1-2021](https://github.com/unahur-progra-concu-1-2021)</sub>
