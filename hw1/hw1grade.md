*Li, Jiayun*

### Overall Grade: 91/100

### Quality of report: 10/10

* Is the homework submitted (git tag time) before deadline?

	Yes. `2018-04-27 16:12:59 -0700`.

* Is the final report in a human readable format html?  

	Yes. `html`.

* Is the report prepared as a dynamic document (Jupyter notebook) for better reproducibility?

	Yes. `ipynb`.

* Is the report clear (whole sentences, typos, grammar)? Do readers have a clear idea what's going on and how are results produced by just reading the report?

	Yes.
 
### Correctness and efficiency of solution: 44/50 

* Q1

* Q2 (-0 pts) 

Good job!
	
* Q3 (-4 pts)
 
    (3): The reason that compiler is able to unroll the loop for integer input is because fixed point numbers (integers) **obey the usual associative and distributive laws**. The fundamental reason that the compiler does not unroll the loop as with integer input is because floating-point number arithmetic does **not** necessarily follow the associative and distributive laws, as you learnt in Q2. (-2 pts)
 
    (4): The `@fastmath` marco tells compiler to ignore the fact that floating-point number arithmetic does not necessarily follow the associative and distributive laws. Therefore compiler is able to optimize the loop like with the integer arithmetic. (-2 pts)


* Q4 (-0 pts) 

    (1), (2): Apparently the expression `y = x^7 - 7x^6 + 21x^5 - 35x^4 + 35x^3 - 21x^2 + 7x -1` is mathematically equivalent to `y = (x - 1)^7`. However the first expression involves sum of terms of alternating signs and incurs **catastrophic cancellation** (substract two nearly equal numbers) (-4 pts)

* Q5 (-2 pts)
	 
     - In your function `h` (loop), the looping order is not optimal for Julia. Remember that Julia stores matrix in column-major order. So `ji` looping is better.  (-2 pts)
     - Your `h_comprehension` is wrong. Try `h_comprehension(n) = [1 / (i + j - 1) for i in 1:n, j in 1:n]` (-2 pts)

* Q6 (-0 pts) 

Good job!


### Usage of Git: 10/10

* Are branches (`master` and `develop`) correctly set up? Is the hw submission put into the `master` branch?

	Yes.

* Are there enough commits? Are commit messages clear? 

	Yes 

* Is the hw1 submission tagged?

	Yes.

* Are the folders (`hw1`, `hw2`, ...) created correctly?

	Yes.	

* Do not put a lot auxillary files into version control.  

	Yes.
		

### Reproducibility: 10/10

* Are the materials (files and instructions) submitted to the `master` branch sufficient for reproducing all the results? 

    Yes

* If necessary, are there clear instructions, either in report or in a separate file, how to reproduce the results?  

	Not applicable for hw1.


### Julia code style: 17/20

* Rule (4): 4 spaces for indenting.

* Rule (6): Never place more than 80 characters on a line.

* Rule (7): Always include a single space after a comma. (-1 pts)

    -code chunk 14, line 6
    
* Rule (8):  Never insert a space before a comma.

* Rule (9): Always insert a single space before and after an operator, except for the `^` and `:` operators, which never have spaces around them. (-2 pts)

    -code chunk 4, line 3
    -code chunk 15, line 4

* Rule (12): When naming variables or functions, use short lowercase names if possible.

* Rule (13): If a variable or function name is too long to be read in all lowercase, insert underscores at word boundaries.

* Rule (16): When naming constants, use all caps.
