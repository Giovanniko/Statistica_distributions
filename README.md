# Statistica_distributions package

Calculates mean, standard deviation, and variance of gaussian and binomial data. Binomial distribution skew can also be calculated.
The mean of two Gaussian distributions are calculated using the + operator.
Uses principales of OOP and magic methods to read in and initialize data.
Graphs a bar chart of both types of data. 

# Files

Gaussiandistribution.py

Generaldistribution.py

Binomialdistribution.py

`__init__.py`

setup.py

license.txt

README.MD

# Installation

Open a new terminal or command line in the folder location of the package

## Type:

```
pip install statistica-distributions
```

Once installed, run a command depending on the data type to analyze:
```
from statistica_distributions import Gaussian

from statistica_distributions import Binomial
```

## Command examples:

Create object:

```
object_name = Gaussian(mean, stdev)
```
or

```
object_name = Binomial(prob, n-trials)
```

Evaluate object:

```
gaussian_object.mean
```

```
gaussian_objecgt.stdev
```

```
binomial_object.variance
```

```
binomial_object.skew
```


## Example:

```
>>> from statistica_distributions import Gaussian
>>> gaussian_one = Gaussian(5,30)
>>> gaussian_one.mean
5
>>>gaussian_two = Gaussian(7,25) 
>>>gaussian_one + gaussian_two
mean 12, standard deviation 39.05124837953327
```



