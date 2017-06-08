# Write a Python program to count the number of rows and columns of a DataFrame.

Define a funtion that takes a dictionary as a parameter and converts it into a DataFrame.
The function should return the number of rows and columns of the DataFrame in a tuple in the form (rows, columns).

_Example:_


**Input:**


    exam_data = {'name': ['Anastasia', 'Dima', 'Katherine', 'James', 'Emily', 'Michael', 'Matthew', 'Laura', 'Kevin', 'Jonas'],
    'score': [12.5, 9, 16.5, np.nan, 9, 20, 14.5, np.nan, 8, 19],
    'attempts': [1, 3, 2, 3, 2, 3, 1, 1, 2, 1],
    'qualify': ['yes', 'no', 'yes', 'no', 'no', 'yes', 'yes', 'no', 'no', 'yes']}


**Output:**



    (10, 4)
