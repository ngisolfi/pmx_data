# pmx for ga

Problem type: Time to failure prediction

Note: Data is hosted on kaggle, and requires setup before downloading (see comments in get_data.sh)

|  |
|  |
|  |
## Sources

Data location: https://www.kaggle.com/datasets/hooong/ngafid-mc-20210917

No data citation available

No data license available.

## Additional information
# PREDICTIVE MAINTENANCE FOR GENERAL AVIATION - DATASET DESCRIPTION:

The dataset comes from the NGAFID Maintenance Classification (NGAFID-MC). This is a novel benchmark in terms of difficulty, number of samples and sequence length. This Repository which is available in Documentation folder consist of over 7500 labeled flights, representing over 11500 hours of per second flight data recorder readings of 23 sensor parameters from Cessna 172S.
The example sensors (internal, external and operational) taken into consideration are as follows: engine RPM, oil temperature, oil pressure, gasket temperature, airspeed, pitch, roll, outside air temperature

Abbreviation NGAFID stands for National General Aviation Flight Information Database. The NGAFID allows GA (General Aviation) pilots to analyze and share their flight data in two ways. First, operators equipped with avionics capable of recording flight data can upload flight and engine data anonymously into NGAFID.

Some of the researchers around the world like Hong Yang, Aidan LaBella, Travis Desell (their article is added to the Documentation folder and citation can be found in the SOURCE file), managed to train their models, and add them to the NGAFID in order to allow users to potentially detect flights that require maintenance as well as provide feedback to further expand and refine the NGAFID-MC dataset.
In total the NGAFID contains over 900 000 hours of flight data generated by over 70 000 flights by 12 various aircraft types from 65 fleets and individual users, which gives a result of over 3.15 billion per second flight data records across 103 potential flight data recorder parameters.

The attached database consists of records collected over a period of 5 years from maintenance from the fleet, which were then clustered by type of maintenance problem and further verified by domain experts for the project under development.
Flights were further extracted from the NGAFID and then labeled as: before the date of the maintenance process and after the date of the maintenance process. And this is the way the Multivariate time series sensor data has been created, giving a possibility to train predictive maintenance models.
The record notebook data was clustered into 39 different maintenance issue types, but the Documentation folder contains datasets for the most common maintenance issues:
- Cluster 28 (C28) with 1432 pre and 984 post examples --> about intake gasket leak/damage (in total 1674 maintenance records).
- Cluster 37 (C37) with 2814 pre and 2275 post examples --> about rocker cover loose/leak/damage (in total 1248 maintenance records). 

Records from 5 flights preceding records of maintenance performed were exported from NGAFID to show data on flights related to maintenance issues.
Two types of data were exported: from flights with no maintenance issues and flights with maintenance issues (unless they were within 5 flights of any other maintenance issue). Flights that lasted less than 30 minutes were excluded, as they mostly do not include any actual flights.
All collected flights were then filtered within 2 days of maintenance (before and after).
Since the maintenance records provide the day and not the time of an action, those flights which occurred on the same day as the maintenance, have been excluded because of impossibility to determine if they occurred before or after maintenance.

# SOURCES RELATED TO THE DATASET (PREDICTIVE MAINTENANCE FOR GENERAL AVIATION):

Below you can find some useful citation, references and links for the project purposes.


The dataset has been dowloaded from the kaggle website that is available under the following link: https://www.kaggle.com/datasets/hooong/ngafid-mc-20210917


The citation and references for the original article, that uses this dataset for their analysis purposes with a detailed description (the article is available to download from the Documentation folder):
YANG, Hong; LABELLA, Aidan; DESELL, Travis. Predictive maintenance for general aviation using convolutional transformers. In: Proceedings of the AAAI Conference on Artificial Intelligence. 2022. p. 12636-12642.


Another citation to the article related to the subject (the article is available to download from the Documentation folder):
Akhbardeh, Farhad & Desell, Travis & Zampieri, Marcos. (2020). MaintNet: A Collaborative Open-Source Library for Predictive Maintenance Language Resources. 7-11. 10.18653/v1/2020.coling-demos.2. 