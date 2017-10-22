# SVM FROM SCRATCH


I have implemented a SVM by pinimizing the following objective function using gradient descent. This equation is quadratic, so the space is convex and any local minimum is global.

![](https://github.com/beaupletga/SVM_from_scratch/blob/master/lagrangien.png)

Once the error is almost 0, we compute b by using the equations of the supports vectors.


1. The error is :

![](https://github.com/beaupletga/SVM_from_scratch/blob/master/result_error.png)

2. The separation :

![](https://github.com/beaupletga/SVM_from_scratch/blob/master/result_hyperplane.png)


## TODO :

Using the kernel trick to separate non linearly separable distribution.
