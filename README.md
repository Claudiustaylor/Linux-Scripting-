# Linux-Scripting-
Bash Shell Scripting to interact with User and display pertinent information

#!/bin/bash /n

#Author: Claudius, Corinne Haley, Diyan Nikolov, Sarah Chang, Nohemi
# Name of Script: greetme

#Description: The purpose of this script is to greet the user. /n

# Greet the User
echo “Welcome $USER!” /n

#Tell the user the date
echo “Today’s Date is: `date`”/n

#Display the calendar
cal /n

#Show current host machine

hostname /n

uname -rs /n
ls -a /n
ps -aux | grep root /n
set | grep ‘$HOME’ /n
set | grep ‘$PATH’ /n
set | grep ‘$TERM’ /n
du /n
id /n
echo "Please couldn't you loan me \$50.00?" /n
echo Goodbye /n
date +%T

chmod +x greetme.sh
