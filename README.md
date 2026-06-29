# Ski Resort Analytics - Dashboard Financiero y Operativo 🎿📊

![Uploading image.png…](https://github.com/AntonioSoto-DataAnalyst/Ski_Resort_Analytics-Dashboard_Financiero_y_Operativo/blob/main/Parque.png?raw=true)

## Descripción del Proyecto
Este proyecto de portafolio consiste en el desarrollo de un panel de control integral en Microsoft Excel para la empresa ficticia de turismo de invierno "SKI Valle Silbador". El objetivo del análisis fue limpiar un conjunto de datos transaccionales con inconsistencias y estructurarlo para proyectar promociones, comisiones cruzadas y calcular la rentabilidad real de los pases de temporada.
## Limpieza y Modelado de Datos

## El proyecto requirió un fuerte componente de normalización de datos antes del análisis:
- Estandarización: Corrección de formatos de fecha erróneos (registros de 2017 ajustados a 2018) y traducción de los días de la semana de inglés a español.
- Corrección de Errores: Limpieza de espacios excedentes y faltas de ortografía en la base de uso de lifts diarios.

## Lógica de Negocios y Funciones Implementadas
Se formularon reglas de negocio complejas para extraer métricas financieras precisas:
- Cálculo de Ingresos por Paquetes: Puesto que la base de datos no incluía el identificador del hotel, se derivó mediante el precio pagado por día, identificando tarifas únicas (ej. Ol Hotels a $105, Elton Hotel a $110, Ski Inn a $75, etc.).
- Análisis de Rentabilidad (Pases de Temporada): Se calculó la ganancia real de los visitantes con pase "Ilimitado" considerando su precio de venta ($1,950) menos el costo operativo de $92 por cada uso del lift.
- Se identificó el punto de quiebre (21 usos) donde el cliente comienza a generar pérdidas.
- Proyección de Promociones: Se calculó el impacto financiero de regalar días extra a visitantes frecuentes (1 día por 7-8 visitas, 2 días por 9 visitas) y el costo potencial de subsidiar rentas de equipo por $30 USD a compradores fuera de temporada.
- Cálculo de Comisiones: Automatización del pago de comisiones fijas ($15 USD) a parques de la red HEROIC no tabulados.

## KPIs Destacados del Dashboard
- Total de ventas ($4.07M) y Ganancia neta por pases de temporada ($1.19M).
- Porcentaje de visitantes por parque de origen (Red HEROIC).
- Análisis de uso de Lifts por trimestre y segmentación de los esquiadores de mayor uso.
