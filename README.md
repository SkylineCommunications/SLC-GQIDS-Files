# SLC-AS-GQI-Files

## About

SLC-AS-GQI-Files is a generic GQI data source that retrieves a file list from a DataMiner Agent.

## Input & Output

### Input

The data source has the following input arguments:

- Path (default: `C:\Skyline DataMiner\Documents\DMA_COMMON_DOCUMENTS`)
- Search Pattern (default: `*.*`)
- Recursive (default: `False`)

### Output

The data source returns a file list with the following fields:

- File Name
- Path
- Created
- Last Modified
- Size
- Type
- Read Only

## Screenshots

### Data source UI

![image](https://user-images.githubusercontent.com/110403333/218708219-fa58076d-bdc7-4a22-9df5-1d492a8274e1.png)

### Result

![image](https://user-images.githubusercontent.com/110403333/218708735-027ceb48-8d5f-4ac0-bfff-f3c7afb79e21.png)
