# GrepX
This script process the output of grep  
and you can watch the matching files by number.

# How to Use
Place this script to your /usr/local/bin or ~/bin  
```
cp grepx ~/bin
```
execute  
```
$ grepx PATTERN [FLAG]
```
When finishing search, you can press the [1-n/v/s/c/n/q] key,  
1-n: press the number and open the file  
v: open with vim  
s: open with subl  
c: open with visual studio code  
n: open with notepad++  
q: quit  

flag:  
-i :ignore case  
-w: match word  