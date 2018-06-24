*LI, JIAYUN*  

### Overall Grade: 98/100

### Quality of report: 5/5

* Is the homework submitted (git tag time) before deadline?

	Yes. `2018-06-11 08:26:19 +0800` for tag `hw4`. 
	
* Is the final report in a human readable format html? 

	Yes. `html`.

* Is the report prepared as a dynamic document (Jupyter notebook) for better reproducibility?  

	Yes. `ipynb`.

* Is the report clear (whole sentences, typos, grammar)? Do readers have a clear idea what's going on and how are results produced by just reading the report? 

	Yes. The report is clearly written
 
### Correctness and efficiency of solution: 78/80 

* Q1 (3 / 3 pts) Good job!

* Q2 (5 / 5 pts) Good job!

* Q3, Q4 (4 / 6 pts) 
        No check of the special case `\alpha[i] == 0 && x[i] > 0 ` (-2 pts)
	
* Q5 (5 / 5 pts) Good job!
    
* Q6 (8 / 8 pts) 	
	You may want to check Prof. Zhou's answer

* Q7 (10 / 10 pts)
      There is a mistake in your derivation, the numerator of your last line should be `d - v` not `d - 1` 
      
* Q8 (23 / 23 pts)

	* Implement gradient correctly (2 / 2 pts)

	* Implement Hessian correctly (2 / 2 pts)

	* Using Hessian's structure when computing Newton's direction and do not form the Hessian matrix. (5 / 5 pts)

	* Safeguard by approximating Hessian by a pd matrix. (3 / 3 pts)

	* Safeguard iterates respect the nonnegativity constraint. (3 / 3 pts)

	* Implement line search loop correctly. (4 / 4 pts)
		
        * Better to break from the line search loop for efficiency. No need to do 10 iterations for each line search. (2 / 2 pts) 
        I would recommend you to read the line search in the answer

	* Do not re-calculate Newton direction in each iteration of line search.  (2 / 2 pts)

* Q9, finding the correct MLE for digits 0-9. (10 / 10 pts) Good job!

* Q10, finding the correct LRT p-value. ( 5 / 5 pts)  Good job!
	
* Q11, achieve classification error rate 12.4%. (5 / 5 pts)  Good job!

### Usage of Git: 5/5

* Are branches (`master` and `develop`) correctly set up? Is the hw submission put into the `master` branch?

	Yes.
	
* Are there enough commits? Are commit messages clear? 
	 
       Yes. 
	
* Is the hw4 submission tagged?

	Yes.

* Are the folders (`hw1`, `hw2`, ...) created correctly? 

	Yes.

* Do not put a lot auxillary files into version control.  

	Yes.

### Reproducibility: 2/2

* Are the materials (files and instructions) submitted to the `master` branch sufficient for reproducing all the results?  

	Yes. I was able to run the Jupyter notebook and reproduce all the results.


* If necessary, are there clear instructions, either in report or in a separate file, how to reproduce the results?  

	Not applicable for hw4.

### Julia code style: 8/8

* Rule (4): 4 spaces for indenting. 

* Rule (6): Never place more than 80 characters on a line. 

* Rule (7): Always include a single space after a comma. 
* Rule (8):  Never insert a space before a comma.


* Rule (9): Always insert a single space before and after an operator, except for the `^` and `:` operators, which never have spaces around them. 

* Rule (12): When naming variables or functions, use short lowercase names if possible.

* Rule (13): If a variable or function name is too long to be read in all lowercase, insert underscores at word boundaries.

* Rule (16): When naming constants, use all caps.
