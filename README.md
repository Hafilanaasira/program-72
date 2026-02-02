# program-72
import turtle

# Create turtle object
x = turtle.Turtle()
x.speed(0)  # fastest drawing

# Function to draw a square rotated by a given angle
def square(angle):
    for _ in range(4):
        x.forward(100)
        x.right(angle)
    x.right(10)  # rotate for the next square

# Draw 36 squares in a circular pattern
for i in range(36):
    square(90)

# Finish drawing
turtle.done()
outpput
     * * * * *
   *         *
  *           *
 *             *
*               *
*               *
 *             *
  *           *
   *         *
     * * * * *
