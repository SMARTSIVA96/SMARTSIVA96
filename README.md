import turtle as t

# Set up the turtle screen
screen = t.Screen()
screen.bgcolor("white")
screen.title("Apple Logo")

# Create a turtle
apple_logo = t.Turtle()
apple_logo.shape("turtle")
apple_logo.speed(2)
apple_logo.color("black")

# Draw the apple shape
apple_logo.penup()
apple_logo.goto(0, -100)
apple_logo.pendown()
apple_logo.begin_fill()
apple_logo.circle(100)
apple_logo.end_fill()

# Draw the apple leaf
apple_logo.penup()
apple_logo.goto(0, 0)
apple_logo.pendown()
apple_logo.setheading(60)
apple_logo.begin_fill()
apple_logo.circle(100, 120)
apple_logo.setheading(0)
apple_logo.end_fill()

# Close the drawing window when clicked
screen.exitonclick()
￼Enter
