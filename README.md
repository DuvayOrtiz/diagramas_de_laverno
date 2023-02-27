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

[![](https://mermaid.ink/img/pako:eNpNUc1Kw0AQfpVhTy22ogcvAS3SVlCoFNqLJBXGZNIObHbi7gapaR_Jk7de82JukoLd0-zM9zM_tUolIxWpXMtXukPrYT1LDIT3OHg2nLIMYTx-gFX82pwKsgJm0yZ6zEes2XmEjIBhh23Yl2FaM5CDgoxYEOBthRo-KwLzfnN9Nzn2_GmLPbjm5wCzmDQXbNCCqwKxOWnPpRbX661jvuer2-4zvSQbOcC83iPkQfwskQmUwTaQQ1sZaQRHacrNr4HgNTlCLzD_d3-LjYAl1PwdGiitpORkcwlrfV5icmGC8yLCeKXlQrqelvFCnLeBTAZKNB61xs3ZaNmNwIMnNsPEJEaNVFAokLOw-brFJMrvqKBERSHMKMdK-0Ql5higWHlZ7U2qIm8rGqmqzNDTjHFrsVBRjtqFLGXsxS76a3ZHPf4BnWSe3w?type=png)](https://mermaid.live/edit#pako:eNpNUc1Kw0AQfpVhTy22ogcvAS3SVlCoFNqLJBXGZNIObHbi7gapaR_Jk7de82JukoLd0-zM9zM_tUolIxWpXMtXukPrYT1LDIT3OHg2nLIMYTx-gFX82pwKsgJm0yZ6zEes2XmEjIBhh23Yl2FaM5CDgoxYEOBthRo-KwLzfnN9Nzn2_GmLPbjm5wCzmDQXbNCCqwKxOWnPpRbX661jvuer2-4zvSQbOcC83iPkQfwskQmUwTaQQ1sZaQRHacrNr4HgNTlCLzD_d3-LjYAl1PwdGiitpORkcwlrfV5icmGC8yLCeKXlQrqelvFCnLeBTAZKNB61xs3ZaNmNwIMnNsPEJEaNVFAokLOw-brFJMrvqKBERSHMKMdK-0Ql5higWHlZ7U2qIm8rGqmqzNDTjHFrsVBRjtqFLGXsxS76a3ZHPf4BnWSe3w)


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


###  Diagramas de flujo


[![](https://mermaid.ink/img/pako:eNpdkctOwzAQRX9l5FUrNULqMgsQUqEqi27KBiUgTZ1pa8mP1A8R-vgYPoAVO7b5MSZNEAjLC-v63Dvj8VFIV5HIxUa7V7lDH-FxVlrgdTtaWCWVG0OWXcOqWLZfhryDBvaJoKJAaFwA6WygbVIePKrDcwf3_nWxTkGiB9Jg08XKLMiElcfKAdnYaaZ95xDyEq0DhOaSAH2ELzReYnsYuSpwXbBDKxQAe34w3B1ZMvgbWDsPnKEO-6TIV3hz_iE72ym0Hyd4KnbIPDQZvkyvpn3i_C9m3QkeBooZyJp_2LwIyaDXNPTTq7HgAUXfjcBCjTai5l54Y-1dowxK1X7aPwY9ul8sx6UVE8HvM6gq_pljd1eKuCNDpcj5WNEGk46lKO2ZUUzRrd6sFHn0iSYi1RVGmincejQi36AOdP4GNYChTw?type=png)](https://mermaid.live/edit#pako:eNpdkctOwzAQRX9l5FUrNULqMgsQUqEqi27KBiUgTZ1pa8mP1A8R-vgYPoAVO7b5MSZNEAjLC-v63Dvj8VFIV5HIxUa7V7lDH-FxVlrgdTtaWCWVG0OWXcOqWLZfhryDBvaJoKJAaFwA6WygbVIePKrDcwf3_nWxTkGiB9Jg08XKLMiElcfKAdnYaaZ95xDyEq0DhOaSAH2ELzReYnsYuSpwXbBDKxQAe34w3B1ZMvgbWDsPnKEO-6TIV3hz_iE72ym0Hyd4KnbIPDQZvkyvpn3i_C9m3QkeBooZyJp_2LwIyaDXNPTTq7HgAUXfjcBCjTai5l54Y-1dowxK1X7aPwY9ul8sx6UVE8HvM6gq_pljd1eKuCNDpcj5WNEGk46lKO2ZUUzRrd6sFHn0iSYi1RVGmincejQi36AOdP4GNYChTw)






Con esto ya sería todo :D, el metodo usado al final es para dar una aproximación a la raiz de manera finita, hasta la proxima ;)


Ciao uwu





