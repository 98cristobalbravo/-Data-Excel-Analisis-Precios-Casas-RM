# Análisis Exploratorio: Valor de Casas Usadas en la Región Metropolitana de Chile

Este repositorio contiene un análisis exploratorio realizado sobre el dataset [Valor Casas Usadas, Chile, RM, 18/07/2023](https://www.kaggle.com/datasets/luisfelipetn/valor-casas-usadas-chile-rm-08032023) disponible en Kaggle. El dataset incluye avisos de venta de casas en la Región Metropolitana, Santiago.

## Descripción del Proyecto

Este proyecto fue realizado con el objetivo de mejorar mis habilidades en análisis de datos. Utilicé Excel para limpiar y analizar el dataset mencionado, enfocado en:

- **Limpieza de Datos**: Eliminación de valores duplicados y columnas innecesarias, transformación de tipos de datos, y formateo de la información para un mejor análisis. Por ejemplo, los datos originales incluían columnas como:

    | Price_CLP  | Price_UF | Price_USD | Comuna       | Ubicacion   | Dorms | Baths | Built Area | Total Area | Parking | id       | Realtor                                 |
    |------------|----------|-----------|--------------|-------------|-------|-------|------------|------------|---------|----------|-----------------------------------------|
    | 1,423,600  | 40       | 1,773     | LoBarnechea | Eltranque   | 4     | 4.0   | 200.0      | 831.0      | 6.0     | 12,302,427| OSSANDON CORREDORES ASOCIADOS S.A.      |

    Luego de la limpieza, la información fue simplificada y estructurada de la siguiente manera:

    | PRECIO CLP  | PRECIO USD | COMUNA      | DORMITORIOS | BAÑOS | AREA CONSTRUIDA | AREA TOTAL | ESTACIONAMIENTOS | RANGO AREA CONSTRUIDA |
    |-------------|------------|-------------|-------------|-------|-----------------|------------|------------------|-----------------------|
    | $1,423,600  | $1,773     | Lo Barnechea| 4           | 4     | 200             | 831        | 0                | 501-1000              |

- **Análisis y Visualización**: Creación de gráficos que permiten visualizar tendencias y patrones en los datos, como la distribución de precios por comuna, el número de habitaciones y baños, y la relación entre el área construida y el precio.

## Futuro Trabajo

Actualmente estoy aprendiendo sobre web scraping y manipulación de datos en Python. En proyectos futuros, planeo realizar estos mismos procesos de análisis de manera automatizada utilizando Python. Esto incluye:

- **Extracción de Datos**: Usar técnicas de web scraping para obtener datos actualizados directamente desde sitios web.
- **Limpieza y Transformación de Datos**: Utilizar librerías como `Pandas` para limpiar y estructurar los datos.
- **Visualización**: Implementar visualizaciones más avanzadas usando librerías como `Matplotlib` y `Seaborn`.

## Visualizaciones

A continuación, se muestran algunos de los gráficos creados durante este análisis:

![image](https://github.com/user-attachments/assets/d7a61ae4-edf4-465f-8a8f-82a6296486a0)


## Conclusiones

Este análisis inicial me ha permitido entender mejor el proceso de limpieza y análisis de datos en Excel, y estoy entusiasmado por aplicar y expandir estos conocimientos en Python en un futuro cercano.
