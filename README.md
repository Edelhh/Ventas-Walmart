**Análisis de ventas Walmart 2010 – 2012.**

Link de data: https://www.kaggle.com/datasets/mikhail1681/walmart-sales/data

**Requerimiento empresarial.**

El objetivo principal de este proyecto es analizar cómo diversos factores externos influyen en las ventas semanales y poder así ofrecer recomendaciones estratégicas que permitan optimizar las ventas. A continuación, detallo los aspectos clave que nos gustaría explorar:

1. **Análisis de Tendencias de Ventas:** Identificar patrones y tendencias en las ventas semanales a lo largo del tiempo.
1. **Impacto de los Feriados:** Evaluar cómo los feriados afectan las ventas en diferentes tiendas.
1. **Influencias Externas:** Analizar el impacto de la temperatura, precios del combustible, CPI y tasas de desempleo en las ventas.
1. **Comparación entre Tiendas:** Realizar comparaciones de desempeño entre las diferentes tiendas.

**Diccionario de datos.**

El dataset de Walmart contiene las siguientes columnas:

1. **Store**: Identificador de la tienda.
1. **Date**: Fecha de la venta.
1. **Weekly\_Sales**: Ventas semanales.
1. **Holiday\_Flag**: Indicador de si la semana incluyó un feriado.
1. **Temperature**: Temperatura en la región de la tienda.
1. **Fuel\_Price**: Precio del combustible en la región de la tienda.
1. **CPI**: Índice de Precios al Consumidor.
1. **Unemployment**: Tasa de desempleo en la región de la tienda.

**Limpieza de datos y transformación.**

- Los datos no se encontraban con datos faltantes.
- Se cambio nombre de las columnas al español.
- Se cambio el valor de Feriados de 1 – 0 a Si y No.
- Nueva columna semana del año.
- Nuevas medidas promedio de semanal de ventas en feriados, sin feriados y promedio por tienda.

**Modelado de datos.**

A continuación, se muestra una captura de pantalla del modelo de datos. En este caso se usó solo una tabla.



**Panel de control de ventas.**

El panel de control de ventas terminado tiene tres páginas:

- La primera página resume las ventas durante las semanas de los diferentes años, también permite realizar comparaciones entre tiendas o conocer en su defecto el aporte de cada tienda.
- La segunda página resume el impacto de los feriados.
- La tercera página trata el impacto de las variables externas sobre las ventas.

**Conclusiones.**

- Se encuentra el mayor pico de ventas en los últimos meses de los años 2010 y 2011. Cabe mencionar que aún no se tiene datos de los últimos meses del 2012 pero se esperaría encontrar nuevamente un aumento de las ventas como en anteriores años.
- Las ventas obtenidas en las semanas que hubo un feriado fueron mayores en promedio que en las que no. Aunque esta observación se requiere estudiar más a fondo debido a la cantidad de datos con las que se cuenta en cada categoría.
- Respecto a las variables externas, la temperatura tiene un comportamiento parecido cada año, logrando las temperaturas más bajas en los últimos meses del año lo que está de acuerdo con la estación respectiva. 
- Los precios de combustible tienden a bajar para finales del año no obstante al inicio del año inicia su aumento de precio logrando su máximo alrededor del abril o mayo. 
- La tasa de desempleo tiende a disminuir respecto al tiempo, mientras el índice del precio del consumidor tiende a aumentar.
