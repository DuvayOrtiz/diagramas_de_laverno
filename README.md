#  reto_number_4
##  diagramas_de_laverno
En este repositorio se estará desarrollando el reto 4 de programación, ojalá todo increible. uwu

### Números Primos


```pseudocode

[variables]
n:entero
i:entero
inicio
i: =2
mientras i ≤ (n^0.5) 
eliminar multiplos de i
si i no se eliminó entonces 
mostrar en pantalla (lista de los primos hasta n) 
i:i+1
fin mientras
FIN
```
###  Diagrama de flujo 

![image](https://user-images.githubusercontent.com/124726079/221446945-c36b4e85-3a75-4bc8-8e38-b5b4462f12d8.png)


###  Raíces cuadradas

```pseudocode

[intervalos]
x:entero 
a:entero
s:entero
i:entero
c:entero

inicio

x es el valor al que deseamos calcular su raíz
c:=2
calcular c^2
c=c+1
 detener cuando que c^2 ≥ x 
 los dos ultimos terminos calculados de la operación anterior los llamaremos s al  mayor e i al menor

realizar |x-s| y |x-i| 

si alguna de las diferencias es 0, a es la raiz de ese número
 
sino se llamará a al cuadrado de s o i en el que el resultado sea menor


si la diferencia es menor con i usar [(x-a^2)/2a]+a
 
si la diferencia con i es menor usar [(a^2- x)/2a]+a

mostrar el resultado en pantalla

fin
```

###  Diagramas de flujo



![image](https://user-images.githubusercontent.com/124726079/221446790-549b8978-62ae-4ed9-8d72-bd6b8134fe0a.png)





Con esto ya sería todo :D, el metodo usado al final es para dar una aproximación a la raiz de manera finita, hasta la proxima ;)


Ciao uwu





