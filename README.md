# PA-2_ECE2112P

# Objective

- Normalization Problem
create a random 5 x 5 ndarray and store it to variable X. Normalize X. Save your normalized
ndarray as X_normalized.npy

- Divide by 3 Problem
Create a 10X10 array which are the squares of the first 100 positive integers.
Then determine the elements divisible by 3

# PA-2

- For the first problem, it required us to create a 5x5 random array and normalize the array. So first initializing the ndarray with a bunch of random numbers using random.rand to generate the numbers, storing the array to the variable X. Then the next step is to normalize the array by using the formula given in the problem as well as the functions .std() and .mean() and apply it to the equation. Then I printed out the original array and the normalized array in order to compare the two arrays.

- For the second problem, we were tasked to create a program that would output the a 10x10 array that would have the squared values of 1 to 100. Then find the values that would be divisible by 3 in the given array. So first we initialize a set that would have a range of 1 to 100 using the function np.arange(1,101). Then to get the square of the the elements in the array I use **2 to get the square of the elements. Then to reformat the array I used .reshape(10,10) to output the matrix in 10 by 10 format. Once the matrix is established I move on to the next part of the problem which is to find the values that would be divisible by 3. So I used the modulo(%) function and compared it to 3, in which if the expression is true the value would be printed.

# Conclusion

Through this programming assignment I was able to understand the different functions that Numeric Python had to offer. These exercises reinforced essential concepts in array generation, transformation, and logical indexing, which are key skills for effective numerical computing with Python.
