### What is an Array? 

An array is a type of data structure used to store multiple elements. In this case, it looks like a list in Python, but the main difference is that it must store the same data type. 

```python
array1 = [2, 3, 4, 5, 6, 7]
array2 = ["bmw", "mercedes", "audi"]
```

Let's create an algorithm (step-by-step intructions that solve a specific problem) to find the lowest value integer in an array. Before implementing the solution with code, it is best practice to write it out in in human-readable language to help the problem easier to digest. You can do this in steps (e.g., 1, 2, 3,.. or in pseudo-code (informal programming)). 

1. Create a variable called 'min_num' and set it equal to the first value in an array. 

2. Go through each element in the array. 

3. If the current element in the array is smaller than the first value of the array, update the inital value of the array

4. Tell the audience what the minimum value is. 

    ```python
    array = [18, 23, 1, 34, 56, 92]
    min_num = array[0]

    for num in array: 
        if num < min_num:
            min_num = num 
    print(f"The minimum value in the array is: {min_num}")
    ```

### What is Algorithm Time Complexity? 

This describes how much time an algorithm takes to run relative to the size of its input. 

