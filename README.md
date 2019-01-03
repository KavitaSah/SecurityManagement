# Security Management & Computer Forensics

## Github for Beginners
1. Install Git  
Follow the instructions here: https://git-scm.com/book/en/v1/Getting-Started-Installing-Git  

2. Checkout our Class Respository
In terminal, run the following to copy the released homework directory to your desktop.   
```$ git clone https://github.com/carriegardner428/SecurityManagement.git```  

- To Update,  
Run a Git Pull  

```
$ git pull origin master 
```  

- To Revert a File...  
Let's say you make a mistake on a file and want to bring back the original copy...  

```
$ git checkout -- <filename>
``` 

- To Commit (Save) Your Changes  
To log checkpoints for things done  

```
$ git add <filename>  
$ git commit -m 'your commit message'  
```  

## Environment Set-Up  

With Conda  
1. 
``` 
$ conda create -n sec python=3.5 anaconda 
```
2. 
```
$ source activate sec
```

Requirements:  
- python==3.5.4  
- pandas==0.22  
- jupyter==1.0.0

[To Be Updated]: I suggest some sort of virtual environment manager, such as conda or pipenv. Or, you can pull a docker image from jupyter. 

## Assignment Submission
After you have complted the assignment, you must turn in the PDF copy to Courseweb.  

- *.pdf - Export the *.ipynb jupyter notebok as a PDF  
- Login to Courseweb and upload the PDF of the assignment  



