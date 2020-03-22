# COVID-19-Colombia

## dataset.csv
Datos tal cual reportados por el INS Colombia

## time_series.csv

Columnas:

* `fecha`: Fecha del caso reportado por el INS
* `muertes`: Número de muertes presentadas hasta ese día
* `total`: Total de casos confirmados hasta ese día
* `dia`: Día desde el paciente cero
* `casos_nuevos`: Casos nuevos presentados en ese día
* `casos_activos`: Casos activos hasta ese día: totales - muertes - recuperados
* `recuperados*`: Número de recuperados hasta ese día

*El INS hasta ahora no está reportando los casos recuperados así que la información se está tomando de otras fuentes: Ministerio de Salud, fuentes de noticias, cuentas oficiales de alcaldías y gobernaciones en redes sociales.
