# Python Practical Exercises

These exercises are designed for beginners and will be completed during the PyLadies Kampala Refugee Python Workshop.

Participants are encouraged to work through the exercises with the support of facilitators and mentors.

---

## Exercise 1: Your First Python Program

Create a Python file called `hello.py`.

Write a program that prints:

```python
print("Hello, PyLadies Kampala!")
print("Welcome to Python!")
```

### Challenge

Change the program so that it also prints your name and the community you come from.

---

## Exercise 2: Variables and Data Types

Create a Python file called `profile.py`.

Create variables for:

* Your name
* Your age
* Your favourite programming language
* Whether you are interested in technology

Example:

```python
name = "Brenda"
age = 25
language = "Python"
interested_in_technology = True
```

Print each variable.

### Challenge

Use an f-string to print a sentence such as:

```text
My name is Brenda, I am 25 years old, and I am learning Python.
```

---

## Exercise 3: User Input

Create a program that asks the user for:

* Their name
* Their age
* Their favourite technology

Print a message using the information they provide.

Example:

```python
name = input("What is your name? ")
age = input("How old are you? ")
technology = input("What technology are you interested in? ")

print(f"My name is {name}. I am {age} years old and I am interested in {technology}.")
```

### Challenge

Ask the user what they hope to learn from the workshop and print their answer.

---

## Exercise 4: Working with Numbers

Create a program that asks the user for two numbers.

Calculate and display:

* Their sum
* Their difference
* Their product
* Their division

Example:

```python
number1 = float(input("Enter the first number: "))
number2 = float(input("Enter the second number: "))

print("Sum:", number1 + number2)
print("Difference:", number1 - number2)
print("Product:", number1 * number2)
print("Division:", number1 / number2)
```

### Challenge

Calculate the average of three numbers entered by the user.

---

## Exercise 5: Lists

Create a list containing five technologies you are interested in.

Example:

```python
technologies = ["Python", "Django", "AI", "Data Science", "Web Development"]
```

Write a program that:

1. Prints the entire list.
2. Prints the first item.
3. Prints the last item.
4. Adds another technology to the list.
5. Removes one technology from the list.

### Challenge

Use a `for` loop to print each technology on a separate line.

---

## Exercise 6: Dictionaries

Create a dictionary containing information about a participant.

Include:

* Name
* Age
* Country
* Favourite technology

Example:

```python
participant = {
    "name": "Amina",
    "age": 22,
    "country": "Uganda",
    "technology": "Python"
}
```

Print each value.

### Challenge

Add another key called `goal` and store what the participant hopes to achieve by learning Python.

---

## Exercise 7: Conditional Statements

Write a program that asks the user for their age.

If they are 18 or older, print:

```text
You can participate in the workshop.
```

Otherwise, print:

```text
You must be 18 or older to participate.
```

Example:

```python
age = int(input("Enter your age: "))

if age >= 18:
    print("You can participate in the workshop.")
else:
    print("You must be 18 or older to participate.")
```

### Challenge

Ask the user how interested they are in Python on a scale from 1 to 5.

Print a different message depending on their answer.

---

## Exercise 8: Loops

Create a list of five names.

Use a `for` loop to print each name.

Example:

```python
names = ["Amina", "John", "Sarah", "Peter", "Grace"]

for name in names:
    print(name)
```

### Challenge

Write a program that prints the numbers from 1 to 10.

Then write another program that prints only the even numbers from 1 to 20.

---

## Exercise 9: Functions

Create a function called `greet()` that accepts a person's name and prints a welcome message.

Example:

```python
def greet(name):
    print(f"Welcome, {name}!")

greet("Amina")
```

### Challenge

Create a function called `calculate_average()` that accepts three numbers and returns their average.

Example:

```python
def calculate_average(a, b, c):
    return (a + b + c) / 3
```

Call the function and print the result.

---

## Exercise 10: Working with Files

Create a text file called `participants.txt`.

Add several participant names to the file.

Write a Python program that opens the file and prints all the names.

Example:

```python
with open("participants.txt", "r") as file:
    participants = file.read()

print(participants)
```

### Challenge

Modify the program so that it adds a new participant to the file.

---

## Exercise 11: Putting It All Together

Create a simple Python program called `participant_profile.py`.

The program should ask the user for:

* Name
* Age
* Country
* Favourite technology
* Learning goal

Store the information in a dictionary and print a simple profile.

Example output:

```text
--- Participant Profile ---

Name: Amina
Age: 22
Country: Uganda
Favourite Technology: Python
Learning Goal: Become a software developer
```

### Challenge

Add a function that displays the participant profile.

---

# Mini Project: Community Technology Directory

For the final exercise, create a small Python program that keeps track of people interested in technology.

Each participant should have:

* Name
* Age
* Technology of interest
* Learning goal

The program should allow the user to:

1. Add a participant.
2. View all participants.
3. Search for a participant by name.
4. Exit the program.

### Example

```text
Community Technology Directory

1. Add participant
2. View participants
3. Search participant
4. Exit

Choose an option:
```

### Challenge

Improve the program by:

* Storing participants in a file.
* Adding error handling for invalid input.
* Allowing users to update participant information.

---

# Introduction to Git and GitHub

After completing the Python exercises, participants will be introduced to Git and GitHub.

### Exercise 12: Create a Git Repository

Create a folder for your Python project.

Open the folder in your terminal and run:

```bash
git init
```

Check the status of the repository:

```bash
git status
```

### Exercise 13: Make Your First Commit

Add your Python files:

```bash
git add .
```

Create your first commit:

```bash
git commit -m "Add Python exercises"
```

### Exercise 14: Push Your Project to GitHub

Create a new repository on GitHub.

Connect your local repository to GitHub and push your project.

The goal is to finish the workshop with a small Python project stored online in your own GitHub repository.

---

# Final Challenge

Choose one of the programs you created during the workshop and improve it.

You can:

* Add new features.
* Improve the user interface in the terminal.
* Add more functions.
* Store information in a file.
* Add error handling.
* Upload the project to GitHub.

The goal is not to create a perfect project. The goal is to practise what you have learned and leave the workshop with something you built yourself.
