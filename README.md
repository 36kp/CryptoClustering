# CryptoClustering

## About
This program is developed to demonstrate my learnings as a part of AI Boot-camp by University of Pennsylvania, Liberal and Professional Studies. [More Info...](https://bootcamp.sas.upenn.edu/artificial-intelligence/landing/)
<br/><br/>
This program puts the topics discussed in **Unsupervised Machine Learning** into action

## Topics covered in this program
1. **Data ClusteringScaling**:
   - Observing data by identifying means and standard deviations
   - Normalizing data using `StandardScaler` function

2. **Data Clustering**:
   - Identifying optimal number of clusters using **Elbow Curve** method.
   - Using `KMeans()` model to identify and assign clusters.
   - Using **Principal Component Analysis** using `PCA` class.

3. **Understanding PCA**:
   - Comparing cluster identification using PCA and original sets of columns.
   - Comparing variances through all columns and PCA.
   - Understanding features influences on Principal Components.


## How to run this program
Follow instructions below to run this program
> NOTE: Following setup and commands are tested in macOS Sonoma 14.5 only

### Pre-requisites
- **Anaconda** (recommended for environment management)
- **Homebrew** (for installing dependencies)
- Python 3.x
- Pandas library
- NASA API key (`NASA_API_KEY`) set in your environment

Install Anaconda and set up your environment:

```bash
# Install Anaconda using Homebrew
brew install --cask anaconda

# Create a new environment (optional but recommended)
conda create -n dev python=3.10

# Activate the environment
conda activate dev

# Install necessary libraries
conda install pandas
conda install scikit-learn
```
## Usage
- Checkout git repository using git clone
`git clone https://github.com/36kp/CryptoClustering.git`
- Go to the repo home directory
`cd \YOUR_PATH\CryptoClustering`
- Execute the Jupyter Notebook
`jupyter notebook`
- Open `Crypto_Clustering.ipynb` from browser