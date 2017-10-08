
## Questions
### OOP
* Write simple class with constructor in python
  ```python
  class SimplePythonClass:
	  def __init__(self, ):
		print("Construct class object.")
  ```
* What is `self` in methods definition?
  `self` is a pointer to the object that is used for calling the method.
  
### Functions

### Loops
* What is the output of the following loop:
  ```
  for i in range(10):
	  if 3 < i:
		break
	  print i
  else:
	  print "complete"
  ```
  Answer:
  Since the `else` statement of loop `for` is get evaluated only when all iterations passed (no `break`s), the output is:
  ```
  0
  1
  2
  3
  ```
  
