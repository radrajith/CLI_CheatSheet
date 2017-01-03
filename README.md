# Command Line Cheatsheet

a command line cheatsheet created for future reference


```curl``` - is used to download stuff from online based on a link

```history```  - is used to view all the previous shell entries. 

```rm [file name]``` - to delete a file(-r to erase the directory)

```ls --all or ls -a``` - list all the items in the current directory(-l long list)


```pwd``` - print the address of the working directory
```cd``` - change directory
```cd ..```- go up one, to the parent directory
```mkdir [dir name]``` - make a directory

ctrl-R - reverse search history using keywords
ctrl-D - stop the program

```cat [name.txt]``` - concatanate command to combine files, or open a file

```wc [name.txt]``` - find the word count of the file

```diff [name1.txt] [name2.txt]``` - find the difference in the two files

```man [program name]``` - manual of the command or the program

```bc``` - calculator

```less [name.txt]``` - to open and view the file(similar to pdf opener)[/ - to search terms]

```nanao [name.txt]``` - text editor

```mv [item1, item2,.....] [directory to be moved]``` - move the files to a different directory
```cp [item1, item2,.....] [directory to be moved]``` - copy the files to a different directory

****
## globbing(works with other commands not just ls)

```ls *html``` - list all the files that have html 

```ls app*``` - list all files that start with app

```ls *pp*``` - list all files that contain the letters pp

```ls b*png``` - list all files that start with b and end with png

```ls app.{css,html} - list all app files that have html or css extensions

```ls bea?.png``` - list all the files that contains bea_.png = _ could be anyletter

```ls be[aeiou]r.png``` - list all the files that contains any letters in the square brackets. ex bear.png

