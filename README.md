# Assignment 1
#write a program on findout biggest value among 2 numbers
def find_biggest(num1, num2):
    """
    Finds the biggest value among 2 numbers.

    Args:
        num1: The first number.
        num2: The second number.

    Returns:
        The biggest of the 2 numbers.
    """

    if num1 > num2:
        return num1
    elif num1 < num2:
        return num2
    else:
        return "The numbers are equal."

num1 = 10
num2 = 20
biggest_value = find_biggest(num1, num2)
print(f"The biggest value is: {biggest_value}")


# write a program to findout the given number is even or odd
def is_even(number):
  return number % 2 == 0
number = 12
if is_even(number):
  print(f"{number} is even.")
else:
  print(f"{number} is odd.")


# write program on to accept student number, name and marks in 3 subjects calculate total and average and give specified grade.
def calculate_result(student_number, student_name, marks):
    total_marks = sum(marks)
    average = total_marks / len(marks)

    # Determine result based on conditions
    result = ""
    if average >= 75:
        result = "Distinction"
    elif average >= 60:
        result = "First Class"
    elif average >= 50:
        result = "Second Class"
    elif average >= 35:
        result = "Third Class"
    else:
        result = "Fail"

    # Print student results
    print(f"Student Number: {student_number}")
    print(f"Student Name: {student_name}")
    print(f"Marks: {marks}")
    print(f"Total Marks: {total_marks}")
    print(f"Average: {average:.2f}")
    print(f"Result: {result}")

student_number = 12345
student_name = "Alice"
marks = [80, 65, 78]
calculate_result(student_number, student_name, marks)


  



