# Convex-Unconstrained-NonLinear-Optimization-Algorithms
To understand what exactly a convex function looks like refer to my notes at the following link :- https://drive.google.com/drive/folders/1cvmy0PdoP3-5sBN_LfmJ_KA_LYmVlehx?usp=sharing

Once we have understood what a convex function looks like, we know that convex functions has a single global minima and hence now our aim is to find this global minima.Hence the word optimization comes into picture because we are dealing with a minimization problem.Now we have got hold of terms convex and optimization, unconstrined means there are no conditions imposed on the domain of the convex function and non linear means the convex function is some non linear function and not a linear function.There are several algorithms to solve this problem, a comprehensive list of state of the art algorithms have been listed below for reference but only few has been explained in complete detail.

unconstrained non linear programming problem abbreviated ad NLPP and in other words also called unconstrained non linear optimization problem if the given function is convex  

#   Analytical Methods :- 
These methods are used to calculate exact value of the minima.

    1. Differentiation Method
#   Numerical Methods :-
These methods are used to calculate approximate value of the minima.But why would one want to calculate approimate solution if already methods to calculate exact solutions are availabe?? because the computation time complexity to calculate exact solution is very high and hence we need to do a trade off between preciseness of solution and time complexity and we have several algorithms which reduces the time complexity to a great extent for just a negligible amount of variation from exact solution.

##       1. Region Elimination Algorithms
Algorithms which tries to find out the global minima but shortening the potential search space in every iteration fall under this category.These algorithms can only be used to find global minima of 2 variable functions.Algorithms under this category can be further put under following buckets.

###      ------------------------------------------Direct Region Elimination Algorithms------------------------------------------
Algorithms which does not uses derivative of the function to shortening the potential search space in every iteration fall under this category.Following algorithms fall under this category

        1. Dichotomous Search Algorithm
######           Theory :- https://drive.google.com/file/d/1UuPNCrBXDRz7uVmc5nu1KhcbwCKYLVdQ/view?usp=sharing
######           Code: https://colab.research.google.com/drive/12Y7ERCyYNIZ4vWfrIFmIO0PCU4mQno_n?usp=sharing
            
        2. Fibonacci Search Algorithm
######            Theory: https://drive.google.com/file/d/1ktiZ821HqllmErNE8GGIzGUICW87w8y7/view?usp=sharing
######            Code: https://colab.research.google.com/drive/1eQghTkrbDcnb8hjnxFlErCOxOsERlvXr?usp=sharing
            
        3. Golden Section Search Algorithm
######            Theory: https://drive.google.com/file/d/1MNLNWqbPP_GREX_VzhecWMaeq3bgJ4Kd/view?usp=sharing
######            Code: https://colab.research.google.com/drive/1ALxO0jylw4QISjqLRHAQhdzdl-R7S1JP?usp=sharing
            
        4. Interval Halving Algorithm
######            Theory: https://drive.google.com/file/d/1YhEd8x6Q-FCzntoh8HbPD7tA8NjzyESo/view?usp=sharing
######            Code: https://colab.research.google.com/drive/1mdeBSy1GcJS9Df6eEma6Q5oXzmuEcKt4?usp=sharing

###      ----------------------------------------InDirect Region Elimination Algorithms-----------------------------------------
Algorithms which uses derivative of the function to shortening the potential search space in every iteration fall under this category.Following algorithms falls under this category.

        1. Bisection Algorithm
######            Theory: https://drive.google.com/file/d/1WqyteEQ9YOlAjRCrcrcg3P4m3TGq8B73/view?usp=sharing
######            Code: https://colab.research.google.com/drive/11pf1iqDGG-6U3aDPylxftSXYdd345kWl?usp=sharing

##    2. Descent Algorithms

###      a. Indirect Descent Algorithms
        1. Gradient Descent (GD) Algorithm / Steepest Gradient Descent Algorithm
######            Theory :
######            Code :
            
        2. Momentum Based Gradient Descent Algorithm
######            Theory :
######            Code :
            
        3. Nesterov Gradient Descent (NAG) Algorithm:
        4. Adaptive Gradient Descent (ADAGRAD) Algorithm:
        5. ADADELTA Algorithm
        6. Adaptive Moments (ADAM) Algorithm

###      b. Direct Descent Algorithms
        1. Newton Raphson Algorithm
######            Theory:
######            Code:

        2. Coordinate Descent Algorithm
######            Theory: https://drive.google.com/file/d/1oD_UmiUzcD40PCzA8WcPNPz4vrCAT7KF/view?usp=sharing
######            Code: https://colab.research.google.com/drive/1BjfaxxWBI-B1c9tAEngOinnnqNxopZsR?usp=sharing

        3. Hooke and Jeeves Algorithm
######            Theory: https://drive.google.com/file/d/140BhvvCtg6fRtnqzsRjJBAE3_ImpJzHJ/view?usp=sharing
######            Code: https://colab.research.google.com/drive/1Dqg5jvbn_4ppmtEpNdi6VR09NnrDnoT3?usp=sharing     

##    3. Evolutionary Algorithms

      1. Genetic Algorithm (GA)
###### Theory :
###### Code :
      2. Particle Swarm Optimization (PSO) Algorithm
      3. Ant Colony Optimization (ACO) Algorithm
      4. Differential Evolution (DE) Algorithm
      5. Memetic Algorithm (MA)  
