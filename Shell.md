## resources
- [cheatsheet](https://github.com/yisraelU/Studying/blob/master/gnu-coreutils-cheat-sheet.pdf)
- [Great Course](http://teaching.idallen.com/cst8207/19w/)
## commands
- source
- export
## files
- .bashrc: is a shell script specifically made for the **bash** ```/bin/bash``` program as opposed to other shell programs .
it executes everytime the command bash is run
  - the purpose is to set up the environment for the new bash instance so anything such as environment variables can be set on a per instance basis and limited to **bash** only
  - other shell interpreters have their own equivalent of a bashrc
- .profile: is a shell script executed everytime you login to a system
  - 
# Grep
  - short for Global regular expression print
  
# Od
  - Octal Dump 
  - dumps file or stdin in Octal Format
    - what that really means
      - outputs to stdout in Octal format which is the default
      - also displays on the side the memory address
    - neat options
      - change endian via ```--endian=little``` or ```--endian=big```
      - ```-c``` only display printables (this is based off C's isprintable) 
# Umask
  - Permission Mode for File Creation
  
  
  
