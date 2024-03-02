2.Toma de datos exprimentales; angulo y tiempo.

Se hace uso de la herramienta Tracker, con la cual se captura el movimiento de la masa (péndulo) y análisis del movimiento. Con los datos obtenidos se procede a realizar el análisis mediante el código solicitado. 
El valor de ángulo y demás datos necesarios se explica a continuación con el inicio de implementación mediante el código de análsisis.


3.Ajuste los parametros del pendulo lineal.

Al ser un modelo de pendulo simple, nos basaremos en la formula general T = 2*pi raíz(L/g)
Por lo que nuestra masa que consideraremos puntual a lo largo de todo el ejercicio, la cuerda de la que está suspendida tendra una masa despreciable y la longitud mencionada anteriormente de 15 cm.
Con esto comenzamos con la implementación del principio de conservación de la energía, buscando hallar el a´ngulo Theta, con rescto del desplazamiento con respecto a la vertical de nuestro modelo. 


4.Generar las simulaciones con una solucion aproximada a pendulo simple y otra solucion mediante un método numerico.


5.Comparacion de modelos.


Modelo de solucion aproximada del péndulo simple, desde el inicio de recepción de datos, velocidad y angulo constante en sus oscilaciones.

En el metodo de Runge-Kutta, se evidencia la disminución de las oscilaciones y la velocidad angular, sin embargo muestra una repetibilidad constante en los ciclos
de onda.


6.Conclusiones

Mediante la implementación del ejercicio de análisis del desplazamiento lineal o pendular, esta actividad hace que 
se afiancen los conocimientos de las herramientas de programación propuestas en clase.

La comparación de los diferentes modelos, con los mismos datos, demuestran que sí se tienen diferencias en los resultados,los cuales pueden ser concluyentes a la hora de su interpretación.
Esto debido a que el análisis de solución aproximada, es un modelo idealizado, mientras que el Runge - Kutta, busca una mejor aproximación de los resultados; al ser una técnica de resolución
de ecuaciones diferenciales.
