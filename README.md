# Introduction to R and spatial data
𝗥 and 🗺 - introduction to R and spatial data! A 3hr interactive workshop.


# Workshop outline

An introduction to reproducible data analysis with R. The aim of this
workshop is to help you decide if R is for you and learn
more about it. We will cover how to
get started with R and structure your projects in it. Create publication-quality
figures and tables that can be updated with the click of a button. Produce
reports that contain both narrative/prose and figures/tables. Furthermore,
we will show you how to learn on your own (self-study) and how to get help when
you are stuck. To get the most out of the workshop you will have to have
some experience with basic concepts of programming (in any language) like
variables, functions and libraries.

This will be an interactive workshop. Before arriving please:

* pack your laptop and its charger
* [install R and RStudio](#software)
* download the data we will use
* introduce yourself on [the shared notepad](https://public.etherpad-mozilla.org/p/geong-r-and-maps-2016) of the workshop


# Lessons and schedule

1. [Intro to RStudio and basics](lessons/01-getting-started.Rmd) (15minutes)
1. [Structuring your work](lessons/02-getting-organised.Rmd) (20minutes)
1. [Making plots](lessons/03-plotting.Rmd) (60minutes)
1. [What to do when you are stuck](lessons/04-getting-help.Rmd) (15minutes)
1. [Interactive tables, plots and maps](lessons/05-interactive-maps.Rmd) (25minutes)


# Personas, do you recognise yourself?

If you are wondering who this workshop is for take a look at the [personas
of fictional attendees][personas] we created to help design the workshop.

[personas]: https://github.com/wildtreetech/r-and-maps/issues/1


# Learning objectives

At the end of the workshop you will ...

* … be able to create a new project that contains an analysis script
  that takes raw data and produces figures and tables from it without
  modifying the raw data.
* … be able to place markers on an interactive map and share it with
  your colleagues.
* … be able to recognise when you are stuck.
* … know where to find documentation and how to ask good questions to
  maximise your chances of getting help.
* … know that there is no magic: the programs you use are no different
  in principle from those that you build.


# Software

For this workshop will be using R and RStudio. As the workshop is only 3hrs
long you will have to have these installed and working prior to the
workshop. Installing R and RStudio is straightforward: just download and
install the version appropriate for your operating system. If you run into
issues contact Tim: <[tim@wildtreetech.com](mailto:tim@wildtreetech.com)>.

- R: [Windows](https://cran.r-project.org/bin/windows/base/R-3.3.1-win.exe) | [Mac OS X 10.9+ (Mavericks) ](https://cran.r-project.org/bin/macosx/R-3.3.1.pkg) |  [Others](https://cran.r-project.org/)
- RStudio: [Windows](https://download1.rstudio.org/RStudio-0.99.903.exe) | [Mac OS X 10.6+ (Snow Leopard) ](https://download1.rstudio.org/RStudio-0.99.903.dmg) |  [Others](https://www.rstudio.com/products/rstudio/download/)

We will use a few libraries that are not part of R by default. You can install
them by running the following commands in RStudio:

```R
install.packages("ggplot2")
install.packages("rmarkdown")
install.packages("leaflet")
install.packages("DT")
```

Also make sure that your packages are up-to-date by running:

```R
update.packages()
```

# Licence

The materials for this workshop are a remix of several existing projects and
some original work. The existing work that has been remixed:

* [Rhody R stats intro](https://github.com/rhodyrstats/intro_r_workshop) (CC0)
* Software carpentry's [R novice gapminder](https://github.com/swcarpentry/r-novice-gapminder)
  material (CC BY 4.0)

All original work is under the following license:

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">R and maps</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/wildtreetech/ghbd" property="cc:attributionName" rel="cc:attributionURL">Tim Head</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
