# RStudio

If you are unfamiliar with the RStudio Integrated Development Environment (IDE) then we suggest you have a look at the following:

1. [Introduction to R and RStudio](https://www.sitepoint.com/introduction-r-rstudio/)
2. ['Working with RStudio' course by DataCamp](https://www.datacamp.com/courses/working-with-the-rstudio-ide-part-1/)
3. [Official RStudio documentation](https://support.rstudio.com/hc/en-us/sections/203994097-RStudio-IDE/)

## Uploading and downloading files to RStudio in your Sandbox

### Uploading Files

To upload datasets, scripts, or other files to the RStudio IDE in a web browser you should take the following steps:

1. Switch to the Files pane
2. Navigate to the directory you wish to upload files into
3. Click the ‘Upload’ button in the toolbar of the Files pane
4. Choose the file you wish to upload from your computer and press 'OK'

* Note that if you wish to upload several files or even an entire folder, you should first compress your files or folder into a zip file and then upload the zip file (when RStudio receives an uploaded zip file it automatically uncompresses it).

### Downloading Files

To download files from RStudio IDE in a web browser you should take the following steps:

1. Switch to directory you want to download files from within the Files pane
2. Select the file(s) and/or folder(s) you want to download
3. Click More -> Export on the toolbar
4. You'll then be prompted with a default file name for the download. Either accept the default or specify a custom name then press OK.

* Note that if you select multiple files or folders for download then RStudio compresses all of the files into a single zip archive for downloading.

*Source: [RStudio support article](https://support.rstudio.com/hc/en-us/articles/200713893-Uploading-and-Downloading-Files/)*

## Read a data file from a website into a dataframe

If you have a data file that is accessible from a website URL you can read it into your RStudio IDE. This example uses the common 'csv' format. Use the following code in your console window:

```
# Install the RCurl package 
install.packages("RCurl")

# Load the RCurl library
library(RCurl)

# Create a variable to store the csv file 'getURL' result
x <- getURL('YOUR_CSV_URL_HERE')

# Read the csv file into a dataframe named 'df'
df <- read.csv(text = x)

```
You can read a wide range of file formats into R: 
[Data import with R](http://www.r-tutor.com/r-introduction/data-frame/data-import/)

## Data analysis

There are many popular R tutorials and courses available online, which will help you analyse your data. Examples include:

* [Introduction to R by DataCamp](https://www.datacamp.com/courses/free-introduction-to-r)
* [Curated list of R tutorials for Data Science](https://www.r-bloggers.com/curated-list-of-r-tutorials-for-data-science/)
* ['Introduction to R for Data Science' by FutureLearn](https://www.futurelearn.com/courses/data-science)

## Share your work

The easiest, most effective way to share your work is by using GitHub. If you haven't used R with Git and GitHub then we recommend these tutorials:

1. ['Happy Git and GitHub for the useR' by Jenny Bryan](http://happygitwithr.com/) from her [GitHub repository](https://github.com/jennybc/happy-git-with-r/)
2. ['RStudio and GitHub' by DataSurg](http://www.datasurg.net/2015/07/13/rstudio-and-github/)