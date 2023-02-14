## BIOL MARI 4323   
### 15 February 2023  

#### 1. Install R  

If you are using Windows, use [this .exe file](https://cran.r-project.org/bin/windows/base/release.htm) to download and install the software.  

If you are using a Mac, go to [this page](https://cran.r-project.org/mirrors.html), and select the link associated with the location nearest to you. From there, follow the link to the Mac download and select the most up-to-date version to access the files you will need to download and install the software.  

*If you already have R installed on your computer, please ensure that it is at least version 4.2*

#### 2. Install RStudio  

Install the free RStudio IDE from [this website](https://www.rstudio.com/products/rstudio/download/#download) by selecting the version appropriate for your operating system (Windows or Mac).  

*If you already have RStudio installed on your computer, please ensure that it is at least version 2022.02*

**Note: If you have separate user and admin accounts, you should run the installers as administrator (right-click on .exe file and select "Run as administrator" instead of double-clicking). Otherwise problems may occur later.**

#### 3. Install Packages  

*You will need to be connected to the internet for this to work*

- Open RStudio
- Look for the `>` symbol in the lower left hand corner, and click to place your cursor to the right of it.  
- Install the up-to-date version of the `dplyr` package by typing `install.packages("dplyr")` and hitting Enter on your keyboard.  
  - You will see messages and text appear in RStudio; the final message should say something like `The downloaded binary packages are in...` and a file location. This means it worked!  
- Do the same process to install up-to-date versions of these additional packages, one at a time:  

`install.packages("tidyr")`   
`install.packages("ggplot2")`   
`install.packages("FSA")` 
