# Logistic Map
The logistic map is derived from a differential equation describing population growth, popularized by Robert May. The dynamical equation is as follows:

x[n+1] = r * x[n] * (1 - x[n])       (1)
Where:

  r can be considered akin to a growth rate.
  x[1] = .5
  x[n+1] is the population next year.
  x[n] is the current population. Population ranges between 0 and 1, signifying the proportion of the maximum population.
  
# Overview

This Python script visualizes the behavior of the logistic map equation (1) for different values of r. It utilizes numpy and matplotlib, two indispensable Python libraries.
