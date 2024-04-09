# An TinyML Incremental Learning Approach for Outlier Detection and Correction*


### ✍🏾Authors:  [Pedro Andrade](https://github.com/pedrohmeiraa), [Morsinaldo Medeiros](https://github.com/Morsinaldo), [Ivanovitch Silva](https://github.com/ivanovitchm), [Marianne Diniz](https://github.com/MarianneDiniz), and [Daniel G. Costa](https://github.com/daniel-gcosta).


# 1. Abstract/Overview
The Internet of Things (IoT) is a paradigm where computing and networking capabilities are integrated into objects, connecting them to the Internet. It is recognized as an important and emerging technology field with vast potential for improving lives, enhancing industrial processes, and enabling real-time decision-making. As the number of connected objects increases, the infrastructure for processing and handling the large volume of data generated also grows. In response, Edge Computing has emerged as a concept where data processing occurs closer to the data source, alleviating the burden on central servers. This article explores the integration of Tiny Machine Learning (TinyML) algorithms into resource-constrained devices, such as microcontrollers, enabling efficient data processing and inference directly on low-power devices. By leveraging lightweight algorithms and model optimization techniques, TinyML offers benefits such as reduced latency, enhanced privacy, improved energy efficiency, and increased autonomy for devices operating in remote or disconnected environments. This article presents an outlier detection and correction algorithm based on TinyML for deployment on resource-constrained computing devices. The algorithm was implemented in an OBD-II scanner as a proof of concept, where a microcontroller acquires real-time vehicle data, identifies outliers, and performs necessary corrections.
  
For a better didactic exposition, the results will be presented in 3 notebooks:

 1. :notebook: Explaining the TEDA Algorithm: Outlier Detection
 2. :orange_book: Explaining the TEDA RLS Algorithm
 3. :green_book: Comparing Freematics, Arduino, C++ e Python

# 2. Environment Setup
First, start by cloning the repository:
```bash
git clone https://github.com/pedrohmeiraa/TEDA-Forecasting
```

We also have cloned the `Padasip` repository:
```bash
git clone https://github.com/matousc89/padasip
```
It is possible to install using `pip`:
```bash
!pip3 install padasip
```
- The **Padasip** (*Python Adaptive Signal Processing*) is a library designed to simplify adaptive signal processing tasks within Python (filtering, prediction, reconstruction, classification). More information [here](https://matousc89.github.io/padasip/).  :twisted_rightwards_arrows:

Now, we are going to install the  `WandB`: 💻

```bash
!pip3 install wandb -qU
```
 - If you want to know more about software package **WandB**, click [here](https://wandb.ai/site).  :bar_chart:
 

# 3. References

 [[1]](https://www.mdpi.com/1424-8220/22/10/3838) :books: **Andrade, P.**; Silva, I.; Silva, M.; Flores, T.; Cassiano, J.; Costa, D.G. *A TinyML Soft-Sensor Approach for Low-Cost Detection and Monitoring of Vehicular Emissions*. SENSORS 2022, 22, 3838.  ![GitHub](https://img.shields.io/badge/DOI-10.3390%2Fs22103838-green)

[[2]](https://www.mdpi.com/1424-8220/21/12/4153) :books: Signoretti, G. ; Silva, M. ; **Andrade, P.**; Silva, I. ; Sisinni, E. ; Ferrari, P.; *An Evolving TinyML Compression Algorithm for IoT Environments Based on Data Eccentricity*. SENSORS 2021, v. 21, p. 4153. ![GitHub](https://img.shields.io/badge/DOI-10.3390%2Fs21124153-green)

[[3]](https://dl.acm.org/journal/tecs) :books: **Andrade, P.**; Silva, I.; Silva, M.; Flores, T.; Costa, D.G. Soares, E.; _Online Processing of Vehicular Data on the Edge Through an Unsupervised TinyML Regression Technique_. ACM TECS 2023. ![GitHub](https://img.shields.io/badge/DOI-under%20review-blue)
