# Convex-Unconstrained-NonLinear-Optimization-Algorithms
To understand what exactly a convex function looks like refer to my notes at the following link :- [https://drive.google.com/drive/folders/1cvmy0PdoP3-5sBN_LfmJ_KA_LYmVlehx?usp=sharing](https://drive.google.com/drive/folders/1fWxVLGycTA-reUqda7Sd9JPHACg7N9Tb?usp=sharing)

Once we have understood what a convex function looks like, we know that convex functions has a single global minima and hence now our aim is to find this global minima.Hence the word optimization comes into picture because we are dealing with a minimization problem.Now we have got hold of terms convex and optimization, unconstrined means there are no conditions imposed on the domain of the convex function and non linear means the convex function is some non linear function and not a linear function.There are several algorithms to solve this problem, a comprehensive list of state of the art algorithms have been listed below for reference but only few has been explained in complete detail.

unconstrained non linear programming problem abbreviated ad NLPP and in other words also called unconstrained non linear optimization problem if the given function is convex  

#   Analytical Methods :- 
These methods are used to calculate exact value of the minima.

    1. Differentiation Method
######           Theory :- [https://drive.google.com/file/d/1-EWtdjTwej9c8NmjftYiCUIe2IlZUqrf/view?usp=sharing](https://drive.google.com/file/d/1lY2H7Uk5gs3iJuIE9unTmvcaOyTXG3SW/view?usp=sharing)

#   Numerical Methods :-
These methods are used to calculate approximate value of the minima.But why would one want to calculate approimate solution if already methods to calculate exact solutions are availabe?? because the computation time complexity to calculate exact solution is very high and hence we need to do a trade off between preciseness of solution and time complexity and we have several algorithms which reduces the time complexity to a great extent for just a negligible amount of variation from exact solution.

##       1. Region Elimination Algorithms
Algorithms which tries to find out the global minima but shortening the potential search space in every iteration fall under this category.These algorithms can only be used to find global minima of 2 variable functions.Algorithms under this category can be further put under following buckets.

###      -------------------------------Direct Region Elimination Algorithms-------------------------------
Algorithms which does not uses derivative of the function to shortening the potential search space in every iteration fall under this category.Following algorithms fall under this category

        1. Dichotomous Search Algorithm
######           Theory :- https://drive.google.com/file/d/1SREhvDrlOAdeI7RXMZfBOsE87bvyoakP/view?usp=sharing
            
        2. Fibonacci Search Algorithm
######            Theory :- https://drive.google.com/file/d/15sw5dKIEf6wkHX_Whx2QTBc07Thpcoa_/view?usp=sharing
            
        3. Golden Section Search Algorithm
######            Theory :- https://drive.google.com/file/d/1pZGXGFnobwGnt77jRcsInF01EhTmkPY8/view?usp=sharing
            
        4. Interval Halving Algorithm
######            Theory :- https://drive.google.com/file/d/1dWBPkZoKFLYnsGOn-_OFXtrOjv3Oqdy2/view?usp=sharing

###      --------------------------------InDirect Region Elimination Algorithms----------------------------
Algorithms which uses derivative of the function to shortening the potential search space in every iteration fall under this category.Following algorithms falls under this category.

        1. Bisection Algorithm
######            Theory :- https://drive.google.com/file/d/1i5omSu5B6t5In6HDT3glHNyuU-Jof68H/view?usp=sharing

##    2. Descent Algorithms

###      --------------------------------InDirect Descent Algorithms----------------------------------------
        1. Gradient Descent (GD) Algorithm / Steepest Gradient Descent Algorithm
######            Theory :-
       
        2. Newton's Algorithm
######            Theory :- https://docs.google.com/document/d/1734cK78lYtNokVa5sSTGIef-uLk7JlZR/edit?usp=sharing&ouid=112473111954452901432&rtpof=true&sd=true

        3. Momentum Based Gradient Descent Algorithm
######            Theory :- https://drive.google.com/file/d/1pyXuYtX6JsnPVT051rjnAwAmuGd1E6wz/view?usp=sharing
            
        4. Nesterov Gradient Descent (NAG) Algorithm:
        5. Adaptive Gradient Descent (ADAGRAD) Algorithm:
        6. ADADELTA Algorithm
        7. Adaptive Moments (ADAM) Algorithm
        8. Conjugate Descent Algorithm
        9. Quasi Newton Algorithm
        10.Broyden Fletcher Goldfarb Shanno (BFGS) Algorithm

###      ---------------------------------Direct Descent Algorithms-----------------------------------------
        1. Newton Raphson Algorithm
######            Theory:- 

        2. Coordinate Descent Algorithm
######            Theory :- https://drive.google.com/file/d/12otwYQnuJ_14ZdtKR4VtzTiyBmeqpHFr/view?usp=sharing

        3. Hooke and Jeeves Algorithm
######            Theory :- https://drive.google.com/file/d/1YDq3BKvq7EICZdJX4r8lwEAzNiU54Xtw/view?usp=sharing

##    3. Evolutionary Algorithms

      1. Genetic Algorithm (GA)
Best way to learn and understand this algorithm is via application and hence we will understand this algorithm via an application of selecting best feature subset for a classification problem (i.e. emotion detection).

###### Theory :- https://drive.google.com/file/d/1nlQ4ngSahKfk0APkN1ji16acPHaGiD8Y/view?usp=sharing
###### Code :- https://github.com/khetansarvesh/Emotion_Detection
      2. Particle Swarm Optimization (PSO) Algorithm
      3. Ant Colony Optimization (ACO) Algorithm
      4. Differential Evolution (DE) Algorithm
      5. Memetic Algorithm (MA)  
