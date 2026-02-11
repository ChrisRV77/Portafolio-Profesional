# Tech Support Analysis

El presente reporte ha sido elaborado utilizando una base de datos generada mediante código en Python y con apoyo de herramientas de inteligencia artificial, con fines exclusivamente prácticos. Por lo tanto, la información presentada no corresponde a datos reales de ninguna empresa. Asimismo, el diseño del informe está basado en un reporte de ZoomCharts que lleva el mismo nombre.

A continuación presento la explicación estructurada del dashboard:



### Encabezado: **Tech Support Analysis**

Panel principal de análisis del proceso de soporte técnico. Resume indicadores clave del ciclo de vida de los tickets (creación, respuesta, resolución, encuesta y cierre), permitiendo evaluar desempeño operativo, tiempos de atención y comportamiento por segmentos.

Cada encabezado superior funciona como botón interactivo que ajusta los parámetros del reporte para profundizar en esa etapa específica del proceso de soporte.

### Visual: **Created Ticket**

Muestra el total de tickets creados (1 mil) junto con una tendencia visual (sparkline). Permite evaluar el volumen de demanda que ingresa al área de soporte.
Al activarse como botón, orienta el análisis hacia la etapa inicial del proceso: origen de tickets, días con mayor carga y patrones de entrada.

Esta es la disposición por defecto que tiene el reporte.

### Visual: **First Response**

Indicador tipo gauge que muestra el porcentaje de cumplimiento en el tiempo de primera respuesta (68%).
Permite medir la rapidez inicial del equipo ante nuevas solicitudes.
Al activarse, el dashboard puede enfocarse en tiempos de atención, desempeño por agente o por tipo de ticket.

### Visual: **Resolution**

Indicador tipo gauge que muestra el porcentaje de tickets resueltos dentro del estándar esperado (68%).
Evalúa eficiencia operativa y cumplimiento de SLA en la etapa de solución.
Como botón, permite profundizar en su distribución mediante los diferentes atributos con los que cuenta.

### Visual: **Survey**

Muestra el promedio de satisfacción (3,03 AV Reviews) con una tendencia visual.
Representa la percepción del usuario final tras la atención recibida.
Al seleccionarlo, el análisis puede profundizar en su distribución mediante los diferentes atributos con los que cuenta.

### Visual: **Closed Tickets**

Indica el número total de tickets cerrados (600) y su tendencia.
Permite analizar la capacidad de finalización frente al volumen creado.
Como botón, orienta el análisis en profundizar en su distribución mediante los diferentes atributos con los que cuenta.

### Visual: **Status Open**

Muestra el porcentaje y cantidad de tickets actualmente abiertos (5,00% | 50).
Sirve para monitorear carga pendiente y posibles acumulaciones.

### Filtros: **Day Type | Source | Priority**

Segmentadores que permiten modificar el análisis en subsecciones, según:

* Tipo de día (laboral o fin de semana)
* Fuente del ticket
* Nivel de prioridad

Estos filtros afectan todos los visuales, facilitando análisis comparativos.

### Filtro: **Agent Group & Agent Name**

Permite segmentar por grupo o agente específico.
Se utiliza para evaluar desempeño individual o por equipo dentro del proceso de soporte.

## Sección de Análisis Operativo

### Visual: **Total tickets**

Gráfico tipo dona que muestra la distribución entre días laborales (72,8%) y fines de semana (27,2%).
Permite entender cuándo se concentra la demanda del servicio.

### Visual: **Total tickets por Topic**

Gráfico de barras horizontales segmentadas por tipo de día.
Muestra los tickets según categoría (Solicitud de Servicio, Reporte de Bug, Servicio al Cliente, Manual de uso, Licencias y precio).
Permite identificar qué tipo de requerimientos predominan y si cambian según el día.

### Visual: **Total tickets por Product group**

Barras horizontales segmentadas por grupo de producto (Software, Consulting Services, Development, Other).
Facilita analizar qué líneas de negocio generan mayor carga operativa y en qué tipo de día.

### Visual: **Total tickets por Month Name**

Gráfico de columnas segmentadas por mes.
Permite identificar estacionalidad en la generación de tickets y variaciones entre días laborales y fines de semana.

### Visual: **Total tickets por Horas**

Gráfico de columnas segmentadas por franja horaria.
Muestra los horarios de mayor demanda y permite optimizar asignación de turnos y recursos.

### Visual: **Mapa geográfico**

Representa la distribución geográfica de los tickets mediante marcadores circulares.
Permite identificar concentración regional de solicitudes y posibles necesidades de soporte localizado.

## Funcionalidad de los Encabezados como Botones

Cada encabezado superior (Created Ticket, First Response, Resolution, Survey, Closed Tickets) funciona como disparador de análisis contextual:

* **Created Ticket** → Enfoque en volumen y entrada de demanda.
* **First Response** → Enfoque en tiempos iniciales y SLA de respuesta.
* **Resolution** → Enfoque en eficiencia y tiempos de solución.
* **Survey** → Enfoque en satisfacción del cliente.
* **Closed Tickets** → Enfoque en productividad y cierre efectivo.

Esto permite recorrer de manera estructurada todo el ciclo del proceso de soporte técnico, desde la creación hasta la evaluación final del servicio, facilitando análisis tanto operativo como estratégico.


**Mensaje de aclaración**

Debido a que la base de datos utilizada en este reporte no está vinculada a un contexto real ni cuenta con antecedentes operativos o históricos que permitan su correcta interpretación, no es posible desarrollar un análisis de insights que represente conclusiones estratégicas o respuestas positivas frente a los resultados actualmente mostrados.

La información presentada tiene fines demostrativos y técnicos, por lo que cualquier hallazgo debe entenderse únicamente como una simulación analítica y no como un diagnóstico real de desempeño.

Puedes ver el reporte en el siguiente link: 

[![Static Badge](https://img.shields.io/badge/Indicadores_Recursos_Humanos-yellow?style=for-the-badge&label=Revisalo_Aquí&labelColor=white&color=yellow)](https://app.powerbi.com/view?r=eyJrIjoiNjIwNjVmNGUtNGE2ZC00MzNmLTk4NDAtMDc2YWU1ZGIxY2QzIiwidCI6ImI3YWY4Y2FmLTgzZDgtNDY0NC04NWFlLTMxN2M1NDUyMjNjMSIsImMiOjR9)
