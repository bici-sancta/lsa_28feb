# lsa_28feb
live session assignment - data science - 28-feb

** Goal: **  Create an RStudio project for the analysis of this data set. Your file structure within the project should include the following:

#### A README file in the project root directory that includes an explanation of the purpose of the project and the other files  

#### A Data directory containing files to load in and clean up the data. The clean up should include finding out where there are outliers or missing values, deciding how you will treat them, making sure values you think are numerical are being treated as such (correct R class), etc.  

--> the data directory contains the following :  
    -- data_cleaning.Rmd ... markdown file to perform data cleaning and .html summary  
    -- data_cleaning.html ... output of .Rmd ... some views of the in-process data cleaning  
    -- manhattan.proj.Rda ... save data structure "bk.homes" - the recommended data set for analysis, post-cleaning  
    -- rolling_sales_manhattan.csv ... the original raw data set

#### An Analysis directory containing a file (or files) for exploratory data analysis on the clean data to visualize compare the square footage and sales price for your neighborhood.  

--> the analysis directory contains the following :  
    -- analysis.Rmd ... markdown file to perform some fundamental analysis on cleaned data set  
    -- analysis.html ... output of .Rmd ... some plots of data vs. potential independent variables    

#### A Paper directory containing a file (plain text or Markdown) that explains any meaningful patterns in this dataset.  

--> the paper directory contains the following :  
    -- manhattan_project.Rmd ... markdown file to summarize results of analysis     
    -- manhattan_project.html ... the project summary  
    
    
### Tip : to render the .html pages that are referenced on this repo ...  
go to this site : http://htmlpreview.github.io/?  
and copy/paste the .html link from this page into the text box  

