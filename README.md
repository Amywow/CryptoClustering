# Challenge CryptoClustering
## Table of Contents
- [Challenge Overview](#challenge-overview)
- [File Layout](#file-layout)
- [Usage](#usage)
- [Contributing](#contributing)
- [Code Contributors](#code-contributors)

## Project Overview
This challenge predict if cryptocurrencies are affected by 24-hour or 7-day price changes by elbow curve and cluster plot.

## - File Layout
All links in this section take you directly to the file in the repository.

- [Crypto_Clustering.ipynb.ipynb](Crypto_Clustering.ipynb)
    - The file contains code that converts the data from csv files into Pandas DataFrames.The data is normalised by scikit-learn. The k value is found by elbow curve. A cluster plot is created by Kmeans. A PCA model is created and fitted, and a elbow curve and a cluster plot are created based on pca data. At the end, elbow curve plots and cluster plots from scaled data and PCA data are compared. 

### [Resources](Resources)
- [ev_evc_prototype.csv](Resources/ev_evc_prototype.csv)
    - The dataset contains the price change (In percentage) and name of cryptocurrency. There are 41 rows and 9 columns of data.
    - 
## Usage
1. Open Jupyter Lab
2. Import Crpto_Clustering.ipynb
3. Run the kernel
4. Check kernel outputs 

## Contributing
Contributions to the CrptoClustering challenge are welcome! If you'd like to contribute, follow these steps:

1. Fork the repository.

2. Make your changes or improvements 

3. Submit a pull request to the main repository.

Please ensure that your code follows the Python coding conventions and is well-documented.

## Code Contributors
The Jupyter notebook is created and  maintained by Chang Yu.

