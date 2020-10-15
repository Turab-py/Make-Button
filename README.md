# Make-Button
How to make a Button in python 3
"""
Created on Thu Oct 15 14:01:17 2020

@author: Turab
"""

from tkinter import *

from tkinter import messagebox

top = Tk()
top.geometry("100x100")
def btncall():
   msg = messagebox.showinfo( "Sample Button", "Error 404 Found")

B = Button(top, text = "Button", command = btncall)
B.place(x = 50,y = 50)
top.mainloop()
