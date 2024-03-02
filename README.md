# Python-import-turtle-Advance-Art-111
Python-import-turtle-Advance-Art-110
from turtle import*
import colorsys
title("Satyam Shorrf")
setup(width=750, height=650)
tracer(5)
bgcolor('black')
pensize(2)
h=0.5

for  i in range(200):
     c = colorsys.hsv_to_rgb(h,1,1)
     h+=0.002
     color(c)
     up()
     forward(i*1)
     down()
     circle(i,40)
     forward(i)
     circle(i,-100)
     hideturtle()
done()
     
