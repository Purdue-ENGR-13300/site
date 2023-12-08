---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---
```{include} /macros.md
```

(mod:PY1_ind_task_2)=
# Task 2

## Learning Objectives  

Create and execute simple scripts comprised of basic {program}`Python` concepts;
Output data from a script to the screen in {program}`Python`; Apply this
course's programming standards in development of {program}`Python` scripts;
Modularize and comment code in {program}`Python` for readability and
reusability. 


## Task Instructions

You are part of a team that is taking measurements around Purdue’s campus using
a highly accurate GPS device and a theodolite. Your team will be recording the
latitude and longitude (in degrees) of two locations and the angle of elevation
or depression (in degrees) between the two locations. Your task is to write a
program that will take these five inputs and use them to calculate the slope
distance (in feet) and the change in elevation (in feet) from your instrument to
your target


```{figure} ../figures/geometry.png

A representation of the angles and distances in this problem.
```

The formulas below can be used to convert degrees of latitude or longitude into
miles.  
 
```{math}
:name: eq:PY1:lat

1 \text{ degree of latitude} = 69 \text{ miles}
```

```{math}
:name: eq:PY1:lon

1 \text{ degree of longitude}
= 69.172 \cos(\frac{\text{lat}_1 + \text{lat}_2}{2}) \text{ miles}
```
 
Where $\text{lat}_1$ is the latitude of location 1, $\text{lat}_2$ is the
latitude of location 2, and $69.172$ is the number of miles in $1$ degree of
longitude at the equator.

For this assignment, write a {program}`Python` script to calculate the slope
distance (in feet) and change in elevation (in feet). Display the output using
formatted print statements as shown below. Be sure that any numbers in your
formatted strings only display one digit after the decimal point.


% Automatically generated of Sample Output section.
```{include} ../../_build/intermediate/M05/reference/ind_2_sample_output.md
```