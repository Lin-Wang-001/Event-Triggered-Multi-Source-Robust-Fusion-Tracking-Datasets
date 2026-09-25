# Supporting Datasets for Event-Triggered Multi-Source Robust Fusion Tracking

The supporting datasets for **Event-Triggered Multi-Source Robust Fusion Tracking** are partially available at: https://pan.baidu.com/s/1LcPfNltqqsp3E9UREaAMag

Due to copyright restrictions, the dataset is partly provided for research purposes only. For further collaboration, please contact the corresponding author.

The released data contain two parts:
﻿
1. **Spatial alignment dataset**
2. **Multi-source fusion tracking dataset**

The spatial alignment dataset provides paired data for evaluating the spatial correspondence between multi-source vessel information and visual observations.
﻿
The multi-source fusion tracking dataset contains camera images, radar images, AIS data and GNSS data for evaluating multi-source vessel tracking method. The radar and visual images in the dataset are as follows: 

<img width="1390" height="501" alt="搜狗高速浏览器截图20260925161953" src="https://github.com/user-attachments/assets/65e160b3-06c6-4107-857a-b04263d47ae1" />



## Dataset Description

### 1. Spatial Alignment Dataset

The spatial alignment dataset is provided in CSV format.

The file `Spatial alignment data.csv` contains paired radar-AIS target positions and corresponding visual target positions used for spatial alignment evaluation.


### 2. Multi-Source Fusion Tracking Dataset

The multi-source fusion tracking dataset contains data collected from multiple information sources, including camera, radar, AIS, and GNSS. 

The dataset includes:

Camera image: visible-camera images stored in .jpg format.
Radar image: radar images stored in .jpg format.
AIS: AIS data stored in text files, including AISData.csv.
GNSS: navigation information stored in GNSSData.csv.

## Dataset Structure

The directory structure of the released supporting datasets is as follows:

```text
Supporting Datasets/
│
├── Spatial alignment dataset/
│   └── Spatial alignment data.csv
│
└── Multi-source fusion tracking dataset/
    │
    ├── Camera image/
    │   ├── xxx.jpg
    │   └── ...
    ├── Radar image/
    │   ├── xxx.jpg
    │   └── ...
    ├── AIS/
    │   └── AISData.csv
    └── GNSS/
        └── GNSSData.csv
    
```


## Usage

The released datasets are provided for academic research purposes.

For questions regarding the dataset or further research collaboration, please contact the authors.
