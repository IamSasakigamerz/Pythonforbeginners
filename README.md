# Pythonforbeginners
from turtle import *

 import turtle as tur
 ws = tur.Screen()
 

 def drawoval(rad):
     

    for i in range(2):
        tur.circle(rad,90)
        tur.circle(rad//2,90)
 
 value=0
 index=0
 
 tur.speed(100)
 
 for i in range(5):
 
    tur.seth(72*index)
    tur.penup()
    tur.forward(60)
    
    if index >5:
        index=0
    else:
        index+= 1
    tur.pendown()
    drawoval(100)

    value+=5
 
 tur.hideturtle()
