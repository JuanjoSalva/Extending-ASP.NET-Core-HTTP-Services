## Laboratorio Módulo 4

Fichero de Instrucciones: Instructions\20487D_MOD04_LAK.md

Entregar el url de GitHub con la solución y un readme con las siguiente información:

1. **Nombres y apellidos:** Juan José Salvador Román
2. **Fecha:** 31/12/2020
3. **Resumen del Ejercicio:** 



**Personalización de la canalización de ASP.NET Core**

En este laboratorio, personalizará la canalización de ASP.NET Core.

Objetivos

- Agregue inversión de control mediante la inyección de dependencia al proyecto.

- Cree un mecanismo de caché y filtros de acción.

- Agregue middleware para informar al cliente a través de la respuesta del encabezado.



**Ejercicio 1:** use la inyección de dependencia para obtener un objeto de repositorio 

 Implemente la inversión del patrón de diseño de control y use la inyección de dependencia. 



**Ejercicio 2:** crear un filtro de caché 

Implementar un filtro de acción que almacene en caché el resultado del servicio. 



Por consola podemos mostrar los resultados:



**Aquí mostramos las reservas en la web.**

![GetAllReservas](E:\JUANJO\CURSO2020\MODULO4_AZURE\20487D\AllFiles\Mod04\LabFiles\Lab1\Starter\img\GetAllReservas.PNG)



**Aquí las mostramos por consola**

![getreservation](E:\JUANJO\CURSO2020\MODULO4_AZURE\20487D\AllFiles\Mod04\LabFiles\Lab1\Starter\img\getreservation.PNG)



**Otra forma**

![getreservationContent](E:\JUANJO\CURSO2020\MODULO4_AZURE\20487D\AllFiles\Mod04\LabFiles\Lab1\Starter\img\getreservationContent.PNG)



**Invokar una** 

![invoke](E:\JUANJO\CURSO2020\MODULO4_AZURE\20487D\AllFiles\Mod04\LabFiles\Lab1\Starter\img\invoke.PNG)

**Borrar** 

![borrada](E:\JUANJO\CURSO2020\MODULO4_AZURE\20487D\AllFiles\Mod04\LabFiles\Lab1\Starter\img\borrada.PNG)





**Ejercicio 3:** crear un middleware de depuración 

Implemente el middleware ASP.NET Core que devuelva el tiempo de ejecución del servicio.

![3](E:\JUANJO\CURSO2020\MODULO4_AZURE\20487D\AllFiles\Mod04\LabFiles\Lab1\Starter\img\3.PNG)