# content

`all_data.txt`  refers to dataset of 17 liquids recognition

` train.ipynb`  refers to training and testing program for the data

File:

`milk_detection`  contains transfer learning task (code and datasets) for milk PH detection

`salt_concentration`  contains transfer learning task (code and datasets) for salt concentration detect



## Hardware Requirements

CPU: Intel core i7-9750H

RAM: 16 GB

GPU: GTX 1660ti with 6 GB memory.

## Software Requirements

### OS Requirements

Windows 10

### CUDA

The CUDA version is 11.6 and driver version is 536.23  (by `$nvidia-smi`).

### Python Dependencies

The code uses Python 3.9.13. The necessary packages are follows:

```
conda == 23.3.1
torch == 1.13.1
tqdm == 4.64.1
numpy == 1.21.5
```