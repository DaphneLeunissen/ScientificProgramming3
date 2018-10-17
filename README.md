# ScientificProgramming3
## Assignment 3 Parallel computing

Processing big data mostly requires lots of computing. Dividing a large problem into smaller problems and solving these smaller problems simultaneously can solve the computing issue. This type of computation is called parallel computing in which the execution of many processes are performed at the same time. In this assignment an algorithm will be designed to process the data in parallel. The data used for this assignment can be downloaded from PubChem (PubChem Assay AID 624202). 
Once on this webpage you need to click on download, tested substances and subsequently download structure SDF where you can download the file as a zip file. After which you need to unzip the folder.  

An R Markdown notebook is created to carry out this assignment. The ‘rcdk’ package will be used to calculate the molecular descriptors and making the code parallel. And also the ‘iterators’ package and ‘doParallel’ package are needed to execute the code. The research questions underlying this assignment consists of 1: When making use of 2 or 4 cores does this also make your code twice of four times faster? And 2: Which CDK descriptors are not thread-safe?

#### How to run the code

The code has been writing as a R Markdown file (saved as Assignment3.Rmd) and can be executed using RStudio. To run this code it is important to adapt the working directory to yours, this is the folder where the SDF file need to be in. After downloading the data, as described above, and changing the working directory the code can be executed by clicking on the Run button in RStudio. The code will install and load required packages, import the data and save the molecules in the mols list. Next the code will calculate the molecular descriptors in parallel and save the time it took to calculate the descriptors performed by various amounts of cores. And finally the results will be plotted. When you click on the Knit button instead of the run button it will create the html file, which is the output of this R markdown file. 

### Prerequisites 

RStudio

#### Programming language

R

#### File format

Markdown

#### Programming Approaches
*	Interactive notebooks
*	Parallel computing 

