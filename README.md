# Pump-it-Up-Data-Mining-Competition

Este repositorio contiene el desarrollo de un modelo para el concurso **"Pump it Up: Data Mining the Water Table"**. Utilizando información proporcionada por el Gobierno de Tanzania, el concurso tiene como objetivo predecir qué bombas de agua del país son:

- Funcionales
- No funcionales
- Necesitan reparación

## Resultados

Después de limpiar, ordenar, analizar y realizar *feature engineering* con distintas librerías de Python (apoyado por herramientas de inteligencia artificial), logré obtener mi mejor puntaje de **0.8156** con un modelo **Random Forest**, posicionándome en el lugar **3111 entre más de 18,000 participantes**.

## Contenido del repositorio

- `Práctica_Maximiliano_Frías_Transformaciones_FE.ipynb`: Notebook dedicado al preprocesamiento y análisis exploratorio de los datos.
- `Práctica_Maximiliano_Frías_Modelos.ipynb`: Notebook enfocado en la construcción del modelo, ajuste de hiperparámetros y mejora del desempeño.

## Descripción de variables del dataset

A continuación, una lista de las principales variables disponibles:

- `amount_tsh`: Total static head (cantidad de agua disponible)
- `date_recorded`: Fecha de ingreso del registro
- `funder`: Entidad financiadora del pozo
- `gps_height`: Altura del pozo
- `installer`: Organización que instaló el pozo
- `longitude`, `latitude`: Coordenadas GPS
- `wpt_name`: Nombre del punto de agua
- `num_private`: Información privada (vacía en muchos casos)
- `basin`, `subvillage`, `region`, `lga`, `ward`: Ubicación geográfica
- `region_code`, `district_code`: Ubicación geográfica (codificada)
- `population`: Población beneficiada
- `public_meeting`: ¿Se realizó una reunión pública?
- `recorded_by`: Entidad que registró la observación
- `scheme_management`, `scheme_name`: Tipo de gestión del sistema
- `permit`: ¿Cuenta con permiso?
- `construction_year`: Año de construcción
- `extraction_type`, `extraction_type_group`, `extraction_type_class`: Tipo de extracción
- `management`, `management_group`: Tipo de gestión
- `payment`, `payment_type`: Método de pago
- `water_quality`, `quality_group`: Calidad del agua
- `quantity`, `quantity_group`: Cantidad de agua
- `source`, `source_type`, `source_class`: Fuente de agua
- `waterpoint_type`, `waterpoint_type_group`: Tipo de punto de agua

## Ejemplo de fila del dataset

```text
amount_tsh              300.0
date_recorded           2013-02-26
funder                  Germany Republi
gps_height              1335
installer               CES
longitude               37.2029845
latitude                -3.22870286
wpt_name                Kwaa Hassan Ismail
num_private             0
basin                   Pangani
subvillage              Bwani
region                  Kilimanjaro
region_code             3
district_code           5
lga                     Hai
ward                    Machame Uroki
population              25
public_meeting          True
recorded_by             GeoData Consultants Ltd
scheme_management       Water Board
scheme_name             Uroki-Bomang'ombe water sup
permit                  True
construction_year       1995
extraction_type         gravity
extraction_type_group   gravity
extraction_type_class   gravity
management              water board
management_group        user-group
payment                 other
payment_type            other
water_quality           soft
quality_group           good
quantity                enough
quantity_group          enough
source                  spring
source_type             spring
source_class            groundwater
waterpoint_type         communal standpipe
waterpoint_type_group   communal standpipe
