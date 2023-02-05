#Fairy Tail logo

import turtle

wn = turtle.Screen()
skk = turtle.Turtle()
wn.bgcolor("Black")
wn.title("Fairy Tail")

skk.color("Orange", "Red")
skk.begin_fill()
skk.speed(10)
skk.pensize(3)
skk.shape("circle")
skk.shapesize(0.01)

skk.right(146)
skk.forward(260)
skk.right(125)
skk.forward(50)
skk.right(208)
skk.forward(125)
skk.right(211)
skk.forward(430)

skk.circle(135, 102)
skk.circle(-135, 40)
skk.right(210)
skk.circle(135, 42)
skk.circle(135, 15)
skk.right(201)
skk.circle(-135, 20)
skk.right(110)
skk.circle(-85, 140)

skk.right(120)
skk.circle(200, 40)
skk.circle(-135, 42)
skk.circle(-135, 5)

skk.right(215)
skk.circle(135, 5)
skk.circle(80, 70)
skk.circle(-200, 30)

skk.right(170)
skk.circle(200, 25)
skk.circle(-135, 42)
skk.circle(-135, 5)

skk.right(215)
skk.circle(135, 5)
skk.circle(80, 70)
skk.circle(-100, 50)

skk.right(160)
skk.circle(180, 45)

skk.left(160)
skk.circle(-130, 50)

skk.right(165)
skk.circle(150, 45)

skk.left(140)
skk.circle(-130, 40)
skk.circle(150, 80)

skk.left(130)
skk.circle(-100, 70)

skk.left(250)
skk.circle(50, 100)
skk.circle(150, 35)
skk.end_fill()

wn.bgpic("background.gif")

turtle.done()
