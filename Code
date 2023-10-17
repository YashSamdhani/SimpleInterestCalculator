#si calculator
import tkinter as tk
from tkinter import *
import math

#si=(p*r*t)/100
window=tk.Tk()
window.title("my emi calculator")
window.geometry("860x500")

lbp=Label(window, text="enter principal")
p=Entry(window)
lbp.grid(column=0,row=0)
p.grid(column=1,row=0
      )
lbr=Label(window, text="enter rate")
r=Entry(window)
lbr.grid(column=0,row=1)
r.grid(column=1,row=1)
       
lbt=Label(window, text="enter time")
t=Entry(window)
lbt.grid(column=0,row=2)
t.grid(column=1,row=2)

def calculate():
    a=int(p.get())
    b=int(r.get())
    c=int(t.get())
    d=((a*b)*c)/100
    lbres.config(text="simple interest is "+ str(d))
    
k=Button(window, command=calculate,text="find vlaue",bg='green',fg='white')
k.grid(column=1,row=3)

lbres=Label(window, text="here will be the result",font=('Fixedsys',20))
lbres.grid(column=1,row=4)

window.mainloop()
