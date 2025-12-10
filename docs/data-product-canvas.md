
# Data Product Canvas - Berlin Traffic Accidents

## Metadata

* owner: Open Lifeworlds
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents
* license: CC-BY 4.0
* updated: 2025-11-11

## Input Ports

### berlin-lor-geodata

* manifest URL: https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/refs/heads/main/data-product-manifest.yml

### berlin-traffic-accidents-source-aligned

* manifest URL: https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-traffic-accidents-source-aligned/refs/heads/main/data-product-manifest.yml

## Transformation Steps

* [Data extractor](https://github.com/open-lifeworlds/open-lifeworlds-python-lib/blob/main/openlifeworlds/extract/data_extractor.py) extracts data from inout ports
* [Data blender](https://github.com/open-lifeworlds/open-lifeworlds-python-lib/blob/main/openlifeworlds/transform/data_blender.py) blends csv data into geojson files

## Output Ports

### berlin-traffic-accidents-geojson
name: Berlin Traffic Accidents Geojson
* owner: Open Lifeworlds
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/tree/main/data/03-gold/berlin-traffic-accidents-geojson
* license: CC-BY 4.0
* updated: 2025-11-11

**Files**

* [berlin-traffic-accidents-2018-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2018-00-city.geojson)
* [berlin-traffic-accidents-2018-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2018-00-district-regions.geojson)
* [berlin-traffic-accidents-2018-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2018-00-districts.geojson)
* [berlin-traffic-accidents-2018-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2018-00-forecast-areas.geojson)
* [berlin-traffic-accidents-2018-00-planning-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2018-00-planning-areas.geojson)
* [berlin-traffic-accidents-2019-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2019-00-city.geojson)
* [berlin-traffic-accidents-2019-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2019-00-district-regions.geojson)
* [berlin-traffic-accidents-2019-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2019-00-districts.geojson)
* [berlin-traffic-accidents-2019-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2019-00-forecast-areas.geojson)
* [berlin-traffic-accidents-2019-00-planning-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2019-00-planning-areas.geojson)
* [berlin-traffic-accidents-2020-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2020-00-city.geojson)
* [berlin-traffic-accidents-2020-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2020-00-district-regions.geojson)
* [berlin-traffic-accidents-2020-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2020-00-districts.geojson)
* [berlin-traffic-accidents-2020-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2020-00-forecast-areas.geojson)
* [berlin-traffic-accidents-2020-00-planning-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2020-00-planning-areas.geojson)
* [berlin-traffic-accidents-2021-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2021-00-city.geojson)
* [berlin-traffic-accidents-2021-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2021-00-district-regions.geojson)
* [berlin-traffic-accidents-2021-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2021-00-districts.geojson)
* [berlin-traffic-accidents-2021-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2021-00-forecast-areas.geojson)
* [berlin-traffic-accidents-2021-00-planning-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-geojson/berlin-traffic-accidents-2021-00-planning-areas.geojson)


### berlin-traffic-accidents-statistics
name: Berlin Traffic Accidents Statistics
* owner: Open Lifeworlds
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/tree/main/data/03-gold/berlin-traffic-accidents-statistics
* license: CC-BY 4.0
* updated: 2025-11-11

**Files**

* [berlin-traffic-accidents-statistics.json](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-traffic-accidents/refs/heads/main/data/03-gold/berlin-traffic-accidents-statistics/berlin-traffic-accidents-statistics.json)


## Observability

### Quality metrics

 * name: geojson_property_completeness
 * description: The percentage of geojson features that have all necessary properties

| Name | Value |
| --- | --- |
| berlin-traffic-accidents-2018-00-city.geojson | 100 |
| berlin-traffic-accidents-2018-00-districts.geojson | 100 |
| berlin-traffic-accidents-2018-00-forecast-areas.geojson | 100 |
| berlin-traffic-accidents-2018-00-district-regions.geojson | 100 |
| berlin-traffic-accidents-2018-00-planning-areas.geojson | 100 |
| berlin-traffic-accidents-2019-00-city.geojson | 100 |
| berlin-traffic-accidents-2019-00-districts.geojson | 100 |
| berlin-traffic-accidents-2019-00-forecast-areas.geojson | 100 |
| berlin-traffic-accidents-2019-00-district-regions.geojson | 100 |
| berlin-traffic-accidents-2019-00-planning-areas.geojson | 100 |
| berlin-traffic-accidents-2020-00-city.geojson | 100 |
| berlin-traffic-accidents-2020-00-districts.geojson | 100 |
| berlin-traffic-accidents-2020-00-forecast-areas.geojson | 100 |
| berlin-traffic-accidents-2020-00-district-regions.geojson | 100 |
| berlin-traffic-accidents-2020-00-planning-areas.geojson | 100 |
| berlin-traffic-accidents-2021-00-city.geojson | 100 |
| berlin-traffic-accidents-2021-00-districts.geojson | 100 |
| berlin-traffic-accidents-2021-00-forecast-areas.geojson | 100 |
| berlin-traffic-accidents-2021-00-district-regions.geojson | 100 |
| berlin-traffic-accidents-2021-00-planning-areas.geojson | 100 |


## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

consumer-aligned


---
This data product canvas uses the template of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).