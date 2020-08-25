![Inove banner](/inove.jpg)
Inove Escuela de Código\
info@inove.com.ar\
Web: [Inove](http://inove.com.ar)

# Seguimiento de flota [Python_2]
Programa que analiza los movimientos de una flota de vehículos, ya sea vehículos de transporte, de pasajeros, de encomienda o de delivery.\
El objetivo es analizar la información de los viajes realizados.

Este proyecto está basado en el proyecto de Python Inicial:\
[https://github.com/InoveAlumnos/flota_python_1](https://github.com/InoveAlumnos/flota_python_1)

# Entrada del sistema
El programa recibe por HTTP la información de cada viaje realizado por nuestra flota, el JSON que reciba debe tener al menos la siguiente información:
- Año-Mes-día del viaje efectuado
- Identificador del vehículo
- ¿Cuánto tiempo el vehículo tardó en llegar a destino (tiempo circulando)? [Valor en minutos].
- ¿Cuánto recaudó por ese viaje?
- [Opcional] Agregar posición (latitud y longitud) del inicio y final del recorrido para futuras funcionalidades.

La información que ingresada a la API debe almacenarse en una base de datos para su posterior analisis.

# Salida del sistema
Se deberá poder extraer de la base de datos un resumen con los siguientes resultados (y cualquier otro que desee agregar el alumno):
- ¿Cuántos viajes realizó un determinado vehículo ingresado por consola? 
- ¿Cuánto tiempo estuvo circulando el vehículo?
- ¿Cuánta recaudación logró el vehículo?

Se deberá especificar el día, mes o año en donde se desea realizar el análisis para el vehículo ingresado. Toda la información necesaria para crear el reporte se debe enviar por HTTP.


# Notas
Este proyecto puede utilizarse como base o referencia para hacer uno parecido o distinto del mismo tema. Se solicita que el contenído mínimo del proyecto alcance los especificado en las "entradas y salida del sistema" pudiendo el alumno modificar o agregar requerimientos. El objetivo en este proyecto es que construyan una base de datos, trabajen los datos y por último retornar una respuesta HTTP con un reporte.\
En cada caso puntual se discutirá con el alumno como puede ser modificado el proyecto según sus deseos o necesidades.

Estos temas se discuten en el campus del curso en el foro correspondiente al proyecto. Cada alumno deberá iniciar un tema de discucisión sobre el proyecto que desea realizar y como este lo desea implementar.

# Consultas
alumnos@inove.com.ar
