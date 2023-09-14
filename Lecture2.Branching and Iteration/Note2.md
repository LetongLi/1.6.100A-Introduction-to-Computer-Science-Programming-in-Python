# Lecture2.Branching and Iteration

## STRINGS
1. letters, special characters, spaces, digits
2. enclose in quotation marks or single quotes
3. concatenate strings

![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/224cd6b7-eb2d-4dc9-9186-cf10f48649e2)


![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/d2ae3e37-4a82-44db-b66e-f8f1a07bc121)

5. do some operations on a string as defined in Python docs
example: silly = hi + " " + name * 3

![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/8c195220-ed2f-4922-9d06-193faf9a40fc)


## INPUT/OUTPUT: print
Example:
x = 1
print(x)
x_str = str(x)
print("my fav num is", x, ".", "x =", x)
print("my fav num is " + x_str + ". " + "x = " + x_str)
Result:

![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/f3b90c9f-3307-4352-8555-6dc21c3a0131)


## INPUT/OUTPUT: input("")
1. binds that value to a variable
2. input gives you a string so must cast if working with numbers
example:

![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/d7ce2fc4-82fd-4929-abf4-6197674e02ff)


![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/4ba2ecc6-cc38-4b88-9270-426ed64fe0a4)


## COMPARISON OPERATORS ON int, float, string

![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/871f24a9-e81e-496a-b1b1-d4c58cb0104f)


## LOGIC OPERATORS ON bools

![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/9613f1b6-edc2-43d1-b87d-c2aff97729ce)

Example:

![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/37b1c59c-5cb2-4383-83de-52a5ce998e7c)

Results:
False
False

## CONTROL FLOW - BRANCHING

![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/f2a4bd89-0368-4f40-9f5a-c2ac68a60ba5)

1.  <condition> has a value True or False
2.  evaluate expressions in that block if <condition> is True
3.  INDENTATION MATTERS IN PYTHON.

## CONTROL FLOW: while LOOPS

![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/90daae39-bf02-4acf-aad9-f26a385ca41e)

1. <condition> evaluates to a Boolean
2. if <condition> is True, do all the steps inside the while code block
3. check <condition> again
4. repeat until <condition> is False
EXAMPLE:
n = input("You're in the Lost Forest. Go left or right? ")
while n == "right":
n = input("You're in the Lost Forest. Go left or right? ")
print("You got out of the Lost Forest!")

![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/b11394e3-248b-4e38-8c3d-cdbe2c557c83)

## CONTROL FLOW: for LOOPS

![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/da673bac-7336-41bb-bc8e-cade851f2861)

1. each time through the loop, <variable> takes a value
2. first time, <variable> starts at the smallest value
3. next time, <variable> gets the prev value + 1
4. etc.

## for VS while LOOPS

![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/45989fa4-4fbf-4367-899f-a9e0d91b35c9)


## range(start,stop,step)
1. default values are start = 0 and step = 1 and optional
2. loop until value is stop - 1
Example:

![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/e9ef85aa-3041-409e-a020-9634a879972d)

Results:
24
21

## break STATEMENT

![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/e46cd027-8351-4df5-b99b-f0b6e110eeb8)

1. immediately exits whatever loop it is in
2. skips remaining expressions in code block
3. exits only innermost loop!
Example:

![image](https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/41dac77d-ebd7-438e-abbf-83bf0017619f)

Results:
5






