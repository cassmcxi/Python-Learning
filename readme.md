# Python Cheatsheet (syntax and meaning)

## Always remember that with programming, theres a bunch of ways to do the same thing !! :)

- 'def' means 'define' for the function

- an 'IF' statement will allow a program to do different things depending on conditions

- 'arguments' are the data that the function can receive when called, example

- def check_win(): <-- the 'argument' goes inside the function paranthesis

- a function doesnt HAVE to return something

- you can CONCATENATE(combine) strings/strings, or strings/variables with the '+' operator

  ```
  
  print("You chose " + player + ", computer chose " + computer)
  
  ```

 ---

- '!=' (not equal)

- '==' (equal)

- '>' (greater than)

- '<' (less than)

- '<=' (less than or equal to)

- '>=' (greater than or equal to)

 ---

## format to 'call' your function, you can use a call to test the function as well an delete it afterwards.

    
    choices = get_choices()
    print(choices)
    

---


    check_win("rock", "paper")
 
 -------------------------------------------------------------

 -------------------------------------------------------------

 - using the random library with list variables

    ```
    options = ["rock", "paper", "scissors"]
    computer_choice = random.options(options)
    ```
 ---

 - dictionary that holds keys and values

    ```
    dict = {"key": "value", "key": "value"}
    ```

- how to select an individual key from the dictionary
  ```
    choices = {"player": "rock", "computer": "paper"}
    p_choice = choices["player"]
  ```
 ---

# "Else' and 'Elif' Statements

### 'Else' and 'If'

- **Example:**
  ```
  
  age = 20
  if age >= 18:
    print("You are an adult.")
  else:
    print("You are a child.")
  
  ```

- It'll print "You are an adult."

### 'Elif'

- Means 'Else If'
- **Example:**

  
  ```
  age = 20

  if age >= 18:
    print("You are an adult.")
  elif age > 12:
    print("You are a teenager.")
  elif age > 1:
    print("You are a child.")
  else:
    print("You are a baby.")
  
  ```

  ### Doesn't check them all, it's finished as soon as the first 'true' is checked, then it moves on


### once you return something, the rest of code does not run
