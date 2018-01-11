## Workshop Description
This one-day workshop is for those interested in expanding their R skills to estimate basic population dynamic rate parameters. Through a sequence of short lectures, code demonstrations, and hands-on application exercises, participants will use R to construct and apply an age-length key to estimate ages of individual fish from their lengths, estimate mortality rates and compare rates among groups, fit a von Bertalanffy growth function (VBGF) and compare function parameters among groups, and fit weight-length relationships and compare parameters among groups. A short demonstration for creating reproducible reports will also be demonstrated. Participants should be familiar with the fundamentals of R. [See the workshop announcement](https://midwestfishwildlifeconferen2018.sched.com/event/Cde4/workshop-introductory-fisheries-analyses-with-r).

----

## Pre-Workshop Preparation - REQUIRED
* **Install R**: Install at least version 3.4.0 of R (*note that 3.4.3 is the latest version*) on your laptop. Directions for a first install are [here for Windows](http://derekogle.com/IFAR/supplements/installations/InstallRWin.html){:target="_blank"} or [here for MacOS](http://derekogle.com/IFAR/supplements/installations/InstallRMac.html){:target="_blank"}. If you are using Windows and already have R installed, then [here is an easy method to upgrade](http://www.r-statistics.com/2015/06/a-step-by-step-screenshots-tutorial-for-upgrading-r-on-windows/){:target="_blank"}. [*The MacOS installation directions may be dated. Simply following the installation defaults should be fine.*]
* **Install RStudio**: [RStudio](https://www.rstudio.com/products/RStudio/){:target="_blank"} is not required for this workshop but I **strongly encourage** you to use it to interact with R. Directions to install and prepare RStudio are [here for Windows](http://derekogle.com/IFAR/supplements/installations/InstallRStudioWin.html){:target="_blank"} and [here for MacOS](http://derekogle.com/IFAR/supplements/installations/InstallRStudioMac.html){:target="_blank"}. [*The MacOS installation directions may be dated. Simply following the installation defaults should be fine.*]
* **Install R Packages**: Install the `FSA`, `FSAdata`, `AICcmodavg`, `captioner`, `dplyr`, `magrittr`, `minpack.lm`, and  `nlstools` packages. Directions for installing packages are [here if you plan to use RStudio](http://derekogle.com/IFAR/supplements/installations/InstallPackagesRStudio.html){:target="_blank"} and [here for Windows](http://derekogle.com/IFAR/supplements/installations/InstallPackagesRWin.html) and [here for MacOS](http://derekogle.com/IFAR/supplements/installations/InstallPackagesRMac.html){:target="_blank"} if you plan to use R directly. Test your package installations by seeing if [this script](InstallationTester.R) runs without error.
* **Get Workshop Materials**: Download (to one folder/directory on your computer) each of these six items:
    * [Lecture Slides (PowerPoint)](Slides.pptx)
    * [Pygmy Whitefish R Script](PWF2016_Student.R) and [data](PWF2016.csv)
    * [Walleye Assignments](WAE_Escanaba.pdf) and [data](WAE_Escanaba_2011_14.csv)
    * [Reproducible Reports Example](ReproReport.Rmd)

----

## Pre-Workshop Preparation - OPTIONAL
* *Get Book*: The materials for this workshop are based on my [*Introduction to Fisheries Analysis with R*](http://derekogle.com/IFAR/){:target="_blank"} book (IFAR). This book is NOT required for the workshop but is available at a 20% discount for workshop participants in this workshop. [Contact me](mailto:derek@derekogle.com) for how to order with the discount.
* *Read Book Chapters*: You may want to (re)familiarize yourself with R basics (IFAR Chapters 1-3), age-length keys (IFAR Chapter 5), estimating mortality rates (IFAR chapter 11), von Bertalanffy growth functions (IFAR Chapter 12), and weight-length relationships (IFAR Chapter 7).
* *Can You Knit?*: If you want to try the reproducible reports example (see above) on your own computer, then, to prepare your computer, you should select the File menu, New File submenu, and R Markdown submenu; select the PDF option on the ensuing dialog box and press OK; save the document that opens onto your computer (don't give the filename an extension); and then press the "Knit" icon on the RStudio script pane toolbar. Install some packages if prompted to do so. If a PDF document is produced then your computer is prepared to compile the reproducible reports example (assuming that you successfully followed the installation instructions above). 

----

## Post-Workshop Follow-up
* Please complete [this survey](https://goo.gl/forms/rNZ2lIEZFzkCW6WO2) regarding this workshop.
* If you have any questions please feel free to [contact me](mailto:derek@derekogle.com).
