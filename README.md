# DifficultQuestion

This project contains a simple Python function that transforms a string into an alternating uppercase/lowercase format.  
For example:  
Input: `hello`  
Output: `HeLlO`

## Function Overview

```python
def alternating(string):
    new_string = ""
    for string_index in range(len(string)):
        if string_index % 2 == 0:
            new_string += string[string_index].upper()
        else:
            new_string += string[string_index].lower()
    print(new_string)
