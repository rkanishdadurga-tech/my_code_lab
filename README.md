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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Web Page</title>
</head>
<body>

    <h1>Welcome to My Website</h1>
    <p>This is a paragraph of text on my new web page.</p>
    
    <!-- This is a link -->
    <a href="https://www.w3schools.com" target="_blank">Visit W3Schools</a>

</body>
</html>
#python program 
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

# Calculate the sum
result = num1 + num2
print(f"The sum is: {result}")