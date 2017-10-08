
## Questions
### Basics
* If I have module `math`, how can get the value of it's attribute `pi` if I only have is as a string:
  ```python
  import math
  attr_name = 'pi'
  ```
  * Answer:
	```python
	value = getattr(math, attr_name)
	```
### OOP
* Write simple class with constructor in python
  ```python
  class SimplePythonClass:
	  def __init__(self, ):
		print("Construct class object.")
  ```
* What is `self` in methods definition?
  `self` is a pointer to the object that is used for calling the method.

<!-- ### Functions -->
### Loops and Comprehensions
* What is the output of the following loop:
  ```python
  for i in range(10):
	  if 3 < i:
		break
	  print i,
  else:
	  print "complete"
  ```
  * Answer:
	Since the `else` statement of loop `for` is get evaluated only when all iterations passed (no `break`s), the output is:
	```python
    0 1 2 3
    ```
* Given a list, print last 3 elements.
  * Answer: `print l[-3:]`

### Modules
* How to list all module's sub elements
  * Answer: `dir(<module name>)`

### Usefull Resources:
https://www.toptal.com/python/interview-questions
