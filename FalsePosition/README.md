# False Position Algorithm 

This algorithm uses false position method to estimate the root of a function 

## Inputs 
1. func
* This is the given function you would like to estimate the root of using false position
2. xl
* This is the left guess or lower guess 
3. xu
* This is the right guess or upper guess of the root
4. es
* This is the stopping error for the given root estimate (defaults to 0.00000001) 
5. maxit
* This is the maximum number of iterations the method can use 

## Outputs 
1. root
* Estimated root of function 
2. fx
* Function evaluated at the root
3. ea
* Relative error associated with root
4. iter
* Number of iterations used 
