import math

# Get the coordinates of the two points from the user
x1 = float(input("Enter x1: "))
y1 = float(input("Enter y1: "))
x2 = float(input("Enter x2: "))
y2 = float(input("Enter y2: "))

# Calculate the distance using the distance formula
distance = math.sqrt(
    math.pow(x2 - x1, 2) + math.pow(y2 - y1, 2))

# Display the distance rounded to two decimal places
print("Distance between the two points:", round(distance, 2))
