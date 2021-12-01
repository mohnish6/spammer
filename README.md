from time import sleep
from pynput.keyboard import key,  contrpller
import thinker as tk
from thinker import 

k=controller()

window=tk.Tk()
window.geometry("300*150")

wel=tk.label(text="welcome to spammer . exe!",width=100,height=1)
wel.pack()

pl = tk.label(text="Your Phrase"width=100,height=1)
pl.pack()

st=tk.Entry(text="your phrase")
st.pack()

dl=tk.label(text="Delay(S)",width=100,height=1)
dl.pack()

d=tk.Entry(text="delay")
d.pack()

def button():
    dela=d.get()
    string.get()
    if dela ==:
       dela=0
    delay = float(dela)
    if dela ==:
       delay=0
       
    sleep(5)
    while(1>0):
         sleep(delay)
        k.type(string)
        k.press(Key.enter)
        k.release(key.enter)
        
b = tk.Button(text="execute in 5 sec",command=button)
b.pack()

window.mainloop()

