

I honestly don't know which sources i'm going to use
I want to make sure to be using the 100 days python course i downloaded before


- [ ] Watch and finish this course https://www.youtube.com/watch?v=XKHEtdqhLK8&t=636s
- [ ] Watch CS50 to learn about CS fundamentals 
- [ ] Finish Pixigami Playlist https://www.youtube.com/watch?v=cqO2S2KdQc8&list=PLZJBfja3V3Rsbiz84Z63IXnTQZH_Rnfuo&index=
- [ ] MIT CS python good to learn about memory > https://www.youtube.com/watch?v=xAcTmDO6NTI

### STUDY NOTES
- operators could be added to variables in the form of (x+= 1 ) to avoid replacing the same variable with another assignment
	`x = 1`
	`x += 1  >>> x = 2`
	`x = 1` 
	`x + 1  >>>> x = 1`

-  print(f"whatever string here is better than {x}")
	Format strings are used to avoid weird print strings while adding 
	variables to it 
- Equality operators ( == ), (!=) answers with boolean. `True, False`
- Evaluation is interpreting an expression and printing its value
	`result = x  == y` 
	`print(result) >>> # True` 

- Logical Operators are `and, or, not`> They compare a boolean and return a boolean 
	If `x and y =  True` >> that means both x and y have ti be `true`
	If either of them was `False` >> expression is `False` // Better use `x or y` instead``
	`not x` if x is true > `not x` becomes false and vice versa 

- Indentation is using 4 spaces to fulfill an If statement
	`if life_is_good:
		`print('alhamdullah') >> with indentation 
	`print('alhamdullah') >>> without indentation 

- The following is a 3 level `if`,`else,elif` statement
	`customer_age = 30  
	`is_student = False  
	`if customer_age < 18:  
	  ``  print("Entry is Free")  
	`elif customer_age > 65 or is_student:  
	  ``  print("Entry is 50% off!")  
	`else:  
	  ``  print("Entry is full price")

- Lists
	`fruits = [x, y, z]`
	`print(fruits[0]` # x
	2d lists are nested lists that are used for data in 2 dimensions like a chess board such as `grid = [[0,1,0], [0,0,1]]
	`print(grid[0][1])` using the first bracket gives the first element, 2nd bracket gives specific item in the first element.  
	`fruits = []` sometimes we create an empty list and then append the list with adding items with `fruits.append()` & to remove items `fruits.remove()` but be sure as it only removes the first occurrence of a recurring item. We can use `furits.pop()` which removes the last item of the list or a specific indexed item. 
	 To know the size of a list we use `print(len(fruits))`

- 