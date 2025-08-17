# Area of a circle is calculated as follows: area = π x r x r and perimeter = 2 x π x r. Write a function that calculates area_of_circle and perimeter_of_circle.

radius = float(input("Please Enter Radius: "))

def area_of_circle(radius):
    return 3.14 * radius * radius

def perimeter_of_circle(radius):
    return 2 * 3.14 * radius

# Call functions and display results
print("Area of Circle:", area_of_circle(radius))
print("Perimeter of Circle:", perimeter_of_circle(radius))
