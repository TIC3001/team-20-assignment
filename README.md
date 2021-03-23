# KWIC (Key Word In Context) Index System
### TIC3001 Assignment 1 for AY2021S2 Team-10

[![Build Status](https://travis-ci.com/TIC3001/tic3001-assignments-ay2021-s2-team-10.svg?token=7MRUrCuQPyv2djJv2xqo&branch=main)](https://travis-ci.com/TIC3001/tic3001-assignments-ay2021-s2-team-10)

## Folder Structure
```
.
|   .gitignore
|   index.py			    # version of program using pipe and filter architecture
|   README.md
|
+---input_files             # files used to test the program
|       anime.txt
|       books.txt
|       movies.txt
|
+---implicit_invocation     # version of program using a implicit invocation architecture
|       main.py
|
\---output_files            # output files from both versions.
        anime_output.txt
        anime_output2.txt
        books_output.txt
        books_output2.txt
        movies_output.txt
        movies_output2.txt
```
## Requirements
`Python 3.6 and above`

## Download and Installation
With Git installed:  
Download the repository by running this command in either Command-Prompt or your preferred console terminal:  
`git clone https://github.com/TIC3001/tic3001-assignments-ay2021-s2-team-10.git`

<b>To use the `implicit invocation` version of the program: </b>

<div>

1) go to the directory of the version of the program that you'd like to use with either:   
`cd ./implicit_invocation`

2) pass a path for a single text file for the program to process: (not doing so will cause program to prompt you to do so afterwards.)  
`python ./main.py (PATH)`
</div>  

<br>

<b>To use the `pipe and filter` version of the program: </b>
<div>
1) pass a path for a directory of text files or a single text file for the program to process:  
    `python ./index.py`
	
	note: input_files folder should be in the same directory as index.py
</div> 

<br>
<hr>

## Credits
### Team Members
- Low Yan Shuang
- Ivan Ho