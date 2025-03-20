README - Dashboard de Análisis de los Niveles de Atención de la Red Hospitalaria

[![Imagen-servicio.webp](https://i.postimg.cc/P5DTBN4r/Imagen-servicio.webp)](https://postimg.cc/5Xfhz4TZ)

Descripción General :memo:

Este dashboard proporciona un análisis detallado de indicadores clave de desempeño (KPIs) relacionados con la gestión del servicio, especialmente los niveles de atención y los tiempos de gestión. Permite visualizar y evaluar la eficiencia operativa a través de diferentes métricas y desviaciones respecto a los objetivos establecidos.
El objetivo principal es poder tener un análisis ágil de los principales KPIs, en este caso niveles de atención, AHT (tiempo medio de operación) y desviación de la previsión frente a la actividad real.
Sin hacer ningún filtro de tiempo, vemos que lo que llevamos de servicio estamos dentro de los objetivos marcados en cuanto a niveles de atención y desviación de la actividad, pero en cambio estamos muy desviados en los tiempos de la llamada.
¿Dónde habría que poner foco? en la mejora del AHT del canal Cita Previa porque claramente es el que más penalizado está respecto al resto. A partir de este foco, entraríamos a revisar por qué hay también una mayor desviación entre territorios.


Contenido del Dashboard

Se ha trabajado con un archivo CSV
BBDD_Dashboard.csv

El archivo mencionado se transforma en un archivo .XLS para realizar el proyecto de Dashboard
Proyecto_dashboard.xlsx

Además, en el repositorio también tenemos el archivo README.md

El dashboard se alimenta de datos estructurados en la hoja dinámicas_dashboard y presenta los siguientes indicadores:

1. Objetivos Claves ✅

Objetivo NAT: 0.8

Objetivo AHT (Average Handling Time): 00:03:00

Objetivo de Desviación: +/-10%

2. Indicadores de Desempeño ⬆️

Niveles de atención global

Promedio de NDA (Nivel de Atención por Departamento)

Promedio de AHT (Tiempo promedio de gestión de atención)

3. Análisis de Desviaciones 💹

Desviación global: Evaluación de la variabilidad en la atención

Promedio de DESV. OFRECIDAS VS PREVISIÓN: Comparación entre valores reales y previstos

Uso del Dashboard

Explorar los indicadores de atención y gestión de tiempos.

Analizar desviaciones con respecto a los valores previstos.

Identificar oportunidades de mejora en la eficiencia del servicio.

Requisitos 🏗️

Para utilizar el dashboard, asegúrese de contar con un software compatible con archivos Excel (.xlsx), como:

Microsoft Excel

Google Sheets (conversión requerida)

LibreOffice Calc
