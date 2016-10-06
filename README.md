# Introduction to R and spatial data
𝗥 and 🗺 - introduction to R and spatial data! A 3hr interactive workshop.


# Workshop outline

An introduction to reproducible data analysis with R. The aim of this
workshop is to help you decide if R is for you or not and how to learn
more about it. We will cover how to
get started and structure your projects in R. Create publication quality
figures and tables that can be updated with a click of a button. How to
create reports that contain both narrative/prose and figures/tables. Furthermore
we will show you how to learn more (self-study) and how to get help when
you are stuck. To get the most out of the workshop you will have to have
some experience with basic concepts of programming (in any language) like:
variables, functions and libraries.

This will be an interactive workshop. Before arriving please:

* pack your laptop and its charger
* [install R and RStudio](#software)
* download the data we will use
* introduce yourself on [the shared notepad](https://public.etherpad-mozilla.org/p/geong-r-and-maps-2016) of the workshop


# Personas, do you recognise yourself?

If you are wondering who this workshop is for take a look at the [personas
of fictional attendees][personas] we created to help design the workshop.

[personas]: https://github.com/wildtreetech/r-and-maps/issues/1


# Learning objectives

At the end of the workshop I will ...

* ... be able to create a new project that contains an analysis script
  which takes raw data and produces figures and tables from it without
  modifying the raw data.
* ... be able to place markers on an interactive map and share it with
  my colleagues.
* ... be able to recognise when I am stuck.
* ... know where to find documentation and how to ask good questions to
  maximise my chances of getting help.
* ... know that there is no magic: the programs I use are no different
  in principle from those that I build.


# Software

For this workshop will be using R and RStudio. As the workshop is only 3hrs
long you will have to have these installed and working prior to the
workshop. Installing R and RStudio is straightforward: just download and
install the version appropriate for your operating system. If you run into
issues contact Tim: <tim@wildtreetech.com>

- R: [Windows](https://cran.r-project.org/bin/windows/base/R-3.3.1-win.exe) | [Mac OS X 10.9+ (Mavericks) ](https://cran.r-project.org/bin/macosx/R-3.3.1.pkg) |  [Others](https://cran.r-project.org/)
- RStudio: [Windows](https://download1.rstudio.org/RStudio-0.99.903.exe) | [Mac OS X 10.6+ (Snow Leopard) ](https://download1.rstudio.org/RStudio-0.99.903.dmg) |  [Others](https://www.rstudio.com/products/rstudio/download/)

We will use a few libraries that are not part of R by default. You can install
them by running the following commands in RStudio:

```R
install.packages("ggplot2")
install.packages("rmarkdown")
install.packages("leaflet")
```
