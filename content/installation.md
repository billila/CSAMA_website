
This page contains important instructions that you should follow before arriving at the course. 

Due to the limited Internet connectivity at the course venue, it is necessary that you install all required software on your laptop before arriving. Because of the range of topics covered in the course you will need to download a large number of packages, so it is really helpful to do this in advance.  To do so, please follow these steps.  

### Setup Steps

1. Please install the current release version of R (version 4.4.0).  For more instructions, please check https://cran.r-project.org/

2. Please install and set up Git. Jenny Bryan has some excellent instructions available at http://happygitwithr.com/install-git.html<br><p>
  If you are using Windows we recommend Git-For-Windows (https://git-for-windows.github.io/) and if you are using a Mac our suggestion is Git-SCM (https://git-scm.com/downloads)

3. Install a recent version of RStudio. Instructions are available here: https://posit.co/download/rstudio-desktop/

4. Extra tools
- (ONLY FOR WINDOWS USERS) Download and install Rtools, avaiable from: https://cran.r-project.org/bin/windows/Rtools/rtools42/rtools.html (Please use Rtools42 due to a bug in Rstudio with newer versions).  If you have Rstudio open you should close Rstudio and start it again after you have finished the installation. This allows the changes to take effect.
 - (ONLY FOR LINUX USERS)  If you use Linux it is likely you will need to install some additional system libraries. An example installation of the required libraries for Ubuntu 20.04 can be found at https://csama2023.bioconductor.eu/linux_libraries.html You may need to adjust this for your own Linux distribution.  In our experience, it is best
to move to the next step and return here only if needed.

5. After installing all of the above, please open RStudio and copy the line below into your R prompt:

```
  source("https://csama2024.bioconductor.eu/install_packages.R")
```
The script will check if you have the versions of R, Bioconductor and RStudio that are required for the course. The script will also install the R/Bioconductor packages needed for the course. The script might trigger a question about whether you would like to update old packages, please select the option to update “all”.  It will also download several datasets used during the course, and may prompt you to create new folders.  It is safe to use the default options here.  

This process may take a long time, but it is generally OK to leave it running after the installation has started.  The list of package may be updated nearer to the start date, so it is worth running this script several times in the build up to the course.

### In case off errors

If you encounter any errors, please pay close attention to the messages displayed, they may contain further instructions. 

For questions regarding software installation, please contact Ilaria Billato or csama (at) stat.unipd.it.

We also have a Slack channel for the course (https://csama-2024.slack.com/) where you can ask support questions and meet fellow course participants.  An invite to this will follow shortly.
