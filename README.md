# A guide to computational social science resources
A collection of resources and readings for people wanting to get acquainted
with computational social science. This started out as a way for us to collect
resources that we found useful or interesting. 

Credit goes to [@andrewnolanhall](https://github.com/andrewnolanhall) for
pitching the idea at [Data Science Nights@Northwestern](http://www.data-science-nights.org/).
Quoted text is taken directly from the website or document. Suggestions welcome.


## What is it?

[matrix of skills](https://github.com/jduckles/dsskills)

## Syllabi
- Perspectives on Computational Analysis [Syllabus](https://github.com/UC-MACSS/persp-analysis)
- [Computational Social Science](https://css-sise.github.io/), syllabus by
  [Nir Grinberg](https://in.bgu.ac.il/en/Pages/Nir-Grinberg.aspx), Ben-Gurion University
- Very high-level view of what makes up "data science:" [Curriculum Guidelines for Undergraduate Programs in Data Science](https://www.annualreviews.org/doi/full/10.1146/annurev-statistics-060116-053930)

## Training
- Learn R in R: [the `swirl` package](https://swirlstats.com).
- [Fast lane to learning R](https://github.com/matloff/fasteR) by 
[Norman Matloff](https://faculty.engineering.ucdavis.edu/matloff/) (professor
of Computer Science at UC Davis). Self-description:

> This site is for those who know nothing of R, or maybe even nothing of
> programming, and seek QUICK, painless entree to the world of R.

  The course is quite thorough regarding base R, including graphics (**ggplot2**
  is covered as well). NM is a proponent of learning base R first before
  learning third-party packages and I tend to agree.
- [R for Data Science](http://r4ds.had.co.nz/) by Garret Grolemund and Hadley
Wickham. The authors are important originators of/contributors to the so-called
"tidyverse", a collection of packages for R. These packages tend make things
easier (especially for automated workflows). However, starting out with the
"tidyverse" when learning R is, in my opinion, a bit like learning to run
before learning to walk.
- [Starting from zero](https://datacarpentry.org/r-socialsci/), Data Carpentry
workshop. These resources are intended for in-person workshops but can be used
by self-learners.

  > This is an introduction to R designed for participants with no programming
  > experience. These lessons can be taught in a day (~ 6 hours). They start
  > with some basic information about R syntax, the RStudio interface, and move
  > through how to import CSV files, the structure of data frames, how to deal
  > with factors, how to add/remove rows and columns, how to calculate summary
  > statistics from a data frame, and a brief introduction to plotting.
	
- [Data Science Course in
  a Box](datasciencebox.org ) ([Course materials](https://github.com/rstudio-education/datascience-box))
  by [Mine Cetinkaya-Rundel](https://www2.stat.duke.edu/~mc301/) for RStudio.
  Primarily intended for teachers but might be valuable for self-learners too.
  Self-presentation:

  > Data Science in a Box contains the materials required to teach (or learn
  > from) an introductory data science course using R, all of which are
  > freely-available and open-source. They include course materials such as
  > slide decks, homework assignments, guided labs, sample exams, a final
  > project assignment, as well as materials for instructors such as
  > pedagogical tips, information on computing infrastructure, technology
  > stack, and course logistics.
  > 
  > See datasciencebox.org for everything you need to know about the project!

- [R for Stata users](http://r4stats.com/books/r4stata/), for people coming
  from **Stata** and wanting to learn **R**. An earlier draft is available for
  free. This book is structured somewhat similarly to the O'Reilly Cookbooks,
  i.e. it is a laundry list of problems or situations for which solutions are
  given in both Stata and R. If your particular problem is among those covered,
  great! If not, you won't get around learning the basics of R and translating
  Stata logic into R logic yourself.
- [Chromebook Data Science project](http://jhudatascience.org/chromebookdatascience/cbds.html)
  > Chromebook Data Science (CBDS) is an online educational program to help
  > anyone who can read, write, and use a computer to move into data science.>
  > It is offered by faculty members in the Johns Hopkins Department of
  > Biostatistics, Johns Hopkins Bloomberg School of Public Health. There are
  > currently 12 courses that are offered in the Chromebook Data Science
  > Curriculum.
- [UK Data Service Data Skills Modules](https://www.ukdataservice.ac.uk/use-data/data-skills-modules)

  > These introductory level interactive modules are designed for users who
  > want to get to grips with keys aspects of survey, longitudinal and
  > aggregate data.
- [The BBC's visual and data journalism cookbook for R](https://bbc.github.io/rcookbook/), [Blog post announcing and explaining the launch of the BBC's visual and data journalism cookbook in R](https://medium.com/bbc-visual-and-data-journalism/how-the-bbc-visual-and-data-journalism-team-works-with-graphics-in-r-ed0b35693535)
- [SciPy Lecture Notes](www.scipy-lectures.org)
  > Tutorials on the scientific Python ecosystem: a quick introduction to
  > central tools and techniques. The different chapters each correspond to a
  > 1 to 2 hours course with increasing level of expertise, from beginner to
  > expert.

## Readings
### Practical advice
"How to name files," Jenny Bryan's [speaker deck](https://speakerdeck.com/jennybc/how-to-name-files)

"Project structure & Naming files," Danielle Navarro (inspired by Jenny Bryan), [slides](https://slides.djnavarro.net/project-structure/)

Version control in R:

- [Collaborating in Git and Github](https://www.sds.pub/collaborating-with-git-and-github.html)
- [How to use Git/Github from R/Rstudio](https://rfortherestofus.com/2021/02/how-to-use-git-github-with-r/)
- [Github](https://rstudio-conf-2020.github.io/r-for-excel/github.html)

["starting R markdown,"](https://www.youtube.com/playlist?list=PLRPB0ZzEYegM86awo590bP1MJjQbjdR9E),
a YouTube tutorial playlist by [Danielle Navarro](https://djnavarro.net/)

### General
[Matthew Sagalnik, _Bit by bit_](https://www.bitbybitbook.com/en/1st-ed/preface/) (free version)

[Matthew Sagalnik, _Bit by bit_](https://press.princeton.edu/titles/11057.html) (tree version)

[Bernard E. Harcourt, _Against Prediction_](https://www.press.uchicago.edu/ucp/books/book/chicago/A/bo4101022.html) (tree version) Summary: _Against Prediction_ argues that predictive policing models not “crime” but “arrests”, i.e. police behavior, not the supposed underlying behavior (not what crimes will happen where, but who will be arrested). Therefore, it will reinforce existing trends in policing instead of “improving” policing.

[Bernard E. Harcourt, _Against Prediction_](http://papers.ssrn.com/sol3/papers.cfm?abstract_id=756945) (working paper)

[Bernard E. Harcourt, _Against Prediction_](http://bactra.org/reviews/against-prediction/) (review by Cosma Shalizi)

[Thoughts on algorithmic fairness](http://joshualoftus.com/post/algorithmic-fairness-is-as-hard-as-causation/): "Algorithmic fairness is an interdisciplinary research field concerned with the various ways that algorithms may perpetuate or reinforce unfair legacies of our history, and how we might modify the alorithms or systems they are used in to prevent this. For example, if the training data used in a machine learning methods contains patterns caused by things like racism, sexism, ableism, or other types of injustice, then the model may learn those patterns and use them to make predictions and decisions that are unfair. There are many ways that technology can have unintended consequences, and this is just one of them."

### Methods
[Claus Witte, _Fundamentals of Data Visualization_](https://serialmentor.com/dataviz/)

[Claus Witte, _Fundamentals of Data Visualization_](https://github.com/clauswilke/dataviz) (R markdown source)

[Kieran J. Healy, _Data Visualization - A practical introduction_](http://socviz.co/)

[Garret Grolemund, Hadley Wickham, _R for Data Science_](http://r4ds.had.co.nz/)

[Quartz guide to real world data munging problems](https://github.com/Quartz/bad-data-guide)

[Data cleaning in R needn't be hard](https://github.com/Cghlewis/R-Ladies-STL-Cleaning-Data-R) - presentation materials by [Crystal Lewis](https://twitter.com/Cghlewis)

### Ethics
[_Bit by bit_, ch. 6](https://www.bitbybitbook.com/en/1st-ed/ethics/)

Fairness definitions and their politics: [presentation by Arvind Narayanan, video](https://www.youtube.com/watch?v=jIXIuYdnyyk), [presentation by Arvind Narayanan, text](https://docs.google.com/document/d/1bnQKzFAzCTcBcNvW5tsPuSDje8WWWY-SSF4wQm6TLvQ/edit), [article by Verma and Rubin, pdf](www.ece.ubc.ca/~mjulia/publications/Fairness_Definitions_Explained_2018.pdf)

[Notes from @DynamicWebPaige on Google's ML Fairness course](https://github.com/dynamicwebpaige/info/blob/master/blog/online_courses/20-10-2018_AI_Ethics.md)

### Neural Networks
[Learning Neural Networks](http://neuralnetworksanddeeplearning.com/index.html)


## Data sets and sources
[Inter-university Consortium for Political and Social research](https://www.icpsr.umich.edu/web/pages/ICPSR/index.html) - A data repository for mostly survey data. North America-centric.

[Cross-national equivalent file](https://www.cnefdata.org/) - The Cross-National Equivalent File (CNEF) project harmonizes a subset of the data found on seven panel data sets collected in Australia, Canada, China, Germany, Korea, Russia, Switzerland, UK, and US.

[Urban Institute Data Catalogue](https://datacatalog.urban.org/search/type/dataset), [UIDC announcement and short presentation](https://medium.com/@urban_institute/announcing-the-urban-institute-data-catalog-ce2c787e38e9)

[Google tool for finding datasets](https://toolbox.google.com/datasetsearch)

[Cook County Open Data portal](https://datacatalog.cookcountyil.gov/)
 
[Cook County Open Data - State Attorney (e.g. arrest data)](https://datacatalog.cookcountyil.gov/browse?tags=state%27s%20attorney%20case-level)

[Wesleyan Media Project](http://mediaproject.wesleyan.edu/): "The Wesleyan Media Project tracks and analyzes all broadcast advertisements aired by or on behalf of federal and state election candidates in every media market in the country."

[The Stanford Open Policing Project](https://openpolicing.stanford.edu/): "Our team is gathering, analyzing, and releasing records from millions of traffic stops by law enforcement agencies across the country."

[The @unitedstates project](https://theunitedstates.io/) Scrapers and parsers for many aspects regarding Congress, e.g. bios of members past and present, data about bills and roll call votes, district shapefiles, and much more.

[Congressional record parser](https://github.com/unitedstates/congressional-record): "This tool converts HTML files containing the text of the Congressional Record into structured text data. It is particularly useful for identifying speeches by members of Congress."

[Pew Research survey data](https://www.pewresearch.org/download-datasets/)


### People, groups, hashtags
[List of sociologists on twitter, by Philip N. Cohen](https://twitter.com/familyunequal/lists/sociologists)

[List of demographers on twitter, by Conrad Hacket](https://twitter.com/i/lists/73400160)

[List of demographers on twitter, by Cameron Campbell](https://twitter.com/i/lists/1292729810804850690)

`#rladies`

`#rstats`

[R Animated Gifs](https://twitter.com/i/moments/1065910383670685696)

[The Data Science job market is saturated](https://veekaybee.github.io/2019/02/13/data-science-is-different/)

[Cheatsheet - Neural networks/maching learning](https://becominghuman.ai/cheat-sheets-for-ai-neural-networks-machine-learning-deep-learning-big-data-678c51b4b463)


## Similar collections
[R for the rest of use, Resources](https://rfortherestofus.com/resources/)

[R resources collection, NU Research Computing Services](https://github.com/nuitrcs/rworkshops)

[Python resources collection, NU Research Computing Services](https://github.com/nuitrcs/pythonworkshops)

[OpenIntro, free textbooks](https://twitter.com/OpenIntroOrg)


## DataCamp
Following recent events at [DataCamp](https://www.datacamp.com) ([here](https://blog.rladies.org/post/statement-about-datacamp/), [here](https://www.buzzfeednews.com/article/daveyalba/datacamp-sexual-harassment-metoo-tech-startup), [here](https://www.datacamp.com/community/blog/apology), [here](https://www.datacamp.com/community/blog/board-update)), this guide prefers to recommend other resources. The course offer is, however, comprehensive, and Northwestern University students benefit from a special offer.
