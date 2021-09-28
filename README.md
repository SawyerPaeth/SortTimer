# Sort Timer

For this project, imported the **time** and **random** modules.  Also installed the **matplotlib** package and imported it from the **pyplot** module.

Used the **time** module to write a decorator function named sort_timer that times how many seconds it takes the decorated function to run.  Since sort functions don't need to return anything, the decorator's wrapper function return that elapsed time.

To get the current time, called time.perf_counter().  Subtracting the begin time from the end time will gave me the elapsed time in seconds.

Wrote a function called **compare_sorts** that takes the two decorated sort functions as parameters. Randomly generated a list of 1000 numbers and then makse a separate copy of that list...
```
list_2 = list(list_1)
```

Generated random numbers by importing the **random** module.  The function call random.randint(a, b) returns a random integer N such that a <= N <= b. Used a = 1 and b = 10000. 

Installed the **matplotlib** package and imported **pyplot** from it.
```
from matplotlib import pyplot
pyplot.plot([1, 2, 3, 4, 10], [1, 4, 9, 16, 100], 'ro--', linewidth=2)
pyplot.plot([1, 2, 3, 4, 10], [1, 3, 7, 20, 150], 'go--', linewidth=2)
pyplot.show()
```
Each of the calls to the plot function plot a line.  The call to the show function displays the graph.  In the calls to the plot function, the first list is the list of x-coordinates.  The second list is the list of y-coordinates.  The 'ro--' tells it to use red circles connected by a dashed line and 'go--' is the same except green instead of red. 

