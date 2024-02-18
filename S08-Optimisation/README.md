[![GitHub watchers](https://img.shields.io/badge/tulip--lab-Statistical--Machine--Learning-brightgreen)](../README.md)
[![GitHub watchers](https://img.shields.io/badge/Module-Convex--Optimization-orange)](README.md)

# Convex Optimization and Learning

Convex optimization is a subfield of optimization that deals with problems where the objective function to be minimized or maximized is convex. In a convex function, a line segment between any two points on the graph of the function lies above or on the graph. This property ensures that any local minimum is also a global minimum, simplifying the optimization process and making it more predictable and efficient. Convex optimization plays a crucial role in various areas, including machine learning, control theory, signal processing, and finance, due to its robustness and the ability to reliably find optimal solutions.

In the context of machine learning, many learning problems can be formulated as convex optimization problems. This formulation is advantageous because convex problems can be solved efficiently and reliably, even at a large scale. For example, least squares for linear regression, logistic regression, and support vector machines are instances of convex optimization problems in machine learning.

The concept of a surrogate function is often used in convex learning problems. A surrogate function acts as a stand-in for the original non-convex objective function, providing a convex approximation that is easier to optimize. This approach is particularly useful in situations where the actual loss function is non-convex and difficult to optimize directly. By optimizing the surrogate function, one can find solutions that are good approximations to the original problem. This method has been instrumental in developing efficient algorithms for complex machine learning tasks where direct optimization is challenging or computationally infeasible.


## :notebook_with_decorative_cover: Lecture Slides Handouts

- [Lecture: Convex Optimisation and Learning](https://github.com/tulip-lab/handouts/blob/main/SML/FLIP16.pdf) 

