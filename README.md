# Operating Systems Project - Linux Command "mbob it"
by Cristalina Nguyen, Christian Santander, Liam Namba

Project for Operating Systems at Loyola Marymount University

## Description
"mbob it" is a command that changes file names and writes them with RanDoM_aLTErNAtInG_cAPs (writing compound words or phrases in which the letters in the words are randomly capitalized). "mbob it" was inspired by the 'Mocking Spongebob Meme', shown below, where a photo of spongebob and a phrase in random alternation caps is used to mock a person. When called, "mbob it" renames the given file, and outputs the image of Spongebob Squarepants in ASCII below it with a quote of the file name.

![2tna31](https://user-images.githubusercontent.com/21330088/52768280-f1a85a00-2fe1-11e9-9127-fd2bb7afcbee.jpg)

## Rationale
The point of "mbob it" is purely humourous, but demonstrates good understanding and ability to manipulate and add to linux modules. Why this is a good idea, or what the good points of it are 


## 1.3 – List of Linux modules that will be modified/affected
"mv" - command that moves one or more files or directories from one place to another where the file content is copied to the new location and the old file is removed. However if both filenames are on the same filesystem, "mv" results in a simple file rename.

"ls" - command that lists computer files where when invoked without any arguments, ls lists the files in the current working directory.


## 1.4 – Preliminary list of any new modules that you will produce [or 'Not Applicable' if there are none]
Not applicable.
- Reverse mbob it?

## 2.1 - Detailed list of Linux modules that will be modified/affected
Modules: "mv" and "ls" utilities

## 2.2 - Detailed list of any new modules that you will produce 
Not applicable - no new modules will be produced

## 2.3 - Class diagram showing affected modules and how they related to one another
[mbob it class diagram.pdf](https://github.com/cristalinanguyen/OperatingSystemsProject/files/3105602/mbob.it.class.diagram.pdf)

## 2.4 - List of explanations of all command line options that will be implemented
"mv" module - since the move module results in a simple file rename if the filenames are on the same filesystem, "mv" will rename the file we want using random capilization case when called on a file

"ls" module - invoked without arguments, to display the files in the directory to view which we would like to rename
