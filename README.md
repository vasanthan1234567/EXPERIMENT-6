# EXPERIMENT-6
### Name : VASANTHAN.N
### Reg no. : 212224240180
## AIM:
To write a Python program for checking Palindrome and to write test cases for ir. 

## ALGORITHM

1. Start
2. Get an input from the user by prompting
3. Run a loop form 0 to len/2.
4. Check if the characters are the same both from the start and the end till len/2.
5. If it is, return the result that it is a palindrome.
6. Else, return that it is not a palindrome.
7. Stop. 

## PROGRAM
```python
def Palindrome(string):
    for i in range(0, int(len(string) / 2)):
        if string[i] != string[len(string) - i - 1]:  
            return False
    return True
s = input("Enter a string: ") 
c = 1
for i in s:
    if not i.isalpha():
        c = 0
        break  
if c == 0:
    print("Enter a valid string")
    print("Test Case:Fail")
else:
    answer = Palindrome(s)
    if answer:
        print("The given string is a palindrome")
        print("Test Case:Pass")
    else:
        print("The given string is not a palindrome")
        print("Test Case:Pass") 
```
## OUTPUT

<img width="382" height="151" alt="image" src="https://github.com/user-attachments/assets/1a18ac52-95cf-4ffd-a700-64a759e8cc4f" />

<img width="389" height="145" alt="image" src="https://github.com/user-attachments/assets/6bdc717e-210c-46ab-b99e-5baffbfa425a" />

<img width="392" height="158" alt="image" src="https://github.com/user-attachments/assets/dca319c2-8c5f-4853-b789-0657e5be9212" />

<img width="420" height="134" alt="Screenshot 2025-08-29 102818" src="https://github.com/user-attachments/assets/5fba9b89-2dbf-4639-a584-95a79700029e" />

<img width="365" height="153" alt="Screenshot 2025-08-29 102858" src="https://github.com/user-attachments/assets/46687aa5-297d-4185-b4a6-6192e55b8dfc" />

## RESULT
Thus, a program to check palindrome has been written and test cases have been written and verified successfully.
