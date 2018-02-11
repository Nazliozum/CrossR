# CrossR
The `CrossR` package (short for _Cross_-validation in _R_) is a set of functions for implementing cross-validation inside the R environment.  

### Contributors

* Nazli Ozum Kafaee / @nazliozum
* Daniel Raff / @raffrica
* Shun Chi / @ShunChi100

### Summary
Cross-validation is an important procedure for model selection and hyper-parameter optimization. This package aims to provide a standardized pipeline to perform cross-validation for different modeling functions in R. In addition, easy visualization of the cross-validation results is provided.  

__To be added.__

### Functions

Three main functions in `CrossR`:

- `split_data()`: This function partitions data into `k`-fold and returns the partitioned indices. A random shuffling option is provided. `stratification` option for imbalanced representations will also be included if time allows.

- `cross_validation()`: This function performs `k`-fold cross validation using the partitioned data and a selected model. It returns the scores of each validation.

- `plot()`: This function visualizes the cross-validation scores against the tuning hyper-parameters. For many hyper-parameters, it outputs a grid of plots with one plot for one hyper-parameter.


### Similar packages

- `caret`


### License
[MIT License](https://github.com/ShunChi100/CrossR/blob/master/LICENSE)
