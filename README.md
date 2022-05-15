# 0x011 C-printf 
This is a collaborative project aim to understand team work by demisifying the concept of printf
# Tasks
The following are the tasks of this project.
### 0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life
* Write a function that produces output according to format.
    - c: converts input into a character
    - s: converts input into a string
    - %: 
    
### 1. Education is when you read the fine print. Experience is what you get if you don't
* Handle the following conversion specifiers:
     - d: converts input into a base 10 integer
     - i: converts input into an integer

### 2.  With a face like mine, I do better in print
* Handle the following custom conversion specifiers:
      - b: the unsigned int argument is converted to binary

### 3. What one has not experienced, one will never understand in print
* Handle the following conversion specifiers:
       - u: converts the input into an unsigned integer
       - o: converts the input into an octal number
       - x: converts the inputs into a hexadecimal number
       - X: converts the input into a hexadecimal number with capital letters
    
### 4. Nothing in fine print is ever good news
* Use a local buffer of 1024 chars in order to call <write> as little as possible.

### 5. My weakness is wearing too much leopard print
* Handle the following custom conversion specifier:
    - S: prints the string.
    - Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)
