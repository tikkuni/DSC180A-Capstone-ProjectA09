# Estimation of Connectivity in the Human Brain Using Functional MRI data: Statistical Approach

_This is our DSC 180A Capstone Project (Section A09):_ Using correlation analysis to detect connected networks in the brain is no new feat in neuroscience. 

Our project carefully considers which statistical methods to employ in estimating the connectivity in a resting-state brain through fMRI data. First, using facts of standard errors and correlations gives confidence of what errors we are expecting to see in simulation versus actual fMRI data collected in resting state scans. Then, extracting valuable data from pairwise correlated matrices of time series data. Then, utilizing benefits of factorization methods such as PCA and ICA to analyze the graphs and find the most interesting components.

## Project Structure

```
|____PCA_ICA_transform.ipynb
|____.DS_Store
|____requirements.txt
|____nilearn_cache
|____correlation_and_standard_errors.ipynb
```

## Accessing and Retriving Data

 * Time series data is generated from the [Nilearn package](https://nilearn.github.io/stable/index.html) and all other necessary data is generated through code.

## Running the Project

 * To install the dependencies, run the following command from the root directory of the project: `pip install -r requirements.txt`

## Reference

[Hand Book of Functional MRI Data Analysis](https://www.cs.mtsu.edu/~xyang/fMRIHandBook.pdf)
