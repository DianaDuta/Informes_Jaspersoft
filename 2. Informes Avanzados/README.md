\# 2. Informes Avanzados



Informes complejos que implementan subinformes, lógica condicional y análisis de datos.



\## Contenido



\### Sistema Master-Detail (Subinformes)

\* \*\*`a\_resumen\_gastos.jrxml` (Maestro)\*\*: Recibe parámetros y gestiona la estructura principal.

\* \*\*`a\_resumen\_subinforme.jrxml` (Detalle)\*\*: Se incrusta en el maestro para listar el detalle de pedidos y calcular estadísticas internas (precio máximo, mínimo y media).



\### Análisis Global

\* \*\*`b\_resumen\_clientes.jrxml`\*\*: Reporte masivo agrupado por cliente. Implementa lógica avanzada en Java para comparar variables y determinar dinámicamente qué cliente ha gastado más o menos en el total global.



---

\*Stack:\* Jaspersoft Studio 7.0.1

