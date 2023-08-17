This repository contains a collection of Python and C functions for various tasks. Below is a brief description of each function.

### Python Functions

1. **square_matrix_simple(matrix=[])**:
   - Computes the square value of all integers in a matrix.
   - Returns a new matrix of the same size where each value is the square of the input value.
   - Initial matrix remains unchanged.

2. **search_replace(my_list, search, replace)**:
   - Replaces all occurrences of an element in a list with another element.
   - Returns a new list with replacements.

3. **uniq_add(my_list=[])**:
   - Adds all unique integers in a list only once for each integer.
   - Returns the sum of unique integers.

4. **common_elements(set_1, set_2)**:
   - Returns a set of common elements between two sets.

5. **only_diff_elements(set_1, set_2)**:
   - Returns a set of elements present in only one of the two sets.

6. **number_keys(a_dictionary)**:
   - Returns the number of keys in a dictionary.

7. **print_sorted_dictionary(a_dictionary)**:
   - Prints a dictionary by ordered keys in alphabetical order.

8. **update_dictionary(a_dictionary, key, value)**:
   - Replaces or adds a key-value pair in a dictionary.

9. **simple_delete(a_dictionary, key="")**:
   - Deletes a key from a dictionary if it exists.

10. **multiply_by_2(a_dictionary)**:
    - Returns a new dictionary with all values multiplied by 2.

11. **best_score(a_dictionary)**:
    - Returns the key with the highest integer value in a dictionary.

12. **multiply_list_map(my_list=[], number=0)**:
    - Returns a new list with all values multiplied by a number using map.

13. **roman_to_int(roman_string)**:
    - Converts a Roman numeral to an integer.
    - Returns 0 if the input is not a valid string or None.

14. **weight_average(my_list=[])**:
    - Computes the weighted average of integer tuples (<score>, <weight>).
    - Returns 0 if the list is empty.

15. **square_matrix_map(matrix=[])**:
    - Computes the square value of all integers in a matrix using map.
    - Returns a new matrix with squared values.
    - Initial matrix remains unchanged.

16. **complex_delete(a_dictionary, value)**:
    - Deletes keys with a specific value from a dictionary.

### C Functions

The C functions provided here print basic information about Python lists and bytes objects.

1. **void print_python_list(PyObject *p)**:
   - Prints information about a Python list.

2. **void print_python_bytes(PyObject *p)**:
   - Prints information about Python bytes objects.


