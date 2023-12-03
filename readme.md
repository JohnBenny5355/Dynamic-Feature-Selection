# Access Point Search

This repository contains the programatic implementation of Access Point Search Algorithm (APSA) which automates the task of finding the optimal set of Access Points that can aid Deep Learning based Anomaly Detector models in detecting anomalies in a particular system.

## Table Of Contents
1. Getting Started
    - Prerequisites
    - Running the code
3. Configuring APSA

## Getting Started
### Prerequisites
To run the code, it is recommended to create a virtual environment and install the required packages. 
To install the required packages, run the following code:

```bash
pip install -r requirements.txt
```
### Execution of CMI-EVSI
To start CMI-EVSI, use the jupyter notebook from the folder with corresponding description of requirements.

### Steps to use CMI-EVSI

The following steps are to be followed to use CMI-EVSI:
1. Place the dataset in the `data` folder.
2. Make it available for access from the main file.
3. Also include the packages corresponding to dynamic selection.

The program will run CMI-EVSI and will provide the optimal set of Access Points that can be used to detect anomalies in the system and also calculate the cost incurred in selecting the access points.

More technical details about the structure of the code can be found in the [docs](docs) folder.
