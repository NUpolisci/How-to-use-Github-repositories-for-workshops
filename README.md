# How-to-use-Github-repositories-for-workshops
This repository is for students who do not know how to access files in github repositories

## Overview of Github
Github is essentially like 'Dropbox', 'Google Drive', 'Box', etc... It is a ways to manage versions of files, including R scripts, between collaborators and your past and furture selves. Rather than having each departmental workshop run out of different folders via 'Dropbox', 'Google Drive', 'Box', etc... we can put it all onto Github. This makes it simple for accessing the latest versions of all workshops, as well as previous workshops. 

## Simple: How to Download Github Repositories 

If you click on a repository, you will be lead to the repository's 'landing page'. For instance, this repository's 'landing page' is <a href="https://github.com/NUpolisci/How-to-use-Github-repositories-for-workshops"> here</a>. Once here, click on the green button which says `Code`. From there, you can download the repository as a zip file. 

<img src = "https://github.com/NUpolisci/How-to-use-Github-repositories-for-workshops/blob/main/Figures/Download.png" width ="800">
When you unzip the file, you can save it in any place on your computer that you prefer.

## Advanced: Connecting the Repo with Rstudio

You can consult <a href="https://happygitwithr.com">this guide</a>.

Basically, you must first you must make sure you have a Github account and that you have installed both Git and Rstudio onto your computer. Once you have created those accounts *and* downloaded both Rstudio and Git, you can continue in <a href="https://happygitwithr.com/push-pull-github.html">Chapter 9</a> through to Chapter 12. Once you have connected github with your computer, you can download the repository straight through to your laptop and Rstudio. 

To do so, go to the repository's landing page once again. In this case, it is <a href="https://github.com/NUpolisci/How-to-use-Github-repositories-for-workshops"> here</a>. Once here, click on the green button which says `Code`. This time, instead of clicking `Download Zip`, you can copy the `HTTPS` (or `SSH`, but this requires you to set up SSH first). 

<img src = "https://github.com/NUpolisci/How-to-use-Github-repositories-for-workshops/blob/main/Figures/Copied.png" width ="800">

### Connect with Rstudio

Open Rstudio and go to *File > New Project*. From there, select *Version Control*. 

<img src = "https://github.com/NUpolisci/How-to-use-Github-repositories-for-workshops/blob/main/Figures/Version Control.png" width ="600">

Next, select *Git*. 

<img src = "https://github.com/NUpolisci/How-to-use-Github-repositories-for-workshops/blob/main/Figures/git.png" width ="600">

From here, you will see a page will allows you to save your repository in a specific location in your computer. But you still have to communicate *which* repository you want from Github.

<img src = "https://github.com/NUpolisci/How-to-use-Github-repositories-for-workshops/blob/main/Figures/Clone.png" width ="600">

You can now paste the HTTPS you copied into the `Repository URL` line. 

<img src = "https://github.com/NUpolisci/How-to-use-Github-repositories-for-workshops/blob/main/Figures/Paste.png" width ="600">

Then click `Create Respository`. Your Rstudio will then open and all the files associated with the repository will appear under the files section of your Rstuido workspace (typically the lower right hand panel). 
