# COMMAND LINE💻💻💻

## Get inside the thecmdchallenge/ directory:
1. ls
2. cd thecmdchallenge

## Print current directory path:
1. pwd

## List all the files from the current directory including the hidden ones:
1. ls -a

## Now list all the files inside the project, recursively (all files in the hierarchy):
1. ls 
2. laR

## Clear all the clutter from the command line:
1. clear

## Go to the last level below the small-name folder and show on the console the content of the trophy.txt file:

1. find . -name trophy.txt
2. cd ./small-name/bigger-name-than-before/omg-this-folder-has-a-huuuuuuge-name-and-i-tired-to-type/this-is-probably-the-longest-folder-name-you-have-ever-seen-but-believe--im-sure-there-are-other-folder-bigger-than-this-one-because-people-sometimes-like-to-assign-huge-names-to-their-personal-stuff-supercalifragilisticexpialidocious
3. cat trophy.txt

## Move one level up and get to the funcode directory and list all files with the JavaScript typical extension:
1. cd ..
2. ls *.js

## Create a new directory inside funcode/the-most-funny/ called “not-that-funny“:
1. cd the-most-funny
2. mkdir not-that-funny
3. ls

## Create a copy of the-mostboring-text.txt (you can find it within /boringfolder/‘s children) and name it lol.txt:
1. find . -name the-mostboring-text.txt
2. cd ./boringfolder/even-more-boring/i-cant-believe-how-boring/the-ultimate-boring-inception/
3. cp the-mostboring-text.txt lol.txt
4. ls

## Move funcode/kids.jpg inside funcode/images/hello/:
1. cd ../../../..
2. cd funcode
3. mv kinds.jpg images/hello
4. cd images/hello
5. ls

## Remove the “small-name“ directory:
1. cd ../../..
2. ls
3. rm -r small-name/
## Print in the command line the content of the-ultimate-joke.txt:
1. cat $(find . -name the-ultimate-joke.txt)

## Remove all the contents from the boringfolder, they are extremely boring…:
1. cd boringfolder/
2. rm -r *

## Update the file kamehameha/dragon-ball-jokes.md by removing the first joke you read on the file, finally save and close the text editor
1. tecla "d" para borrar una linea o tecla "x" para borrar caracteres
2. :qw 