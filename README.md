# T.b.brucei_RNA_analysis
(Only works on the University of Edinburgh Bioinformatics server. If you want to use this on your own laptop, change the directory in the first block of the code into where your raw RNA-seq are)

A.  Modules

(1) perform quality check of paired-end raw sequence data

(2) assess number and quality

(3) align read pairs

(4) generate counts data and put it into a single plain text tab-delimited ouput file


B.	User interaction

(1)	At the end of fastqc quality check, the fail/warn message will be shown on the screen. Based on the this the user will be asked to choose whether to continue pair alignment.

(2)	At the very end of the program, the user can choose whether to view the full/part output file right now.

C.  Flowchart

![](https://user-images.githubusercontent.com/46657555/74935908-0aabce00-53e1-11ea-96ee-7aa230ac5a44.png)
