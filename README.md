# first-code
def main():
    pass

if __name__ == '__main__':
    main()
import turtle as t
pen = t.Turtle()
t.bgcolor('#9966cc')
t.delay(8)
pen.color('red')
pen.begin_fill()
pen.left(40)
pen.forward(120)
pen.circle(80, 190)
pen.right(100)
pen.circle(80, 190)
pen.forward(160)
pen.left(90)
pen.forward(50)
pen.setpos(-60, 100)
pen.end_fill()
def txt():
    pen.up()
    pen.setpos(-60, 100)
    pen.color('white')
    pen.write('hello guys', font=("Comic Sans MS", 14))
txt()
pen.end_fill()
t.exitonclick()
