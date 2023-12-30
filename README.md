# I-love-you-

import turtle
def draw_heart():
    turtle.fillcolor("white")
    turtle.begin_fill()
    turtle.left(50)
    turtle.forward(133)
    turtle.circle(50, 200)
    turtle.right(140)
    turtle.circle(50, 200)
    turtle.forward(133)
    turtle.end_fill()

def write_love_phrase():
    turtle.penup()
    turtle.goto(0, -50)
    turtle.color("white")
    turtle.write("I love you", align="center", font=("Arial", 16, "normal"))

def main():
    turtle.speed(2)
    turtle.bgcolor("black")
    turtle.color("white")
    draw_heart()
    write_love_phrase()
    turtle.hideturtle()
    turtle.done()
if __name__ == "__main__":
    main()
