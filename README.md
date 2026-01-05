In this lab, you will install the software needed for this course and confirm it is working on your computer. Even if you already have R or RStudio installed on your computer, please make sure that it is the most recent version of the software. 

Note that this lab is not graded. However, it is important to complete it by Thursday (1/15). During class on Friday (1/16), we will practice using and knitting R Markdown files. (To submit all future labs and homework assignments, you will need to know how to use and knit an R Markdown file.)

Please follow the instructions below. 

# Part I: Software Installation

1. Install the latest version of R from the CRAN web site: https://cloud.r-project.org/
2. Install the latest version of RStudio from the Posit web site: https://posit.co/download/rstudio-desktop/
3. Install Git from the Git web site: https://git-scm.com/downloads [Mac only: Install Xcode developer tools from the App Store, if you have not already done so.]

# Part II: Checking Installation

1. Open RStudio.
2. Click File > New Project... > Version Control > Git.
3. Enter this information.
  Project URL: https://github.com/SDS-322E-EODS/Lab0 
  Project directory name: Lab0
  Create project as a subdirectory of: You may choose to select a directory to store the project or use the default.
4. Click Create Project.
5. Run this line of code in the Console section of RStudio: install.packages(c("rmarkdown", "knitr"))
  Once you have run that code, you may be prompted to update other package dependencies. Please follow the prompt to do so.
6. Open Lab0.Rmd by clicking it in the Files section.
7. Click the Knit.

If an HTML file saying "Success!" is generated, you have successfully completed Lab 0. If you get an error, see if you can figure out what is going wrong (based on the error message) or ask a fellow student or the TA for help.


