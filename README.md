This repository is a companion for the workshop conducted at the [19th Congress of the International Society for Folk Narrative Research](https://en.lfk.lv/isfnr2024) related to the topic *Digital Approaches in Narrative Research: Opportunities and Challenges*. The workshop is intended for a beginner audience of folklorists who are interested in learning about the use of data science tools to analyze folktale texts, types, and motifs using the `trilogy` ensemble of datasets.  For this workshop, we will be using the `R` statistical programming language, as well as `Git` to share code. Please read the following instructions in preparation for your attendance at the workshop.  

__Note:__ If you run into issues or have questions during the installation of the necessary software and packages, please [file an issue here](https://github.com/j-hagedorn/trilogy_workshop/issues/new) describing your question so that I can update the documentation to help you and other potential attendees.  Excited for our time together in Riga!

### Before the workshop

Please complete the following steps prior to attending the workshop, in order to assure that you will be able to meaningfully participate without encountering technical issues. We will not have time during the workshop to troubleshoot technical installation issues on individual users' machines. The setup will likely take about 30 minutes, so be sure to give yourself enough time:

**Set up GitHub and make a local fork of this repository**

1. [Sign up for a GitHub account](https://github.com/signup)
2. [Install Git](https://git-scm.com/downloads) on the computer you will use at the workshop session.
3. [Install Github Desktop](https://desktop.github.com/) on the computer you will use at the workshop session. Open it and follow the instructions to connect it to your personal GitHub account.
4. Fork this GitHub repository (*by clicking 'Fork' at the top of this page*) to create a copy under your own account.
5. Clone your forked GitHub repository to your computer so that you can edit the files locally on your own machine. You can do this in GitHub Desktop by selecting *File* |> *Clone repository* and then selecting `{your_username}/trilogy_workshop`
6. *The day of the workshop*, update your local version from the upstream repository [using these instructions](https://stackoverflow.com/questions/46110615/how-to-sync-your-forked-repo-with-original-repo-in-github-desktop).  Since I will be making changes to the materials as we approach the workshop, this will ensure that your copy is up-to-date.

**Set up the RStudio environment**

1. [Install R and RStudio](https://posit.co/download/rstudio-desktop/) on the computer you will use at the workshop session. 
3. Open RStudio and copy/paste the following code in the "Console" area: `install.packages(c("tidyverse","rmarkdown","bslib","revealjs","plotly","reactable","quanteda","UpSetR","patchwork"))`
4. In the upper right corner of RStudio, select "Open Project..." and navigate to the folder for this repository ("trilogy_workshop").  Select the `trilogy_workshop.Rproj` file.
5. Check that the "Files" from this repository now appear in the lower right-hand pane of your RStudio window.

### During the workshop

We'll be going through:

1. [Intro slides](https://j-hagedorn.github.io/trilogy_workshop/slides/slides.html#/)
2. Example data exploration in [Introduction to the Trilogy](https://j-hagedorn.github.io/trilogy_workshop/notebooks/intro_to_trilogy.html)
3. A sample use case for using the Trilogy datasets to explore a specific question.

### Other resources

Hagedorn, J. (2023). trilogy: Reference datasets for myth and folktale motifs [Software]. *GitHub*. https://github.com/j-hagedorn/trilogy

Hagedorn, J., & Darányi, S. (2022). Bearing a Bag-of-Tales: An Open Corpus of Annotated Folktales for Reproducible Research. *Journal of Open Humanities Data*, 8(0), 16. [doi.org/10.5334/johd.78](https://doi.org/10.5334/johd.78)

Eklund, J., Hagedorn, J. & Darányi, S. (2023). Teaching Tale Types to a Computer: A First Experiment with the Annotated Folktales Collection. *Fabula*, 64(1-2), 92-106. [doi.org/10.1515/fabula-2023-0005](https://doi.org/10.1515/fabula-2023-0005)

### Disclaimer

*Presenter and repository author is not liable for any issues which result from the downloading of software or use of code on either a personal or organizational device.*