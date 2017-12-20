# python-data-science

null/undefined is None

Python Data Structures

## List
x = [1,2,3]

## Tuple

Tuples are immutable lists

x = (1,2,3)

## Tuples and lists

List of lists/ Tuples of tuples
tuples = [x, y]

## String
(age, income) = "32,12000".split(",")

## Dictionary

obj = {}
obj["name"] = "Nithin"

## Functions

def someFunction(param):
  return param * param

## Callbacks
def someFunction(callback, a):
  return callback(a)

## Lambdas(Anonymous Functions)
someFunction(lambda x: x * x, 3)

## Boolean
True False

else if -> elif

## For loop
  for x in range(10)
  
  prints 0 - 10
  

is ==

## Numpy
import numpy as np

np.random(number, standardDeviation, datapoints)

np.mean(array)

np.median(array)

np.append(array, anotherArray)

np.random(10, high=90, size=500)
## pyplot

import matplotlib.pyplot as plt

plt.hist(array, )

## scipy

from scipy import stats
stats.mode(array)
