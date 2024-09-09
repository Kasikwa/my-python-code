# my-python-code
# Recreate the Python file after reset
file_content = '''
# Python program to take user's name, age, and location, and print a personalized message

name = input("Please enter your name: ")
age = input("Please enter your age: ")
location = input("Please enter your location: ")

# Output the personalized message
print(f"Hello {name}, you are {age} years old and live in {location}.")
'''

# Save the content to a file named "user_input.py"
file_path = "/mnt/data/user_input.py"
with open(file_path, "w") as file:
    file.write(file_content)

file_path
