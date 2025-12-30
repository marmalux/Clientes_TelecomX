# Baja de clientes en Telecom X
Debido a la alta baka de clientes se ha creado un proyecto **Churn de clientes**, el cual consiste en identificar la razón o razones de ello, para estos se hara un proceso ETL para recopilar, limpiar, analizar los datos para brindarselo al equipo de ciencia de datos para encontrar modelos predictivos.

## Tecnologías / herramientas utilizadas
* Python (Google Colab)
* Pandas
* De Matplotlip su módulo pyplot
* Seaborn
* Librerías "request" y "json"

## Dataset

los datos se obtienen de el archivo crudo *raw* de github proporcionado para el análisis.
```
https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/refs/heads/main/TelecomX_Data.json
```
## Ejecución
La ejecución del proyecto se puede hacer en Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/marmalux/Clientes_TelecomX/blob/main/Clientes_TelecomX.ipynb)

## Resultados a tomar en cuenta
### categorías personales
![Servicio de internet](https://raw.githubusercontent.com/marmalux/Clientes_TelecomX/refs/heads/main/images/categorias_personas_resultado.png)
### Categorías varias
![categorias_otras](https://raw.githubusercontent.com/marmalux/Clientes_TelecomX/refs/heads/main/images/comparacion_demas_categorias_resul.png)

### Pago y tiempo de uso
![pago clientes](https://raw.githubusercontent.com/marmalux/Clientes_TelecomX/refs/heads/main/images/incidencias_pago_cliente.png)

En cuanto al tiempo de usuarios.
![meses_contrato](https://raw.githubusercontent.com/marmalux/Clientes_TelecomX/refs/heads/main/images/meses_contrato_promedio.png)

## Conclusiones en base a resultados
  **Personal**

Hay relación entre las personas que tienen a alguien mas en casa como la pareja (esta mas) y los dependientes los que se fueron de la compañia, la edad no esta muy relacionada pues son comparables con los que quedaron.
Los servicios mas solicitados de los que no son clientes fueron DSL y fibra optica, pero en su mayoría usaban el servicio de teléfono, en cambio los clientes que aun quedan usan mas fibra optica y no hacen mucho uso de la linea telefónica.

  **Pago**

Según los gráficos de pago, los clientes que se fueron pagaban mas por dia si usaban fibra óptica que los que tenian el servicio DSL, gran parte era por que tenían mas líneas telefónicas, en cambio los que aun son clientes, pagan un poco mas por dia en servicio telefonico pero con menos lineas y por ello menos hacen uso de ella, la mayoria tiene el servicio de fibra pagan menos por dia que los que se fueron.

Otra cosa a tomar en cuenta es que en su mayoría los clientes que se fueron pagaban en generam menos o casi el mínimo por dia que los que se quedaron.

Esto puede implicar que se fueron por que pagaban mas por el servicio de fibra optica que los nuevos usuarios y que el pago que hacian en el servicio telefónico (que era lo que la mayoría querían), además, los que no tenian el servicio telefonico pagaban mas que los que actualmente no tienen servicio telefónico, por lo que el pago es importante a tomar en cuenta.


  **Tiempo y tipo de contrato**

Aunque La mayoría prefirieron el contrato por mes, muchos de los que ya no son clientes optaron por contratos largos de año o 2 años por lo que puede indicar que muchos esperaron a que terminara su contrato para irse por lo que no fué hasta que terminara el contrato el que se notara la baja de clientes

## Recomendación final
Se pudo observar que la mayoría que se fueron fue debido al pago ya sea por el servicio o por que el hecho de tener acompañantes afectara, y además que los servicios que querían (que en su mayoría fue telefonía) aumento el costo comparado con los usuarios que quedan, por lo que podría ayudar es las promociones a estos viejos clientes dandoles mejor precio por su servicio telefónico o incluso darle un servicio extra como lo podria ser la televisión para hacer mas llamativo debido a que solo estaban por el servicio telefónico. Esto podria ayudar a mantener a viejos clientes por las ofertas debido al tiempo en el cual han estado en la empresa.
