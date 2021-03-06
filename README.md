# GrepX
This script process the output of grep  
and you can watch the matching files by number.  

Demo on ubuntu.  
![demo](https://raw.github.com/shengyu7697/GrepX/master/demo.gif)  

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

## Features
- Support many editors:
    + vim
    + sublime
    + visual studio code
    + notepad++

- Support many search command tools:
    + grep
    + ack-grep
    + silversearcher-ag (recommand)

## System Requirement
Windows, Mac OS or Linux  

## License
GrepX is published under the MIT license.  
