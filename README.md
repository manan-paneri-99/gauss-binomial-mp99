# gauss-binomial-mp99
Python package for calculating and visualizing Gaussian and Binomial distributions.
The package contains methods for performing computations pertaining to Guassian and Binomial distributions.

# Files

## Generaldistribution.py
The parent class, contains <__init__> and <read_data_file> methods.

Import:
```
>>> from gauss_binomial_mp99 import Gaussian, Binomial
>>> gauss = Gaussian()
>>> gauss.read_data_file('sample.txt') 
```

## Gaussiandistribution.py
Gaussian distribution class for calculating and visualizing a Gaussian distribution. Methods to compute Gaussian distribution features include- 

* '<calculate_mean()>': Function to calculate the mean of the data set.
* '<calculate_stdev()>': Function to calculate the standard deviation of the data set.
* '<plot_histogram()>': Function to output a histogram of the instance variable data using matplotlib pyplot library.
* '<pdf(x)>': Probability density function calculator for the gaussian distribution.
* '<plot_histogram_pdf>': Function to plot the normalized histogram of the data and a plot of the probability density function along the same range

**Default**: *mu*= 0 and *sigma*=1
* Form: guass(mu, sigma) *

Example:
```
>>> gauss.calculate_mean()
78.0909090909091
>>> gauss.calculate_stdev()
92.87459776004906
```


Provides the functionality of adding two Gaussian distribution objects.


## Binomialdistribution.py
Binomial distribution class for calculating and visualizing a Binomial distribution. Methods to compute Gaussian distribution features include-

* 'calculate_mean()': Function to calculate the mean from p= probability and n= size
* 'calculate_stdev()': Function to calculate the standard deviation from p and n.
* 'plot_bar()': Function to output a histogram of the instance variable data using matplotlib pyplot library.
* 'pdf(x)': Probability density function calculator for the gaussian distribution. 
* 'plot_bar_pdf': Function to plot the pdf of the binomial distribution.

**Default**: *p*= 0.5 and *n*=20
* Form: bin(p, n) *

```
>>> bin= Binomial(.45, 78)
>>> bin.mean()
xyz
```

Provides the functionality of adding two Binomial distribution objects with the same probablity.


## Installation

```
>>> pip install gauss_binomial_mp99
```
