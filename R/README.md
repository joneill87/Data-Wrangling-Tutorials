# Quick Start Instructions

The following guide will help you get an R environment up and running to try out the code in this repository

## What is R?

R is a programming language which is primarily used for statistical computing and
data visualisation. R has a huge range of user-contributed packages providing
out-of-the-box solutions for most of your statistical and graphical needs. R is a
specialised language built around the concept of the dataframe (table of data).
Developers who are used to application-oriented languages such as C\#, Java, Python
*etc.*, may find R presents a bit of a learning curve; it's well worth the time
investment, though. In my opinion, as a prototyping language, R beats Python hands-down.
It's an essential tool in any data-wranglers toolbox

## Setting up the Environment

In order to run the code in this repository you'll need to install the R language and
*RStudio*, the IDE for working with R. We'll start by installing the base language.

1. Head over to the Comprehensive R Archive Network (CRAN) [mirror list](https://cran.r-project.org/mirrors.html). 
2. Choose a precompiled binary distribution matching your platform (Windows/Linux/Mac). 
3. Choose *base* rather than *contrib* for a minimal install. 
4. Run the installer and accept the defaults

Next up, we want to install R Studio

1. Go to [https://www.rstudio.com](https://www.rstudio.com) and go to the Download section
2. Choose the free version and download the installer for your platform
3. Run the installer and accept the defaults
4. Run *RStudio* to test that everything installed correctly.

## Running an R Markdown Notebook

RMarkdown (.rmd) is a file format which allows R code to be mixed with markdown for nicely
formatted and presented code. This is particularly important in data wrangling where scripts
are often quite short, but can be dense and difficult to understand without sufficient comments.
Download a [1 Introduction to R.rmd](<1 Introduction to R.rmd>) file from this repository and open it in RStudio.

The majority of the document is written markdown. Markdown is a simple markup language giving you basic formatting capabilities. It's quite intuitive and easy to learn, check out this [cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) for an handy guide.

Code sections are delimited using triple backticks and the name of the language in curly braces *e.g.* \`\`\`{r}. When we build, or *knit*, the notebook, RStudio will run the code block and output the result of the last line of code in the block. 

Let's see R Markdown in action. Just above the script window (top left) there's a ball-of-wool icon. Click this icon to *knit* the notebook into a more readable format. You should be presented with a pop-up asking you to install new packages. Click *yes* to continue. After a few seconds you should be presented with a nicely formatted document.

We can also output the document as a .pdf or .html file. HTML files are handy if you'd like to host your beautiful work online. PDFs can be useful for creating reports *etc.* Note that in order to knit to pdf you'll need to have Latex installed on your computer (specifically MikTex). See [miktex.org](https://miktex.org) for full details. 

I highly recommend using RStudio for all of your R development work. Remember, plain R scripts are for horribly hacked together bits of code that will never see the light of day. If you want to share or show off your work, use markdown!