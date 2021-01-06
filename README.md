# Trabajo-de-Investigacion-P1
Integrantes: Bryan Santiago Torres Reyes , Roger Steveen Armas Simbaña , Israel Alejandro Portero Cazares

NRC: 4867

Objetivos:

Objetivo  general

* Familiriarizasre y implementar los metodos y conversiones  presentados en en el capitulo 8  para la resolucion de ciertos tipos  de circuitos.


Objetivo especifico


* Presentacion de las caracteristicas de una fuente de voltaje cd y de  una fuente de corriente.

* Aplicar conversiones  de fuente en diferentes circuitor presentados.

* Aplicar  teoremas de Thevenin y Norton en el analisis de circuitos .

* Aplicar el teorema de transferencia de potencia maxima  en el analisis de circuitos.

* Determinar el teorema delta a Y , Y a delta en el analisis de un determinado circuito


Marco Teorico / Diagramas :

*  Fuente de voltaje cd 

La fuente de voltaje de  cd es uno de los principales tipos de fuente de energia. Este tipo de fuente idealmente proporciona un voltaje constante a la carga , incluso  cuando la resistencia de esta varia.

* Fuente de corriente

La fuente de corriente es otro tipo de fuente de energia que idealmente suministra una corriente constante a una carga ,  incluso cuando la resistencia de esta varia.  Esta fuente de corriente es importante  en ciertos tipos de circuitos transistores.

*  Conversiones de fuente 

 -Conversion de una fuente de voltaje en una fuente de corriente  
 
 El voltaje de fuente , Vs, dividido entre la resistencia interna de la fuente ,Rs , da el valor de la corriente de la  fuente equivalente
 
 
![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen%201.png)

       
El valor de Rs es el mismo tanto con la fuente de voltaje como con la  fuente de corriente .  La flecha direccional para la corriente  apunta de menos a mas . La fuente de corriente equivalente  esta en paralelo  con Rs.


![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen%202.png)


- Conversion de una fuente de corriente en una  fuente de voltaje

La corriente de la  fuente Is, multiplicada por la resistencia interna de la fuente Rs, da el valor del voltaje de la fuente equivalente.

![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen%203.png)

De nuevo, Rs no cambia. La polaridad de la fuente de voltaje es de menos a mas en la direccion de la corriente. La fuente de voltaje equivalente es el voltaje es el voltaje en serie con Rs.

![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen%204.png)


*  Teorema de superposicion

En un circuito con multiples fuentes , el teorema de superposicion es una forma de determinar corrientes  en dicho circuito , dejando una fuente a la vez y  reemplazando  las fuentes por resistencias internas.

Pasos para aplicar el teorema de  superposicion :

1. En el circuito dejar una fuente de voltaje o de corriente y reemplazar las demas  por sus resistencias internas es decir un corto circuito.

2.  Determinar el voltaje o corriente pedido como si solo hubiera una sola fuente 

3. Repetir el mismo proceso con las demas fuentes existentes 

4. Realizar las sumas algebraicas de  las corrientes producidas por cada fuente individual , realizado se hace los calculos normales con la ley de Ohm.

![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen%205.png)


* Teorema de Thevenin

El teorema de Thevenin es un metodo para simplificar un circuito en una forma equivalente estandar

El equivalente de Thevenin de cualquier circuito resistivo de dos terminales consta de dos partes de la fuente de voltaje equivalente (Vth) y una resistencia equivalente (Rth)

* Voltaje equivalente de Thevenin (Vth)

En un circuito , el Vth es el voltaje del circuito abierto(sin carga) , que esta entre dos terminales de salida.



![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/imagen%207.png)






* Resistencia equivalente de Thevenin (Rth)

Es la resistencia total que aparece entre dos terminales en un circuito que tiene todas las fuentes reemplazadas por su resistencia interna



![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen%208.png)







* Pasos para aplicar el teorema de Thevenin

1.  Eliminar las cargas  del circuito ( Abrir dos terminales).

2.  Calcular el voltaje de Thevenin en las terminales abiertas

