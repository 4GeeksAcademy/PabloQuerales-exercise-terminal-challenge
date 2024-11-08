`#COMMAND LINE`
Get inside the thecmdchallenge/ directory
-ls
-cd thecmdchallenge
´´Print current directory path´´
-pwd
´´List all the files from the current directory including the hidden ones´´
-ls -a
´´Now list all the files inside the project, recursively (all files in the hierarchy)´´
-ls -laR
`Clear all the clutter from the command line`
-clear
`Go to the last level below the small-name folder and show on the console the content of the trophy.txt file`
-find . -name trophy.txt
-cd ./small-name/bigger-name-than-before/omg-this-folder-has-a-huuuuuuge-name-and-i-tired-to-type/this-is-probably-the-longest-folder-name-you-have-ever-seen-but-believe--im-sure-there-are-other-folder-bigger-than-this-one-because-people-sometimes-like-to-assign-huge-names-to-their-personal-stuff-supercalifragilisticexpialidocious
-cat trophy.txt
`Move one level up and get to the funcode directory and list all files with the JavaScript typical extension`
-cd ..
-ls *.js
`Create a new directory inside funcode/the-most-funny/ called “not-that-funny“`
-cd the-most-funny
-mkdir not-that-funny
-ls
`Create a copy of the-mostboring-text.txt (you can find it within /boringfolder/‘s children) and name it lol.txt`
-find . -name the-mostboring-text.txt
-cd ./boringfolder/even-more-boring/i-cant-believe-how-boring/the-ultimate-boring-inception/
-cp the-mostboring-text.txt lol.txt
-ls
`Move funcode/kids.jpg inside funcode/images/hello/`
-cd ../../../..
-cd funcode
-mv kinds.jpg images/hello
-cd images/hello
-ls
`Remove the “small-name“ directory`
-cd ../../..
-ls
-rm -r small-name/
`Print in the command line the content of the-ultimate-joke.txt`
-cat $(find . -name the-ultimate-joke.txt)
`Remove all the contents from the boringfolder, they are extremely boring…`
-cd boringfolder/
-rm -r *
`Update the file kamehameha/dragon-ball-jokes.md by removing the first joke you read on the file, finally save and close the text editor`
-tecla "d" para borrar una linea o tecla "x" para borrar caracteres
-:qw 