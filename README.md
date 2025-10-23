# Como hacer un analisis a la linea de tiempo del MCU
El Marvel Cinematic Universe (MCU) se ha construido como un universo exitoso en la pantalla grande. Con millones de fans, gran recaudación y un impacto cultural gigante, este ha marcado un antes y después en el cine de superhéroes. 

Sin embargo ¿ha seguido siendo tan exitoso?

En este blog explicaré como hacer una grafica en que se pueda ver la evolución de su exito, midiendo la critica, así como contrastandola con el presupuesto y las ganancias obtenidas.

## Paso 1: Obtener datos

Primero, como necesito información como el presupuesto, ganancias y opinion de la critica, usé la base de datos **Marvel Movie dataset** de M George que se puede encontrar en https://www.kaggle.com/datasets/minisam/marvel-movie-dataset

## Paso 2: Uso de paquetes y limpieza de datos

Lo primero que hay que hacer es identificar los paquetes a usar. En este caso usaremos dplyr

```{r}
library(dplyr)
library(readcsv)
```

```{r setup, include=FALSE}
library(dplyr)
```

En caso de no tener uno o más paquetes paquetes, se pueden instalar en el script del RMarkdown o la consola de la siguiente forma:

```{r setup, include=FALSE}
install.packages("dplyr")
```
Si no tienes más de uno, puedes hacer lo anterior para cada paquete, o tambien lo siguiente:

```{r setup, include=FALSE}
install.packages(c("dplyr", "readcsv"))
```
Con los paquetes instalados y en el library, podemos 

## Paso: Lectura de datos

## Paso: Graficación


