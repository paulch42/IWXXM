# OpenAPI
An [OpenAPI](https://www.openapis.org) model of [IWXXM, version 2023-1](https://schemas.wmo.int/iwxxm/2023-1/). The structure of the model is based on the [IWXXM logical model](https://schemas.wmo.int/iwxxm/2023-1/html/) (i.e., the UML model). There is one folder for each package in the UML model, and one _yaml_ file for each diagram.

The contents of the model are:

| Item | Description
|-|-|
| METAR_SPECI | A model of the IWXXM _METAR/SPECI_ package. |
| TAF | A model of the IWXXM _TAF_ package. |
| AIRMET | A model of the IWXXM _AIRMET_ package. |
| SIGMET | A model of the IWXXM _SIGMET_ package. |
| Tropical Cyclone Advisory | A model of the IWXXM _Tropical Cyclone Advisory_ package. |
| Volcanic Ash Advisory | A model of the IWXXM _Volcanic Ash Advisory_ package. |
| Space Weather Advisory | A model of the IWXXM _Space Weather Advisory_ package. |
| WAFS Significant Weather Forecast | A model of the IWXXM _WAFS Significant Weather Forecast_ package. |
| Meteorological_Feature | A model of the IWXXM _Meteorological Feature_ package. |
| Common | A model of the IWXXM _Common_ package. |
| Measures | A model of the IWXXM _Measures_ package. |
| METCE | A minimal model of METCE features to support the IWXXM model. |
| AIXM | A minimal model of AIXM features to support the IWXXM model. |
| GML | A minimal model of GML entities to support the IWXXM model. |
| Examples | Example messages that comply with the OpenAPI schema. |
| check | Scripts that validate the IWXXM OpenAPI schema files. Depends on Python and the [openapi-spec-validator](https://pypi.org/project/openapi-spec-validator/) package. |

Lower level detail is not covered, particularly relating to AIXM, GML and METCE.