3.  Calcular la resistencia de Thevenin entre las dos terminales abiertas con las fuentes reemplazadaz, de corriente (abierta) y voltaje (cortocircuito) respectivamente.

4. Conectar Vth y Rth en serie para producir la equivalente de Thevenin

5. Reemplazar la carga en las terminales reemplazadas del paso 1 , de ahi utilizar ley de Ohm para los calculos del circuito original.



Ejemplo :


![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/imagen%206.png)






* Teorema de Norton

Es un metodo empleado para simplificar un circuito lineal de dos terminales en un circuitoequivalente con una fuente de corriente en paralelo con un resistor.Se denomina la fuente de corriente como In y la resistencia Rn.


![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen%209.png)






* Corriente equivalente de Norton (In)

Es la corriente que se encuentra en cortocircuito entre dos terminales de salida de un circuito




![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen%2010.png)






* Resistencia equivalente de Norton (Rn)

La resistencia equivalente de Norton sse emplea de igual manera que la resistencia de Thevenin. Es la resistencia total que aparece entre dos terminales de salida que tiene las fuentes reemplazadas por sus resistencias internas.


* Pasos para aplicar el teorema de Norton

1.  Poner en cortocircuito las dos terminales que se desea determinar el equivalente de Norton.

2.  Determinar la corriente de Norton en las terminales en cortocircuito.

3.  Determinar la resistencia de Norton con las terminales abiertas y con las fuentes reemplazadas, en corriente (abierta) y voltaje (cortocircuito) al igual que se hace en la resistencia de Thevenin.

4.  Calcular In y Rn con el circuito en paralelo para que se produzca el equivalente de Norton.


*  Teorema de transferencia de potencia maxima

Para una fuente de voltaje dada , la potencia maxima se transfiere desde una fuente hasta una carga cuando la resistencia de la carga es igual a la resistencia interna de la fuente.

Se transfiere potencia maxima cunado Rs=Rl



![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen%2011.png)






* Conversiones Delta a Y , Y a Delta

Las conversiones entre este tipo de circuitos tipo delta y Y son muy utiles en aplicaciones especializadas de tres terminales,un ejemplo claro es de un circuito con puente Wheatstone con carga.


![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/imagen%2012.png)





*  Conversion de Delta a Y

Se requiere que R1 , R2, R3 debe estar en funcion de RA ,RB ,RC



![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen%2013.png)






Se emplea las siguientes formulas:


![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen%2014.png)





![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen%2015.png)






![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen16.png)





* Conversion de Y a Delta

Para realizar esta conversion RA ,RB , RC debe de estar en funcion de R1 , R2 ,R3

Se emplea las sigueientes formulas:



![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen%2017.png)




![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen%2018.png)





![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Imagen%2019.png)


Diagramas :

![](https://github.com/iaportero/Trabajo-de-Investigacion-P1/blob/main/Imagen/Superposicion_y_Transformacion_de_Fuentes.png)




Desarrollo:

https://github.com/iaportero/Trabajo-de-Investigacion-P1/tree/main/Hojas%20tecnicas

Conclusiones:

*  Con el teorema de superposicion , en un circuito de diversas fuentes este proporciona un metodo de analisis apropiado.

*  el circuito equivalente de Thevenin siempre aparece en la forma de una fuente  de
voltaje equivalente en serie con una resistencia equivalente haciendo caso omiso del circuito original
que reemplaza.

* Cualquier resistor de carga conectado entre las terminales de salida de un circuito equivalente
Norton tendrá la misma corriente a través de él y el mismo voltaje entre sus terminales como si
estuviera conectado a las terminales de salida del circuito original.

*  La transferencia de potencia maxima se da cuando la resistencia de la carga es igual a la resistencia interna  de la fuente.


Bibliografia

Principios de Circuitos Electricos, Floyd .L.Thomas,Mexico 2007,Recuperado:3-01-2021 ,Capitulo  8 , Pag :281-310




 
 
 
 
 
 
 
 
