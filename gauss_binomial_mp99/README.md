#gauss-binomial-mp99 package

Summary of the package

The package contains methods for performing computations pertaining to Guassian and Binomial distributions.

#Files

Generaldistribution.py
The parent class, contains __init__ and read_data_file methods.

Gaussiandistribution.py
Inherits from the Generaldistribution class. Methods to compute Gaussian distribution features include calculate_mean(), calculate_stdev(), plot_histogram(), pdf(x) and plot_histogram_pdf.
Provides the functionality of adding two Gaussian distribution objects.

Binomialdistribution.py
Inherits from the Generaldistribution class. Methods to compute Gaussian distribution features include calculate_mean(), calculate_stdev(), plot_bar(), pdf(x) and plot_bar_pdf.
Provides the functionality of adding two Binomial distribution objects with the same probablity.



#Installation

pip install gauss-binomial-mp99