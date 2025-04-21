This package adapts the primers originally created by Posit for educational use. The package includes modules that primarily encapsulate an introduction to "ggplot2", "dplyr". The code was adapted from that developed by Posit (https://github.com/rstudio-education/primers) though some components may have changed. 

This contains the following tutorials: 

Basics: 
<ol>
 <li>Programming Basics (Programming-Basics)</li>
 <li>Visualization Basics (Visualization-Basics)</li>
</ol>


ggplot2: 
<ol>
  <li>Exploratory Data Analysis (ggplot2-Exploratory-Data-Analysis)</li>
  <li>Bar Charts (ggplot2-Bar-Charts)</li>
  <li>Boxplots (ggplot2-Boxplots)</li>
  <li>Histograms (ggplot2-Histograms)</li>
  <li>Line Plots (ggplot2-Line-Graphs)</li>
  <li>Scatterplots (ggplot2-Scatterplots)</li>
  <li>Overplotting (ggplot2-Overplotting)</li>
  <li>Customizing Plots (ggplot-Customize)</li>
</ol>

Tidy Data: 
<ol>
  <li>Intro to Tidy Data (tidy-Intro-Tidy-Data)</li>
  <li>Joining Datasets (tidy-Join-Datasets)</li>
  <li>Separating and Uniting Columns (tidy-Separate-Columns)</li>
</ol>

dplyr: 
<ol>
  <li>Deriving data (dplyr-deriving)</li>
  <li>Isolating data (dplyr-isolating)</li>
  <li>Working with tibbles (dplyr-tibbles)</li>
</ol>

To install this package: 

First install and load the following packages:
<ol>
<li>tidyverse</li> 
<li>devtools</li>
<li>learnr</li>  
</ol>

Install and load the gradethis package using the following code to install: 
remotes::install_github("rstudio/gradethis")


Then install and load the PositPrimers package (https://github.com/liannesiegel/PositPrimersLinks to an external site.) by using the following code to install:  devtools::install_github("liannesiegel/PositPrimers")

To run a tutorial (e.g. "Programming-Basics"), first make sure the package is loaded then run: 

learnr::run_tutorial("Programming-Basics", "PositPrimers")
