# nx-challenge

## Objetivo

La idea es que uses los datasets adjuntos en el mail para hacer un modelo que pueda predecir la columna "TARGET".

### Descripcion

Cada una de las filas del archivo (indexada por SK_ID_CURR) corresponde a una persona distinta que nos pidió un préstamo, y la columna "TARGET" dice qué ocurrió con ese pedido en particular (es decir, tiene un 1 si su pago se atrasó , es decir, que entraron en default, y 0 si no lo hizo). La idea es que puedas hacer un proceso que permita predecir los clientes futuros que van a entrar en default sobre el préstamo.
El archivo "HomeCredit_columns_description - HomeCredit_columns_description.parquet" tiene la información disponible sobre cada una de las columnas de los otros archivos adjuntos. 

### Datos Utilizados

Se utilizan 3 tablas en formato parquet:
drive-download-20221102T125102Z-001/Copia de application_train.parquet
drive-download-20221102T125102Z-001/Copia de credit_card_balance.parquet
drive-download-20221102T125102Z-001/Copia de installments_payments.parquet

Otra tabla tiene los significados de cada una de las variables en dichas tablas:
drive-download-20221102T125102Z-001/Copia de HomeCredit_columns_description - HomeCredit_columns_description.parquet

#### Diagrama Entidad-Relación

![Alt text](images/DER.png?raw=true')


