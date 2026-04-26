## 📊 Dataset Summary: Enriched Tourism Dataset Paris (POIs)

This dataset is a cleaned and enriched version of the Paris subset from the **Tourpedia** project, originally sourced from [tour-pedia.org](http://tour-pedia.org/download/paris-attraction.csv) [Enriched Tourism Dataset Paris (POIs)](https://data.mendeley.com/datasets/vh4g4g2322/1). It is designed for tourism-oriented data analysis, recommendation systems, and natural language processing tasks.

### 🔃 Releases

* ***Paris.csv***: https://github.com/tantikristanti/Datasets/releases/download/paris-tourism/Paris.csv
* ***Paris_annotated.csv***: https://github.com/tantikristanti/Datasets/releases/download/paris-tourism/Paris_annotated.csv

### 📦 Dataset Composition

| File                          | Description                                                                                           | Key Columns                                                                                                                                                                                                                                     |
| ----------------------------- | ----------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Paris.csv**           | Cleaned POI data with user-generated reviews aggregated from Google Places, Foursquare, and Facebook. | Unique identifier, POI name, category, address, latitude, longitude, details, and**multi-format reviews**(all words, only nouns, nouns+verbs, noun+adjectives, nouns+verbs+adjectives)[](https://data.mendeley.com/datasets/vh4g4g2322/1) |
| **Paris_annotated.csv** | Ground truth manual annotations categorizing each POI into **12 pre-defined categories**.      | POI name, address, and 12 category columns where `1`indicates membership; blanks indicate non-membership                                                                                                                                      |

### 🔄 Data Cleaning & Quality

* **Original entries** : 4,351 POIs.
* **Cleaned entries** : 477 high-quality POIs after removing erroneous and incomplete data points, followed by further validation to ensure data integrity.

## 📔 Attribution statement

The **"Enriched Tourism Dataset Paris (POIs)"** created by Ramon Hermoso, Sergio Ilarri, and Raquel Trillo-Lado, published by Mendeley Data on October 30, 2024, under a ***CC BY 4.0 license***.
This repository does not make any changes to the original dataset. The original work can be accessed through its DOI: `10.17632/vh4g4g2322.1`.
