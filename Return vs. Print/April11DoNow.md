# April 11 Do Now

**Open up the terminal. Paste the following code into the editor:**

```python
import random

def mystery_function(x, y):
    random_number = random.randint(0,2) # What's the range of randoms?
    if random_number > 0: # What's the probability that random_number is greater than 0?
        z = x + y
    else:
        z = x * y
    return z
mystery_function(1, 2)
```
**In comments:**
1. What happens when your run this code? How do you know what the result was?
2. Keeping the function the same, rewrite the code to print out the value that the function returns.