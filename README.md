# MCOC-Proyecto-0

Introducción
==============

En este proyecto se mostrará el efecto de perdida de significancia, a partir de la iteración de una resta de dos números de punto flotante. Cada iteración hará que un número sea más cercano al otro. La idea de este proyecto es comparar el resultado exacto frente al resultado dado por el programa, podremos observar que la mayoría de estos resultados tendrán un error asociado a la perdida de significancia.

Proyecto
==============

Se quiere mostrar el error asociado entre la resta de dos puntos puntos flotantes.

Se iterará 18 veces la siguiente resta :

-> 0.1-0.1[i]1

El término [i] significa que por cada iteración se agregará un 0 en la posición en que se encuentra.


Resultados
==============

Se define el error relativo como :

ERROR = (Promedio_Calculado - Resultado_Exacto) / Resultado_Exacto

Abajo se muestra como va creciendo el error relativo en la medida en que se considera mayor. Esto ocurre debido a la perdida de significancia en la operacion resta de puntos flotantes usada.

Output de la consola:

i=0 -> error: 5.204170427930421e-16 %

i=1 -> error: -8.673617379884035e-16 %

i=2 -> error: 1.1018204577883939e-13 %

i=3 -> error: 3.8777168325301864e-13 %

i=4 -> error: -1.0001341524705151e-12 %

i=5 -> error: 1.1002216831004514e-10 %

i=6 -> error: 5.263558687189278e-10 %

i=7 -> error: 5.263559100779585e-10 %

i=8 -> error: 5.603750711548639e-08 %

i=9 -> error: 5.603750711548639e-08 %

i=10 -> error: -8.274037105959341e-08 %

i=11 -> error: 8.24393231366947e-06 %

i=12 -> error: 0.00010538844696842115 %

i=13 -> error: 0.0007992778373591124 %

i=14 -> error: 0.0007992778373591912 %

i=15 -> error: 0.028554853452988006 %

i=16 -> error: 1.0 % 

i=17 -> error: 1.0 % 



