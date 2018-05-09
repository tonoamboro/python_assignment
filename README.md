# Python Assignment
## Author
Tono Amboro

## Description
This repository was created as a part assignment on Big Data Analysis course, which will attempt to create several methods for analyzing DNA sequence using Python 3.  

## Contents of the repository
1. README.md (this file).
2. Script.ipynb. It is a python script which generated from Jupyter lab. I created this file so that I can try some scripts before I write it on the .py files. This file is the environment for trial and error of some scripts. 
3. assg_script.py. It is the main script that I created for this assignment. In this script, I write some method to achieve the goal of this assignment. 
4. test_assg_script.py. It is a pytest file for testing the function that I wrote in the main script. This script ensures the main script to generate the desired output. 
5. nd2.fasta. It is a DNA sample (in .fasta format) that contain a lot of DNA sequences from many species. Our instructor provides this file. 
6. dna_sample.fasta. It is a DNA sample (in .fasta format) that I created to work on my main script. It contains fewer sequences so I could accelerate the process. 
7. dna_false_sample.fasta. It is a DNA sample (in .fasta format) that I created to work on my main script. It also contains fewer sequences so I could accelerate the process. However, this file has a false sequence alphabets on it, which also similar with the nd2.fasta file. This is an important file so that we could test the script whether it could differentiate the DNA sequence (ATCG) with another sequence, also to spot when something is wrong with the DNA sequence. 
8. output folder. This folder contain tables folder and graphs folder to save the desired output from the main script. Inside the tables folder, there are several .csv file with table in it. Whereas inside the graphs folder, there are two graphs generated by the main script.

## IMPORTANT! So you could use the script and replicate the process!
Before you run the script:
1. Ensure your data file is in .fasta format.
2. Place the script and the data in the same directory.
3. Create output folder in the same directory, and create tables and graphs folder inside the output folder.
4. Although, you will be warned when your DNA sequence is incorrect, always ensuring your DNA sequence in the right format is recommended.
