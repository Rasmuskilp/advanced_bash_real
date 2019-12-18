#Advanced Bash

This lecture will cover concepts and commands in bash.
- STDIN,STDOUT,STDERR

## concepts:
- extension less
- everything is a files
- case sensitive - when doing grep or ls

## commands
- wild cards
- permissions
- chmod [permission binary] [file]
- filters
- head -2 words.txt
- tail -3words.txt
- sort words.txt
- nl
- wc #wordcount gives number of characters


- STDIN STDOUT and STDERR
these have number that identify them.
STDIN --> 0
STDOUT --> 1
STDERR --> 2
## Piping and Redirection
-
`` $ls missing_directory
> ls:cannot access 'missing_directory': no such file or directiory
$ ls missing_directory 2>> error_logs.txt # append with second arrow
$ cat error_logs.txt
``
``
cat word.txt | grep li
 > delicious
  $ cat words.txt | grep -v a | sort -r
  > [inverted list of words without an a]
  
``
