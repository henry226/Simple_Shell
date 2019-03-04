# Shell Project

### 1. Internal commant “help” to see what the internal commands are.  
```sh
ML>> help
Meng-Tse Li's Shell
The folloowing are built in:
cd
exit
help
users
history
!!
!n
```  
### 2. External command “ls” and internal command “cd” to see and change my file directory.
```sh
ML>> ls
Makefile myshell myshell.c
ML>> cd ../
ML>> ls
Desktop Documents Downloads examples.desktop hello hello.c hi Makefile Music myshell myshell.c Pictures Public
shell shell.c Templates text text.c Video
```  
### 3. “users” command to see the user.
```sh
ML>> users
The user is: henry
ML>>
```  
### 4. “history” command to see all the commands I did in the past.
```sh
ML>> history
ls
cd ../
ls
help
clear
users
history 
clear
history
clear
history
ML>>
```
### 5. “!!” command which executes the last command I had executed. In this case, the last command I did was “history”.
```sh
ML>> history
ls
cd ../
ls
help
clear
users
history 
clear
history
clear
history
ML>> !!
ls
cd ../
ls
help
clear
users
history 
clear
history
clear
history
ML>>
```
### 6. “n5” to execute the fifth command I did in the past. In this case is “help” command.
```sh
ML>> !5
Meng-Tse Li's Shell
THe follwoing are built in:
cd
exit
help
users
history
!!
!n
ML>>
```
### 7. “!100” command, it will give user error message if user did not use 100 commands in the past yet. In addition, random “hsa” command will gave user command not found message because it doesn’t belong to any commands.
```sh
ML>> !100
Error, mot in the hisotry list.
ML>> hsa
has: command not found.
```