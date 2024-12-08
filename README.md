from turtle import *

# Set the speed of the turtle
speed(100)

# Set the background color
bgcolor('black')

# Draw a pattern
for i in range(290):
    color('yellow')  # Set the pen color
    circle(i)      # Draw a circle with radius i
    left(5)        # Turn the turtle 5 degrees to the left

done()
