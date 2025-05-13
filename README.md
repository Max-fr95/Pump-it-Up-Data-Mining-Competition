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

- `amount_tsh` - Total static head (amount water available to waterpoint)
- `date_recorded` - The date the row was entered
- `funder` - Who funded the well
- `gps_height` - Altitude of the well
- `installer` - Organization that installed the well
- `longitude` - GPS coordinate
- `latitude` - GPS coordinate
- `wpt_name` - Name of the waterpoint if there is one
- `basin` - Geographic water basin
- `subvillage` - Geographic location
- `region` - Geographic location
- `region_code` - Geographic location (coded)
- `district_code` - Geographic location (coded)
- `lga` - Geographic location
- `ward` - Geographic location
- `population` - Population around the well
- `public_meeting` - True/False
- `recorded_by` - Group entering this row of data
- `scheme_management` - Who operates the waterpoint
- `scheme_name` - Who operates the waterpoint
- `permit` - If the waterpoint is permitted
- `construction_year` - Year the waterpoint was constructed
- `extraction_type` - The kind of extraction the waterpoint uses
- `extraction_type_group` - The kind of extraction the waterpoint uses
- `extraction_type_class` - The kind of extraction the waterpoint uses
- `management` - How the waterpoint is managed
- `management_group` - How the waterpoint is managed
- `payment` - What the water costs
- `payment_type` - What the water costs
- `water_quality` - The quality of the water
- `quality_group` - The quality of the water
- `quantity` - The quantity of water
- `quantity_group` - The quantity of water
- `source` - The source of the water
- `source_type` - The source of the water
- `source_class` - The source of the water
- `waterpoint_type` - The kind of waterpoint
- `waterpoint_type_group` - The kind of waterpoint

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
