# tablacalendario
🗓️ Generador de Tabla Calendario (Lenguaje M)

Este script en lenguaje M (Power Query) se utiliza para transformar una tabla base de fechas (ConMes) agregando múltiples columnas con información temporal relevante. Esto resulta muy útil para modelado de datos en Power BI, permitiendo crear segmentaciones por mes, día, semana, trimestre, etc.

🚀 ¿Qué hace este script?

Agrega las siguientes columnas a una tabla de fechas:

Columna	Descripción
NombreMes	Nombre completo del mes en español (ej. "enero")
Día	Día del mes (1-31)
NombreDia	Día de la semana en español (ej. "lunes")
Semana	Número de la semana del año (1-53)
AñoMes	Concatenación del año y mes en formato AAAA-MM (ej. "2024-01")
Trimestre	Número de trimestre (1 a 4)
AñoTrimestre	Concatenación del año y trimestre en formato AAAA-T# (ej. "2024-T1")
EsInicioMes	Booleano que indica si la fecha es el primer día del mes
EsFinMes	Booleano que indica si la fecha es el último día del mes
EsDiaLaboral	Booleano que indica si la fecha es un día laboral (lunes a viernes)

