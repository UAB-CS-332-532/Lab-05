# Lab-05: Unix File System

## Name: 

## Honor Code:

I, _______, declare that I have completed this assignment completely and entirely on my own, without any unathorized consultation from others or unathorized access to online websites. I have read the UAB Academic Honor Code and understand that any breach of the UAB Academic Honor Code may result in severe penalties.

Student Signature/Initials: ____________

Date: ____________

## Assignment:

Modify the *ReadDir_V2.c* file to traverse the file hierarchy recursively.

(ReadDir_V2.c: https://github.com/UAB-CS-332-532/Lab-05/blob/497c1fe17bf68d9220c2b99fd92da880a2df47ec/ReadDir_V2.c)

- The starting directory should be specified as a command-line argument (e.g. ./lab05 ../Labs)

- You should list all sub-directories and the files in those sub-directories.

- You should create a function *"recursivelyTraverseFileHiearchy"* that recursively calls itself on each sub-directory.

- Your solution will assist you in solving HW2.

## Example:

` $ ./lab05 ../
> [1] .DS_Store (regular file)
>
> [2] Lab-01 (directory)
>
>    [1] README.md (regular file)
>
>    [2] a.out (regular file)
>
>    [3] .gitignore (regular file)
>
>    [4] HelloWorld.c (regular file)
>
>    [5] .git (directory)
>
>        [1] config (regular file)
>
>        [2] objects (directory)
`
