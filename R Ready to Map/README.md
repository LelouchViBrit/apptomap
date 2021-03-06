---
title: "R Ready to Map: Getting Started"
output: html_notebook
---

# R Ready to Map

## Tutorial Purpose
The purpose of this tutorial is to help those with with a varieties of experiences in R, ranging from complete beginner to advanced, to learn how to
write code to collect tweets using the rtweet package and to display tweets on a basic
interactive map using Leaflet for R, an R mapping package.
By the end of this tutorial, one should be able to know how to do a one-time collection of
tweets and a collection of tweets based on what people are tweeting in real time for a
specified time period. This tutorial is focused more on getting the task done as opposed
to going in-depth into data science, R, the particulars of the Twitter API and so on. This tutorial is divided into three units:

Unit 1: Collecting Twitter Data. In this unit, you will learn how to do a one-time collection of tweets and a collection of tweets happening in real-time. You'll also learn some other useful things that the rtweet package offers.

Unit 2: Mapping Twitter Data. In this unit, you will learn how to map Twitter data using the Leaflet for R package.

Unit 3: Creating an Interactive document. In this unit, you will learn how to create an RMarkdown document and integrate elements such as a leaflet map and plots.

## Main Scenario 
<i> You decided to make a life change and and decided to get into the food truck business. You had this idea of having a food truck named "Oishii Ramen" (oishii means tasty in Japanese) which would serve ramen, dumplings, and bubble tea.  Miraculously, you were able to raise enough money to buy a food truck through crowdfunding and some kind investors (family members), but you still have a limited budget. You decided that you would rely on social media to advertise your business. Being a new business owner, you feel overwhelmed with the task at hand. Where do you begin?</i>

## Terms to Know
<b>RStudio</b>: The IDE that is used for the R programming language. 

<b>IDE</b>:  Integrated Development Environment. It is an application that includes a code debugger, a compiler, and code editor so you can write your code. 



## Where to Start?
You found out about this extremely cool programming language called R. You also found out that RStudio is a handy way to deal with your code. 


1. If you already haven't, download and install the latest version of [R](https://www.r-project.org/). 

2. Download and install [R Studio](https://www.rstudio.com/).

3. Open up RStudio. Once you've done that, you need to install the rtweets package.

```{r, chunk-one, echo = TRUE, eval = FALSE}
install.packages("rtweet") #Allows you to download and install the package to your library.
library("rtweet") #Adds the rtweets package to R so you are able to use it!

```


If you have opened this notebook within RStudio, then you can run the above code chunk by clicking the green arrow on the far right of the code chunk, putting your cursor in the code chunk and pressing *Ctrl+Shift+Enter*. You know this is a code chunk indicated by the three "```{r}". In the parenthesis, "r indicates the program langauge being used, "chunk-one" indicates the name of the code segment(you can name each code segement whatever name you like), "echo = TRUE" means that the actual code is being displayed, and "eval = FALSE" means NOT to run the code in the chunk. The default of eval is TRUE, but I do not want the code to run immedately! More information about code chunks will be in Unit 3 on creating RMarkdown documents.

4. Make sure to set your working directory before you start coding. You can do this by going to session -> Set Working Directory and choose the location of your choice. I would recommend to set it to the project directory. You can also do this by simply typing:
```{r, chunk-two, echo = TRUE, eval = FALSE}
setwd('~/')
```

I have posted three presentations that gives a general gist of the units on GitHub. You can download them as HTML presentation by saving them. You can do this by clicking on "View Raw" and then right-click and choose "Save As." For those who have issues with downloading or viewing the presentations, I published the presentations on RPubs:
- [Unit 1: Collecting Twitter Data](http://rpubs.com/momiji15/374922)
- [Unit 2: Mapping Twitter Data](http://rpubs.com/momiji15/374923)
- [Unit 3: Creating Dynamic Documents](http://rpubs.com/momiji15/376043)

## Examples 
Here are example documents that were made for the course.
### Unit 3
  - Creating an R Markdown Document: [Food Truck Report for Investors](http://rpubs.com/momiji15/375864)
  - Creating an R Markdown Presentation: [Food Truck Presentation](http://rpubs.com/momiji15/375887)

Feel free to message me if you have any issues with any of the materials!

# Use of Course Materials
Please feel free to use these course materials for your personal use or to integrate in your class or workshop, but please give credit where it's due. A lot of hard work went into making this course! :).

# References
Kearney MW (2018). rtweet: Collecting Twitter Data. R package version 0.6.7, https://cran.r-project.org/package=rtweet.


