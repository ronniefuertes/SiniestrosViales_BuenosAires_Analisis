![Siniestros Viales](assets/seguridad_vial.png)
# Proyecto: Siniestros Viales

## Descripción del Proyecto

Los siniestros viales, también conocidos como accidentes de tráfico o accidentes de tránsito, son eventos que involucran vehículos en las vías públicas y que pueden tener diversas causas, como colisiones entre automóviles, motocicletas, bicicletas o peatones, atropellos, choques con objetos fijos o caídas de vehículos. Estos incidentes pueden tener consecuencias que van desde daños materiales hasta lesiones graves o fatales para los involucrados.

En Argentina, cada año mueren cerca de 4.000 personas en siniestros viales. Aunque muchas jurisdicciones han logrado disminuir la cantidad de accidentes de tránsito, esta sigue siendo la principal causa de muertes violentas en el país. 

El Observatorio de Movilidad y Seguridad Vial (OMSV) solicita la elaboración de un proyecto de análisis de datos, con el fin de generar información que le permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales de los siniestros viales.

## Estructura del Repositorio

- `/assets`
   - Imagenes para la generación del documento.

- `/dashboard`
   - `siniestros_viales.pbix`: Dashboard interactivo con el análisis de los siniestros viales.

- `/datasets`
   - `hechos.csv`: Archivo principal que contiene los datos sobre siniestros viales.
   - `victimas.csv`: Archivo que contiene los datos sobre las víctimas de los siniestros viales.
   - `siniestros.csv`: Archivo, con la información completa, utilizado para la generación del dashboard.
   - `diccionario_de_datos.xlsx`: Archivo que contiene el significado de los datos sobre hechos y victimas.

- `/datasets`
   - `República de Argentina-cnphv2022.pdf`: Resultados provisionales del Censo Nacional de Población, Hogares y Viviendas 2022.

- `EDA.ipynb`: Notebook con el Análisis Exploratorio de Datos.
- `README.md`: Documento actual.

## Resumen del análisis

* La mayoría de los siniestros viales involucran a una sola víctima: Esto indica que la gran mayoría de los incidentes tienen un impacto limitado en términos de víctimas.

* Patrones de víctimas a lo largo del año: A inicios y finales de año existe un aumento en la cantidad de víctimas. En el período de 2016 al 2018 hay poca variación en la cantidad de víctimas, lo que podría considerarse como un período estacionario. En el período de 2018 al 2021 hay una tendencia bajista, indicando una disminución en la cantidad de víctimas. Sin contar 2020, que fue atípico en términos de movilidad por la pandemia.

* Más de tres cuartas partes de las víctimas fatales fueron de sexo masculino (77%) y el 49% tenían entre 25 y 54 años de edad.

* Horarios críticos para siniestros viales: Los momentos más críticos son los horarios de ir al trabajo (5-9 h), de almuerzo (12-14 h) y de salida del trabajo (17-18 h). Los fines de semana también son propensos a incidentes con un alto número de víctimas.

* Comunas con más víctimas: Las comunas 1, 4, 7, 8 y 9 registran la mayor cantidad de siniestros, lo que sugiere factores que contribuyen a un elevado número de víctimas en esas áreas.

## KPI

* Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior

    Definimos a la tasa de homicidios en siniestros viales como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico. Su fórmula es: (Número de homicidios en siniestros viales / Población total) * 100,000

* Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior

    Definimos a la cantidad de accidentes mortales de motociclistas en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal. Su fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100

* Reducir en un 10% la cantidad de peatones fallecidos en el último año, en CABA, respecto al año anterior

    Definimos a la cantidad de peatones fallecidos en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas las víctimas. Su fórmula para medir la evolución de los accidentes mortales con peatones es: (Número de accidentes mortales con peatones en el año anterior - Número de accidentes mortales con peatones en el año actual) / (Número de accidentes mortales con peatones en el año anterior) * 100