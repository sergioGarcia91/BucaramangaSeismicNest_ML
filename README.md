Machine learning in the Bucaramanga Seismic Nest.

# Towards Earthquake forecasting in the Bucaramanga Nest, a machine learning approach

This repository compiles the notebooks used for generating Artificial Neural Network (ANN) models to estimate the occurrence of seismic events with magnitudes greater than 4.5. The work was developed in Google Colab, using a sequential approach in which the dataset was progressively evaluated and considerations were made as the work advanced.

The content of each notebook is described below:

- **ML_SismosNido_1**: Contains the initial exploratory analysis of the models and the first versions of the neural networks.
- **ML_SismosNido_2**: New conditions for training the models are proposed, now considering periods of 6 months and 1 year.
- **ML_SismosNido_3**: An input analysis is performed considering the number of seismic events greater than or equal to the value of interest for each column.
- **ML_SismosNido_4**: A difference in the number of events since 2009 is observed, so data from that year onward is used. Confusion matrices of the models up to that point are also included.
- **ML_SismosNido_5**: Based on the premise that there is an energy release affecting the number of higher magnitude events generated, lower magnitudes are included for model training from 2009 onward.
- **ML_SismosNido_6b**: Notebook for creating graphs and decision-making evaluation.
- **ML_SismosNido_7**: Based on previous results, the ISC catalog for the same geographic quadrant is consulted.
- **ML_SismosNido_8**: The number of layers in the models is modified to adjust them to a pyramidal structure.
- **ML_SismosNido_9**: Notebook presenting a tentative and speculative calculation of the orientation and inclination of the plane generated from the location of the seismic events in the "nido."
- **ML_SismosNido_10**: This notebook was developed as part of a test conducted during the manuscript's revision phase.

# Catalog

The consultation was conducted using the Seismicity Catalog of the Servicio Geológico Colombiano: [http://bdrsnc.sgc.gov.co/paginas1/catalogo/index.php](http://bdrsnc.sgc.gov.co/paginas1/catalogo/index.php).

## Characteristics of the Quadrant:

| Parameter | Min  | Max  |
|-----------|------|------|
| Longitude | -73.4 | -72.8 |
| Latitude  | 6.5  | 7.1  |
| Year      | 1994 | 2023 |

> Subsequently, events from January and February 2024 were considered for reevaluating the models, as the models for December indicated a possible occurrence of seismic events.

## Data

The original information is available for download in the **Data** folder.

# Models

In the respective folders named **ModelosMLP_Class**, you can find the different models generated during each version of the training process.




