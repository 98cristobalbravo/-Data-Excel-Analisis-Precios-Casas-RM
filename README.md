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

### Promedio precio USD por comuna
![image](https://github.com/user-attachments/assets/d7a61ae4-edf4-465f-8a8f-82a6296486a0)

### Número de avisos por comuna
![image](https://github.com/user-attachments/assets/0310ce45-8ffe-4ab7-82f2-37ebee202cb2)

### Promedio área construida y comuna de publicación de aviso
![image](https://github.com/user-attachments/assets/9661f135-097c-4a06-a008-b38cb92d407e)

### Promedio de estacionamientos y baños por comuna
![image](https://github.com/user-attachments/assets/4207170e-2339-43a1-9cf2-da6473d803d4)

### Número promedio de dormitorios por comuna
![image](https://github.com/user-attachments/assets/cbb6bfe4-6316-49c4-8692-2df2986b15fd)


## Conclusiones

- En el análisis realizado, se identificaron patrones claros en los valores de venta y características de las viviendas según la comuna.
- Comunas como El Monte, San Ramón, La Pintana y Lo Espejo destacan por tener los valores de venta más bajos, así como menores áreas construidas, número de baños y dormitorios.
- Este patrón contrasta con comunas como Vitacura, Providencia y Las Condes, donde los precios y características son considerablemente más altos.
- Además, se observó que Puente Alto es la comuna con el mayor número de avisos, lo cual es consistente con su gran tamaño y densidad poblacional.

