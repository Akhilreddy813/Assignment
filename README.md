# Assignment
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

# Example usage
num1 = 10
num2 = 20
biggest_value = find_biggest(num1, num2)
print(f"The biggest value is: {biggest_value}")

