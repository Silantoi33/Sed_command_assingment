# Sed_command_assingment
## Assignment

Use the sed command in a for loop to remove the following lines in the file diary.html
 - 1 to 221
 - 265 to 330
Save the output in a file called diary_no_header-no_footnote.txt

silantoi@DESKTOP-4CSCM70:~/firstdir$ `for a in diary.html; do sed '1,221d;265,330d' $a > diary_no_header-no_footnote.txt; done`

# grep Assingment
## Assignemnt

 - Cd to the directory /exercise-data/writing
 - Create a for loop that you will use on the LittleWomen.txt
 - The loop should count the names "Jo" , "Meg", "Beth", "Amy"
 - And prints the output on the screen

silantoi@DESKTOP-4CSCM70:~/shell-lesson-data/exercise-data/writing$ `for a in Jo Meg Beth Amy; do printf "$a "; less LittleWomen.txt | grep $a |wc -l; done`
|....|....|
|Jo  |1528|
|Meg |685 |
|Beth|463 |

