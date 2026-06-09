# my_code_lab
active learner 

a=int(input("enter the number:"))
b=int(input("enter the number:"))
print("before swapping:", a, b)

# 1. Save the original value of 'a' into the variable 'temp'
temp = a

# 2. Overwrite 'a' with the value of 'b'
a = b

# 3. Put the saved value from 'temp' into 'b'
b = temp

# 4. Print the actual variables without quotes
print("after swapping:", a, b)
