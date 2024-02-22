from shapes import Rectangle, Circle
from data_structures import DataProcessor

# Testing the functionality of Rectangle and Circle classes
rectangle = Rectangle(5, 3)
circle = Circle(4)

print("Rectangle area:", rectangle.calculate_area())
print("Rectangle perimeter:", rectangle.calculate_perimeter())

print("Circle area:", circle.calculate_area())
print("Circle perimeter:", circle.calculate_perimeter())

# Testing the functionality of DataProcessor class
DataProcessor.demonstrate_operations()
