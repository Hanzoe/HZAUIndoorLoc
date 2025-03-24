# HZAUIndoorLoc Dataset

**HZAUIndoorLoc** is a self-built indoor localization dataset collected at **Huazhong Agricultural University (HZAU)**. The dataset is designed to facilitate research on indoor positioning, especially focused on cross-environment generalization and environment-invariant feature extraction.

---

## Dataset Overview

The dataset includes Wi-Fi Received Signal Strength Indicator (RSSI) data collected across three different buildings:

- **Building 0** (Symmetrical structure)
- **Building 1** (Symmetrical structure)
- **Building 2** (Independent structure)

Buildings 0 and 1 share symmetrical architectural layouts, which aids the learning of environment-invariant features. Building 2 serves as an independent validation scenario, helping evaluate model generalization to different architectural conditions.

---

## Dataset Specifications

| Attribute                | Description                                     |
|--------------------------|-------------------------------------------------|
| **Buildings**            | Building 0, Building 1, Building 2              |
| **Floors per Building**  | 2 floors per building                           |
| **Coordinate Points**    | 37 coordinate points per floor                  |
| **Wi-Fi Access Points**  | 259 unique WAPs across buildings                |
| **Training Records**     | 10,269 RSSI records                             |
| **Validation Records**   | 2,568 RSSI records                              |

---

## Dataset Structure

The dataset is organized as follows:

```
HZAUIndoorLoc/
├── Training set (10,269 records)
└── Validation set (2,568 records)
```

Each record contains RSSI values corresponding to the Wi-Fi Access Points (WAPs) at predefined coordinate locations within buildings and floors.

---

## Download

Dataset can be downloaded from the following link:

- [**Download HZAUIndoorLoc Dataset**](https://drive.google.com/file/d/1H274CbjTmYt1oA_MR1P3dD_iqdjtpdC-/view?usp=drive_link)


---

## Visualization

![Buildings (0, 1, and 2) used for dataset collection at Huazhong Agricultural University.](f10-2.png)
Buildings (0, 1, and 2) used for dataset collection at Huazhong Agricultural University.

