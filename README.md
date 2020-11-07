# Limad-Github-repository

import turtle
from random import randint


lim = turtle.Turtle()
lim.speed(0)
turtle.Screen().bgcolor('ash')
for i in range(50):
  lim.color('blue')
  lim.circle(i*2)
  lim.lt(10)
lim.pu()
lim.goto(-250,0)
lim.pd()
for i in range(50):
  lim.color('magenta')
  lim.circle(i*1.5)
  lim.lt(8)
lim.pu()
lim.goto(250,0)
lim.pd()
for i in range(80):
  lim.color('green')
  lim.circle(i*0.8)
  lim.lt(9)
