# KBadrat
import turtle
while True:
    i = raw_input()
    if i == "exit":
        break
    if i == "fd":
        turtle.fd(1)
    if i == "bk": 
        turtle.bk(1)
    if i == "lt":
        turtle.lt(90)
    if i == "rt":
        turtle.rt(90)
    if i == "pu":
        turtle.pu()
    if i == "pd":
        turtle.pd()
