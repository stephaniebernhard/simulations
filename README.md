# simulations
Calculate Pi by using python simulations, following the tutorial from:  [junilearning](https://junilearning.com/blog/coding-projects/python-data-science-monte-carlo-simulations/)

## Scenario
Imagine throwing darts on a squared dart board with a circle (radius circle = sidelength of square/2). All darts ending up in the circle are counted as "hits".

## Math
Pi can be approximated by diving the number of "hits" by the number of samples (= #darts thrown) and multiplying with factor 4.

This follows from p(hit) = hits / #darts thrown = circle area / square area = pi*r^2 / 4*r^2.

Therefore: 4 * #darts in circle / #darts thrown = pi

## Approach
1. Simulate one dart by randomly generating x and y coordinates for dart.
2. Create Loop and record data in dataframe.
3. Plot results.