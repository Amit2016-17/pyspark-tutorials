# pyspark-tutorials
Code snippets and tutorials for working with social science data in PySpark.
Note that each .ipynb file can be downloaded and the code blocks executed or
experimented with directly using a Jupyter (formerly IPython) notebook, or
each one can be displayed in your browser as markdown text just by clicking on
it.

1. If you're new to Python entirely, consider trying an intro tutorial first. 
Python is a language that stresses readability of code, so it won't be too
difficult to dive right in.  [This](http://www.learnpython.org/en/Hello%2C_World%21 "Interactive Python Tutorial") is one good interactive tutorial.


2. After that, or if you're already comfortable with Python basics, get started
with pySpark with these two lessons.  They will assume you are comfortable with 
what Python code looks like and in general how it works, and lay out some things 
you will need to know to understand the other lessons.

   basic 1.ipynb  
   basic 2.ipynb

3. Basic data tasks are covered in the following guides.  Note that these are not
intended to be comprehensive!  They cover many of the things that are most
common, but others may require you to look them up or experiment.  Hopefully this 
framework gives you enough to get started.

   merging.ipynb  
   missing data.ipynb  
   moving average imputation.ipynb  
   pivoting.ipynb  
   resampling.ipynb  
   subsetting.ipynb  
   summary statistics.ipynb  
   graphing.ipynb
   
4. The pySpark bootstrap used by the Urban Institute to start a cluster on Amazon
Web Services only installs a handful of Python modules.  If you need others for your
work, or specfic versions, this tutorial explains how to get them.  It uses only 
standard Python libraries, and is therefore not specific to the pySpark environment:

   installing Python modules.ipynb

5. And finally, now that Spark 2.0 is deployed to Amazon Web Services development has
begun on OLS and GLM tutorials, which will be uploaded when complete.