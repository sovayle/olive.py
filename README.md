# olive.py
import turtle
import random
import math

wn = turtle.Screen()
wn.title("oliveeee")

puv = turtle.Turtle()
puv.shape('turtle')
puv.color('green')
puv.width(2)

puv.speed(100)

speed = [56,87,76,98,89]

radius = [50,100,150,200,250]

c = speed+radius
print(c)

wn.mainloop()
