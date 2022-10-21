# Predictive and Prognostics Maintence Data Repository

Predictive Maintenance poses a number of challenges for machine learning. The general types of machine learning problems encountered in predictive maintenance are:

1. Time to failure prediction
2. Anomaly detection
3. Clustering
4. Fault detection and root cause analysis

The purpose of this repository is to help researchers start working on predictive maintenance quickly. It provides an overview of relevant predictive maintenance data and 'quick start' scripts for researchers. We call it the Predictive and prOgnostics maiNtenance data repositorY or (PONY) for short.

| **Dataset**                                                                                                                                              | **Description**                                                                                                                     | **Problems**                       | **Equipment Type**                  | **Note**                                                    |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------- | ----------------------------------- | ----------------------------------------------------------- |
| [electrical fault detection](https://github.com/autonlab/pmx_data/tree/main/pmx_data/electrical_fault_detection)                                         | Line currents and voltages of electrical system with 4 fault conditions                                                             | Fault Detection and Classification | Electrical                          |                                                             |
| [turbofan](https://github.com/autonlab/pmx_data/tree/main/pmx_data/turbofan)                                                                             | Multidimensional sensor data from simulated run to failure experiments                                                              | Time to event prediction           | Aircraft                            |                                                             |
| [solar power generation](https://github.com/autonlab/pmx_data/tree/main/pmx_data/solar_power_generation)                                                 | Power generation and weather data for 2 solar power plants                                                                          | Fault detection                    | Electrical                          |                                                             |
| [li-ion battery aging](https://github.com/autonlab/pmx_data/tree/main/pmx_data/li-ion_battery_aging)                                                     | Data from tests on 4 Lithium-Ion batteries cycled under random currents                                                             | Time to failure prediction         | Batteries                           |                                                             |
| [robot execution failures](https://github.com/autonlab/pmx_data/tree/main/pmx_data/robot_execution_failures)                                             | Sensor data from a robot after 5 different types of failures                                                                        | Time to failure prediction         | Robotics                            |                                                             |
| [production plant data for condition monitoring](https://github.com/autonlab/pmx_data/tree/main/pmx_data/production_plant_data_for_condition_monitoring) | Sensor data from 8 run-to-failure experiements on a production line component                                                       | Time to failure prediction         | Tools & Machinery                   |                                                             |
| [machinery faults datasets](https://github.com/autonlab/pmx_data/tree/main/pmx_data/machinery_faults_datasets)                                           | Extremely large dataset of simulated time series machinery data with 6 operating states, each of which can have several fault types | Fault classification               | Tools & Machinery                   |                                                             |
| [pmx from elevator industry](https://github.com/autonlab/pmx_data/tree/main/pmx_data/pmx_from_elevator_industry)                                         | Data on elevator ball bearing wear                                                                                                  | Time to failure prediction         | Tools & Machinery                   |                                                             |
| [predictive maintenance fault classification](https://github.com/autonlab/pmx_data/tree/main/pmx_data/predictive_maintenance_fault_classification)       | Sensor data from a drill press under induced fault conditions                                                                       | Fault detection and classification | Tools & Machinery                   |                                                             |
| [Predictive Maintenance for Electrical Wiring Faults](https://github.com/autonlab/pmx_data/tree/main/pmx_data/wiring_dataset)                            | A dataset to support automatic optical inspection tool for electrical components using computer vision.                             | Fault Detection                    | Electrical                          | Data is structured to be ready to used by a yolov5 network. |
| [gearbox fault diagnosis](https://github.com/autonlab/pmx_data/tree/main/pmx_data/gearbox_fault_diagnosis)                                               | Vibration measurements from healthy and faulty gearboxes with varying loads and recoring frequencies                                | Fault detection                    | Gearboxes & Mechanisms              |                                                             |
| [pump sensor](https://github.com/autonlab/pmx_data/tree/main/pmx_data/pump_sensor)                                                                       | Time series sensor readings from a water pump with status                                                                           | Anomaly detection                  | Tools & Machinery                   |                                                             |
| [Air pressure system failures in Scania trucks.](https://github.com/autonlab/pmx_data/tree/main/pmx_data/scania_trucks_air_pressure_system_failure)      | Classifying whether truck failure is a result of its air pressure system                                                            | Failure Classification             | land_vehicles                       |                                                             |
| [gearbox fault detection](https://github.com/autonlab/pmx_data/tree/main/pmx_data/gearbox_fault_detection)                                               | Bench test gearbox with 7 induced faults to detect in 3 channels, high frequency timeseries                                         | Fault Detection                    | Gearboxes & Mechanisms              |                                                             |
| [cnc mill tool wear](https://github.com/autonlab/pmx_data/tree/main/pmx_data/cnc_mill_tool_wear)                                                         | Time series machining data across 18 CNC milling experiments                                                                        | Fault Detection                    | Tools & Machinery                   |                                                             |
| [maintnet](https://github.com/autonlab/pmx_data/tree/main/pmx_data/MaintNet)                                                                             | Maintenance action write-ups for aircraft, automotive, and facility domains                                                         | Language model, event forecasting  | Aircraft, automotives, and facility |                                                             |
| [nasa milling prognostic dataset](https://github.com/autonlab/pmx_data/tree/main/pmx_data/nasa_milling_prognostic_dataset)                               | Investigating wear on a milling machine under several runs in various operating conditions                                          | Fault Detection                    | Tools & Machinery                   |                                                             |
| [one year industrial component degradation](https://github.com/autonlab/pmx_data/tree/main/pmx_data/one_year_industrial_component_degradation)           | High-frequency time series data documentating degradation of an industrial component over the course of a year                      | Time to failure prediction         | Tools & Machinery                   |                                                             |
| [autonomous underwater vehicle](https://github.com/autonlab/pmx_data/tree/main/pmx_data/autonomous_underwater_vehicle)                                   | Time series measurements from an underwater vehicle with 5 fault types                                                              | Fault Classification               | maritime                            | requires unrar                                              |
| [pmx iot sensor](https://github.com/autonlab/pmx_data/tree/main/pmx_data/pmx_iot_sensor)                                                                 | Data on failure of heat exchagers on an assembly line                                                                               | Time to failure prediction         | Tools & Machinery                   |                                                             |
| [diesel engine faults](https://github.com/autonlab/pmx_data/tree/main/pmx_data/diesel_engine_faults)                                                     | Diesel engine data from failure scenarios across 4 operating states                                                                 | Fault Detection                    | Engines                             |                                                             |
| [pmx for aircraft machine and components](https://github.com/autonlab/pmx_data/tree/main/pmx_data/pmx_for_aircraft_machine_and_components)               | telemetry time series data and maintenance records for aircraft                                                                     | Time to failure prediction         | Aircraft                            |                                                             |
| [hdd data](https://github.com/autonlab/pmx_data/tree/main/pmx_data/hdd_data)                                                                             | 2013 BlackBlaze hard drive failure data                                                                                             | Time to failure prediction         | Computer HW & IOT                   |                                                             |
| [plant fault detection](https://github.com/autonlab/pmx_data/tree/main/pmx_data/plant_fault_detection)                                                   | Time series measurement from 70 plants with 6 fault types                                                                           | Fault detection                    | Gearboxes & Mechanisms              |                                                             |
| [hydraulic sensor system](https://github.com/autonlab/pmx_data/tree/main/pmx_data/hydraulic_sensor_system)                                               | Time series sensor readings on a hydraulic test rig with target condition values                                                    | Fault Detection and Classification | Tools & Machinery                   |                                                             |
| [telemanom](https://github.com/autonlab/pmx_data/tree/main/pmx_data/telemanom)                                                                           | Telemetry data from 2 spacecraft with labeled anomalies in the testing set                                                          | Supervised Anomaly Detection       | Robotics                            |                                                             |
| [maintenance of naval propulsion plants](https://github.com/autonlab/pmx_data/tree/main/pmx_data/maintenance_of_naval_propulsion_plants)                 | Synthetic gas turbine data                                                                                                          | Time to failure prediction         | Maritime                            |                                                             |
| [pmx for ga](https://github.com/autonlab/pmx_data/tree/main/pmx_data/pmx_for_ga)                                                                         | Per-second sensor data from flights of a Cessna 172S preceeding maintenance                                                         | Time to failure prediction         | Aircraft                            |                                                             |
| [delta robot](https://github.com/autonlab/pmx_data/tree/main/pmx_data/delta_robot)                                                                       | Time series sensor data for a robot used in a production line                                                                       | Anomaly detection                  | Robotics                            |                                                             |
| [prediction of downtime duration](https://github.com/autonlab/pmx_data/tree/main/pmx_data/prediction_of_downtime_duration)                               | Predicting downtime duration of car manufacturing assembly lines                                                                    | Time to event prediction           | Tools & Machinery                   |                                                             |

# Adding a dataset

The minimum requirements to add a dataset to this repository are:

1. Create a directory for the data.
2. Write an 'info.yaml' file containing basic information about your dataset that will be used to generate a README (see [sample_info.yaml](https://github.com/autonlab/pmx_data/blob/main/sample_scripts/sample_info.yaml) for examples).
3. Optional: write a 'custom_writeup.md' markdown file containing any information about your dataset that is not encapsulated by info.yaml. This will be added to the generated README.
4. Write a 'get_data.sh' script to download the data and unpack it into a standard csv format.
5. Write a 'load_data.py' sample script to load the data into a pandas dataframe.

# Additional Resources

https://data.phmsociety.org/

# Wishlist

It would be good to have some visual inspection data here, a graphical data modality. I know there are people doing PMx with microscopy or aerial inspection. Not what WE do, but it certainly falls under the PMx bucket.