# Sed_command_assingment
## Assignment

    Use the sed command in a for loop to remove the following lines in the file diary.html
    1 to 221
    265 to 330
    Save the ouptput in a file called diary_n

    (base) silantoi@DESKTOP-4CSCM70:~/firstdir$ `for a in diary.html; do sed -n '1,221p' '265,330p' $a > diary_no_header-no-footnote.txt | sed -i '1,221d' '265,330d' $a; done`

sed: can't read 265,330d: No such file or directory

sed: can't read 265,330p: No such file or directory

(base) silantoi@DESKTOP-4CSCM70:~/firstdir$ less diary_no_header-no-footnote.txt
