VIM helper Commands

cscope commands:
add  : Add a new database             (Usage: add file|dir [pre-path] [flags])
find : Query for a pattern            (Usage: find c|d|e|f|g|i|s|t name)
       c: Find functions calling this function
       d: Find functions called by this function
       e: Find this egrep pattern
       f: Find this file
       g: Find this definition
       i: Find files #including this file
       s: Find this C symbol
       t: Find this text string
help : Show this message              (Usage: help)
kill : Kill a connection              (Usage: kill #)
reset: Reinit all connections         (Usage: reset)
show : Show connections               (Usage: show)
example : cscope  find e <text to search>
ctrl+r         in cscope screen to reenter the text.
Ctrl+d       to close cscope
ctrl+t    go back in search
ctrl+]   go to definition
ctrl+w t, ctrl+w H/K    change the split screen layout
ctrl+\ s (space s)  show all reference
ctrl+v                      visual select word
 y  to copy
p to paste
dd to delete entire line
gg first line
G last line
gD global declaration
gd local declaration 
 find <location path> -name “*.*”
f9   -> functions in file     f7 -> file order(own shortcuts)

