## Session #1 Homework

## Concepts used 

-> Basic NumPy and Pandas functions </br>
### Question 1

What's the version of NumPy that you installed? 

### Question 2

What's the version of Pandas? 


### Getting the data 
Now read it with Pandas
### Question 3

What's the average price of BMW cars in the dataset?


### Question 4

Select a subset of cars after year 2015 (inclusive, i.e. 2015 and after). How many of them have missing values for Engine HP?


### Question 5

* Calculate the average "Engine HP" in the dataset. 
* Fill the missing values in "Engine HP" with the mean value from the previous step. 
* Now, calcualte the average of "Engine HP" again.


Round both means before answering this questions. You can use the `round` function for that.
### Question 6

* Select all the "Rolls-Royce" cars from the dataset.
* Select only columns "Engine HP", "Engine Cylinders", "highway MPG".
* Now drop all duplicated rows using `drop_duplicates` method (you should get a dataframe with 7 rows).
* Get the underlying NumPy array. Let's call it `X`.
* Compute matrix-matrix multiplication between the transpose of `X` and `X`. Let's call the result `XTX`.
* Invert `XTX`.
* What's the sum of all the elements of the result?

### Question 7 

* Create an array `y` with values `[1000, 1100, 900, 1200, 1000, 850, 1300]`.
* Multiply the inverse of `XTX` with the transpose of `X`, and then multiply the result by `y`. Call the result `w`.
* What's the value of the first element of `w`?.


