\# Portfolio de Diseño de Informes | Jaspersoft Studio



Esta es una colección estructurada de prácticas y ejercicios de diseño de informes empresariales utilizando \*\*TIBCO Jaspersoft Studio\*\*. 



El objetivo de este proyecto es demostrar la progresión desde consultas SQL básicas hasta la maquetación de informes complejos con lógica de negocio avanzada.



\## Estructura del Proyecto



El repositorio está organizado en dos niveles de dificultad:



\### \[1. Informes Sencillos](./1.%20InformesSencillos)

Fundamentos del diseño de reportes y consultas a base de datos.

\- \*\*Consultas SQL:\*\* Uso de `JOIN`, `ORDER BY` y filtrado.

\- \*\*Parámetros:\*\* Informes dinámicos que solicitan datos al usuario (ej. filtrar por Cliente).

\- \*\*Variables y Cálculos:\*\* Operaciones aritméticas en línea (Precio × Cantidad) y acumuladores.

\- \*\*Agrupación Básica:\*\* Uso de `Group Header` y `Group Footer` para organizar listados.



\### \[2. Informes Avanzados](./2.%20Informes%20Avanzados)

Implementación de lógica compleja y estructuras anidadas.

\- \*\*Master-Detail (Subinformes):\*\* Arquitectura de informe padre-hijo pasando parámetros para mostrar detalles transaccionales.

\- \*\*Estadísticas de Grupo:\*\* Cálculo de máximos, mínimos y promedios (`MAX`, `MIN`, `AVG`) dentro de grupos específicos.

\- \*\*Lógica Condicional:\*\* Uso de expresiones Java (operadores ternarios) para resaltar datos críticos (ej. "Cliente que más ha gastado").



\## Stack Tecnológico



\* \*\*IDE:\*\* Jaspersoft Studio 7.0.1

\* \*\*Lenguaje de Expresiones:\*\* Java

\* \*\*Base de Datos:\*\* MariaDB / HSQLDB (Sample DB)

\* \*\*Control de Versiones:\*\* Git \& GitHub



\## Cómo usar este repositorio



1\. Clonar el repositorio:

&nbsp;  ```bash

&nbsp;  git clone \[https://github.com/DianaDuta/Informes\_Jaspersoft.git]  (https://github.com/DianaDuta/Informes\_Jaspersoft.git)

