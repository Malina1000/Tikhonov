# this repository is created for educational purpose

---
the main feauture of the project is that it is very important to the environment and nature in the oceans of siberian plames. 

DId you heat new morgenstern song? Neither did i.

The only reason why i am typing this is because i ve got nothing to do and i like to type fast on this Bluetooth keyboard


```
.model tiny
.286
.code 

org 100h

Start:

    mov ah, 09h     ; DOS Int - print string 
    mov dx, offset HelloWorldString ; dx = &HelloWorldStr
    int 21h         ; system call

    mov ax, 4c00h   ; terminate programm
    int 21h         ; system call

HelloWorldString db "Hello World Yo Yo $"

end     Start
```