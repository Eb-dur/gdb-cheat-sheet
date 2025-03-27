# gdb-cheat-sheet
```
r                                        # run
q                                        # quit
c                                        # continue
f                                        # run until function finished
bt                                       # stack trace
u                                        # up one in stack 
d                                        # down one in stack 
i <what> <of what>                       # get <what> information of <of what>  
p <variable> | $<register>               # print variable | register
x / <length>? <format>? <Address exp>    # display memory content at given address using given format, o,x,d,u,b,f,c,s
l <> | <line> | <fun> | <start>,<stop>   # list source at specifier, default 10 lines
b  <file>:? + <fun> | <N> | <>           # puts breakpoint at fun | line N | current position, for specific file put
s <> | <N> | <+> | <->                   # step n numbres, minus and plus print after/before current print
n <> | <N> | <+> | <->                   # like s but no count into functions
```
