# STAT 215A, Fall 2022

This is the github repository for STAT 215A, Fall 2022.

Thanks to Omer Ronen, James Duncan, Tiffany Tang, Zoe Vernon, Rebecca Barter, and other past GSI's for
sharing their material with me. This document was originally written by Rebecca
for STAT 215A in the Fall of 2017 and has been slightly modified in subsequent
years.

Questions and discussions between students can be posted on Ed Discussions (signup link on bCourses). That way everyone else
can see your questions and the answers, and we don't have to answer the same
questions a million billion times. Preferably you will answer each other's
questions. It is our intention to only jump in when the question is one that
only we can answer.

Please think carefully before asking questions specifically about the projects.
For example, questions concerning how to do something specific in R (e.g. "how
do I convert a list of lists to a long-form data frame?") are fine, but
questions asking what other people did for their analysis are not (e.g. "what
are some findings that people have come across in the Redwood project?").
Questions asking about clarifications are fine.

# Class times

**Lectures**:

Tuesdays & Thursdays, 12:30-2:00pm, Dwinelle 219

**Labs**:

Fridays, 9-11am, Evans 344

(**Office Hours**:)

(*Bin*: TBA)

(*Theo*: Thursday 11:00-12:30pm, Friday 11:00-12:00pm, Evans 444)

# Reading Schedule

- Week 1
  - date: Thu 08/25
    content: "Lecture 1: Introductions"
  - date: Fri 08/26
    content: "Section 0: Git / GitHub + R / Tidyverse"
    assignments:
      - name: "Lab 0: GitHub setup + practice submission"
        due: 09/02
- Week 2
  - date: Tue 08/30
    content: "Lecture 2: Problem Formulation"
    readings:
      - name: "\"The Future of Data Analysis\" (Tukey, 1962) [please skim]"
        url: https://www.jstor.org/stable/2237638
      - name: "\"Science and Statistics\" (Box, 1976)"
        url: https://www.jstor.org/stable/2286841
      - name: "\"Veridical data science\" (Yu and Kumbier, 2020)"
        url: https://www.pnas.org/content/117/8/3920
  - date: Thu 09/01
    content: "Lecture 3: Exploratory Data Analysis (EDA)"
  - date: Fri 09/02
    content: "Section 1: Workflow + Rmd + Latex + R Tricks + Lab 1"
    assignments:
      - name: Lab 0 due
        url:
      - name: "Lab 1: PECARN data assigned"
        due: 09/23 at 11:59pm
- Week 3
  - date: Tue 09/06
    content: "Lecture 4: EDA (Part 2)"
  - date: Thu 09/08
    content: "Lecture 5: EDA (Part 3)"
  - date: Fri 09/09
    content: "Section 2: Advanced visualization techniques"
    
- Week 4
  - date: Tue 09/13
    content: "Lecture 6: Prediction and assessment"
    readings:
      - name: "\"Growth in a Time of Debt\" (Reinhart & Rogoff, 2010)"
        url: "https://pubs.aeaweb.org/doi/pdfplus/10.1257/aer.100.2.573"
      - name: "\"Does high public debt consistently stifle economic growth?\" (Herndon, Ash, & Pollin, 2014)"
        url: "https://academic.oup.com/cje/article-abstract/38/2/257/1714018"
  - date: Thu 09/15
    content: "Lecture 7: Prediction and assessment (Part 2)"
    readings:
      - name: "\"What's Wrong with Social Science and How to Fix It: Reflections After Reading 2578 Papers\""
        url: "https://fantasticanachronism.com/2020/09/11/whats-wrong-with-social-science-and-how-to-fix-it/"
      - name: Principal Component Analyses (PCA)-based findings in population genetic studies are highly biased and must be reevaluated
        url: "https://www.nature.com/articles/s41598-022-14395-4"
      - name: Systematizing Confidence in Open Research and Evidence (SCORE)
        url: "https://www.darpa.mil/program/systematizing-confidence-in-open-research-and-evidence"
  - date: Fri 09/16
    content: "Section 3: TBA"
- Week 5
  - date: Tue 09/20
    content: "Lecture 8: Stability"
    readings:
      - name: "Stability-driven nonnegative matrix factorization to interpret spatial gene expression and build local gene networks (Wu et al. 2016)"
        url: "https://www.pnas.org/content/113/16/4290"
      - name: "\"Funes the Memorious\" (Borges, 1942)"
        url: "http://vigeland.caltech.edu/ist4/lectures/funes%20borges.pdf"
      - name: "\"Algebraic connectivity of graphs\" (Fiedler 1973)"
        url: "http://snap.stanford.edu/class/cs224w-readings/fiedler73connectivity.pdf"
      - name: "\"Normalized Cuts and Image Segmentation\" (Shi and Malik, 2000)"
        url: "https://people.eecs.berkeley.edu/~malik/papers/SM-ncut.pdf"
  - date: Thu 09/22
    content: "Lecture 9: Stability (Part 2)"
  - date: Fri 09/23
    content: "Section 4: TBA"
    assignments:
      - name: Lab 1 due at 11:59pm
- Week 6
  - date: Tue 09/27
    content: "Lecture 10: Stability (Part 3)"
    readings:
      - name: "\"Minimum information about clinical artificial intelligence modeling: the MI-CLAIM checklist\" (Norgeot et al., 2020)"
        url: "https://www.nature.com/articles/s41591-020-1041-y"
      - name: "\"Regression Shrinkage and Selection via the Lasso\" (Tibshirani, 1996)"
        url: "http://www.jstor.org/stable/2346178"
      - name: "\"Ridge Regression: Biased Estimation for Nonorthogonal Problems\" (Hoerl & Kennard, 1970)"
        url: "http://www.jstor.org/stable/1267351"
      - name: "John Platt (1964) “Strong inference”, Science"
        url: "https://science.sciencemag.org/content/146/3642/347/tab-pdf"
      - name: "Rohe, Qin and Yu (2016) on directed spectral clustering, PNAS"
        url: "https://www.pnas.org/content/pnas/113/45/12679.full.pdf"
      - name: "Breiman (1995) paper on non-negative garrote, which motivated Lasso"
        url: "https://www.jstor.org/stable/1269730?seq=1"
      - name: "Elastic net paper by Zuo and Hastie (2005)"
        url: "https://www.jstor.org/stable/3647580?seq=1"
  - date: Thu 09/29
    content: "Section 5: TBA"
  - date: Fri 09/30
    content: "Lecture 11: Stability (Part 4)"
    readings:
      - name: "Garrigues and El Ghaoui (2018) on on-line Lasso"
        url: "http://papers.nips.cc/paper/3431-an-homotopy-algorithm-for-the-lasso-with-online-observations.pdf"
      - name: "Nishimoto et al (2011) on movie reconstruction"
        url: "https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3326357/"
- Week 7
  - date: Tue 10/04
    content: "Lecture 12: Sources of randomness"
    readings:
      - name: "Notes on Ridge Regression by van Wieringen"
        url: "https://arxiv.org/pdf/1509.09169.pdf"
      - name: "UCERF3: A New Earthquake Forecast for California’s Complex Fault System"
        url: "https://pubs.usgs.gov/fs/2015/3009/pdf/fs2015-3009.pdf"
      - name: "Contributions to the mathematical theory of evolution (Pearon 1983)"
        url: "https://royalsocietypublishing.org/doi/10.1098/rsta.1894.0003"
      - name: "\"Remarks on nonparametric estimates of a density function\" Rosenblatt (1956)"
        url: "https://projecteuclid.org/download/pdf_1/euclid.aoms/1177728190"
  - date: Thu 10/06
    content: "Lecture 13: Sources of randomness (Part 2)"
    readings:
      - name: "Saltelli et al (2020) on five ways to ensure models serve society"
        url: "https://www.nature.com/articles/s41599-020-00557-0"
    assignments:
      - name: Lab 2 due at 11:59pm
  - date: Fri 10/07
    content: "Section 6: Introduce Lab 3"
  - date: Sun 10/09
    assignments:
      - name: Lab 2 Peer Review assigned
        due: 10/17 at 11:59pm

- Week 8
  - date: Tue 10/11
    content: "Section 7: TBA"
    assignments:
      - name: Lab 3 assigned
        due: 10/26 at 11:59pm
    readings:
      - name: "Neyman (1923)"
        url: "https://www.jstor.org/stable/2245382"
      - name: "Rubin (1974)"
        url: "http://www.fsb.muohio.edu/lij14/420_paper_Rubin74.pdf"
      - name: "Lin (2013)"
        url: "https://projecteuclid.org/euclid.aoas/1365527200"
      - name: "Freedman book chapter 4: linear regression models"
  - date: Thu 10/13
    content: "Lecture 14: Sources of randomness (Part 3)"
  - date: Fri 10/14
    content: "Lecture 15: Bootstrap. Interpretation."
    readings:
      - name: "Freedman book chapter 5"
      - name: "Risk Analysis of the Space Shuttle: Pre-Challenger"
        url: "https://www.tandfonline.com/doi/abs/10.1080/01621459.1989.10478858"
      - name: "Ali et al (2019) paper on facebook ad process"
        url: "https://arxiv.org/abs/1904.02095"
  - date: Sun 10/16
    assignments:
      - name: Lab 2 Peer Review due at 11:59pm
- Week 9
  - date: Tue 10/18
    content: "Section 8: Midterm review"
  - date: Thu 10/20
    content: "Midterm Exam"
  - date: Fri 10/21 (1-2:30pm)
    content: "Lecture 17: Classification"
- Week 10
  - date: Tue 10/25
    content: "Lecture 16: Bootstrap. Interpretation. (Part 2)"
    assignments:
      - name: Lab 3 due at 11:59pm
  - date: Fri 10/28
    content: "Section 9: Introduce Lab 4"
- Week 11
  - date: Mon 10/31
    assignments:
      - name: "Lab 4: Group Project assigned"
        due: "11/19 at 11:59pm"
  - date: Tue 11/01
    content: "Lecture 18: Inference for logistic regression"
    readings:
      - name: "A Gentle Introduction to Risk-limiting Audits (Lindeman and Stark, 2012)"
        url: "https://www.stat.berkeley.edu/~stark/Preprints/gentle12.pdf"
      - name: "Do-no-harm playbook by Ripley and Kleinfeld (2020)"
        url: "https://electionsos.com/resource/how-to-cover-electoral-conflict/"
      - name: "SPRT Derivation (on bCourses)"
  - date: Thu 11/03
    content: "Lecture 19: Logistic regression, Exponential family"
    readings:
      - name: "Dobson Ch. 3-4"
  - date: Fri 11/04
    content: "Section 9: TBA"
- Week 12
  - date: Tue 11/08
    content: "Lecture 20: Logistic regression, Exponential family (Part 2)"
  - date: Thu 11/10
    content: "Lecture 21: GLMs, Iteratively Reweighted Least Squares"
    readings:
      - name: "D. F. Freedman and D. Lane (1983) \"A Nonstochastic Interpretation of Reported Significance Levels\""
        url: "https://www.jstor.org/stable/1391660"
      - name: "D. F. Freedman (1995) Some issues in the foundation of statistics"
        url: "https://link.springer.com/article/10.1007/BF00208723"
  - date: Fri 11/11
    content: "Section 10: TBA"
    assignments:
      - name: Final Project assigned
        due: "12/10 at 11:59pm"
      - name: "Lab 4 due at 11:59pm"
- Week 13
  - date: Tue 11/15
    content: "Lecture 22: GLMs, Iteratively Reweighted Least Squares (Part 2)"
  - date: Thu 11/17
    readings:
      - name: "Reread: \"Veridical data science\" (Yu and Kumbier, 2020)"
        url: "https://www.pnas.org/content/117/8/3920"
      - name: "Dwivedi et al. (2020) Stable discovery of interpretable subgroups via calibration in causal studies"
        url: "https://arxiv.org/pdf/2008.10109.pdf"
    content: "Lecture 23: Statistical Inference. PCS inference."
  - date: Fri 11/18
    content: "Section 11: Intro to COVID-19 data (guest speaker Tiffany Tang)"
- Week 14
  - date: Tue 11/22
    content: "Lecture 24: Statistical Inference. PCS inference. (Part 2)"
  - date: Thu 11/24
    content: "Thanksgiving Break"
  - date: Fri 11/25
    content: "Thanksgiving Break"
- Week 15
  - date: Tue 11/29
    content: "Lecture 25: Advanced topics"
  - date: Thu 12/01
    content: "Lecture 26: Advanced topics (Part 2)"
  - date: Fri 12/02
    content: "Extra OH"
- Week RRR
  - date: Fri 12/09
    assignments:
      - name: Final Project due at 11:59pm
  


# Class website

bCourses and https://yu-group.github.io/stat-215a-fall-2022/

# Useful resources

The following resources are excellent for both learning R and becoming a more advanced user.

- [R for Data Science](https://r4ds.had.co.nz/), a free online book written by Hadley Wickham and Garrett Grolemund.

- The [tidyverse website](http://www.tidyverse.org/). Much of what makes R powerful is the collection of packages developed by Hadley Wickham and the other lovely people over at RStudio encompassed in a the so-called "tidyverse". The tidyverse website provides a summary of all of its packages. The particularly useful ones will be `ggplot2` and `dplyr`.

- The ["Tidy Data"](https://www.jstatsoft.org/article/view/v059i10/v59i10.pdf) paper by Hadley Wickham will give you a feel for how to effectively mold in R your data for maximizing ease of usefulness. Note that the `reshape2` package is essentially obsolete and have been replaced by the `tidyr` package (part of the tidyverse). Specifically, the functions `melt` and `cast` have been replaced by the more intuitively named functions `gather` and `spread`, respectively.

We will also be using Git and GitHub a lot in this course. Here are some resources for figuring out what Git is and how to use it.

- For information on installing Git and setting up GitHub see their [website](https://github.com/).

- Software Carpentry has a thorough [Git and GitHub tutorial](http://swcarpentry.github.io/git-novice/) available for free.


# The lab assignments

There will be 4-5 lab reports throughout the semester. These reports are a *big deal*. It is in completing these reports that the real learning happens. You will get to apply what you've learned in the lectures and labs to real datasets (with real issues). You will also learn to develop a narrative that reports your scientific findings as accurately and accessibly as possible: you will learn to tell a story with your analysis.

While you are allowed to discuss the projects with one another, each student must work on and hand in their own report. If you do consult with other students, please acknowledge these students in your lab reports. 


[comment]: <> (The current tentative dates for the labs are as follows:)

[comment]: <> (| Project title                  | Date released | Due date                | Peer grade submission date |)

[comment]: <> (|--------------------------------|---------------|-------------------------|----------------------------|)

[comment]: <> (| ER PECARN data cleaning        | September 3   | September 16 &#40;2 weeks&#41; | September 26               |)

[comment]: <> (| Linguistic Survey              | September 24  | October 07 &#40;2 weeks&#41;    | October 17                 |)

[comment]: <> (| Stability of Linguistic Survey | October 12    | October 21 &#40;1.5 weeks&#41;  | &#40;graded by Omer&#41;        |)

[comment]: <> (| *Midterm*                      | October 28    |                         |                            |)

[comment]: <> (| Cloud detection &#40;group project&#41;| October 29 | November 12 &#40;2 weeks&#41;   | &#40;graded by Omer&#41;        |)

[comment]: <> (| ER PECARN data &#40;final project&#41;   | November 13   | December 04 &#40;3 weeks&#41;   | &#40;graded by Omer&#41;        |)



## The reports

Each report will be up to 12 pages (.pdf format) and will contain (1) a description of the problem, (2) a description of the data, (3) a description of the data cleaning procedure, (4) a description of the analytic methods, (5) a description of your results, and (6) relevant visualizations in all five stages.
There is no predetermined structure of the report, and it is entirely free form. There are only a few real requirements:

1. No code is to appear in the final pdf report.

1. Your report must not exceed 12 pages.

1. You must make an effort to communicate effectively. Think as if you are writing a blog post or an informal journal article.

1. The data from each lab comes from an existing research paper, which will be given to you. You must also make an effort to incorporate domain information and knowledge in the writeup to give the report some context. For example, it is good habit to explain in the introduction why your problem is important within the domain, to describe any connections between the statistical models/algorithms and the true phenomenon at hand, and to conclude with a discussion of the impacts of the results within the domain context. Ideally, domain knowledge should be incorporated at all stages of the data science pipeline.

1. Favour simplicity over complexity. It is much more important to be thorough and to communicate effectively than to come up with some super fancy modeling idea that no one understands. If a super fancy is needed or justified, then feel free to go for it.

Keep in mind that there are two types of visualization: *exploratory* and *explanatory*. Exploratory visualizations are graphics that you produce to help *you* understand the data, whereas explanatory visualizations are final versions of a small subset of these figures that you produce to explain to *other people* what is in the data. Typically you will produce many, many exploratory plots and only a few key explanatory plots that answer specific questions. Choose your explanatory plots carefully, and ask the following question of every figure in your report: "Does this figure add anything? Is my story strictly worse when I remove it?" If the answer to either question is "no", then you should remove the figure. Just because you spent a lot of time making a really pretty figure, doesn't mean that it adds anything to your story. There have been many times in my life where I have spent an hour or two making a really awesome plot only to decide the next day that it is actually fairly irrelevant to my main points and removing it.

You will also be submitting your code, and you should write it nicely according to the Google R Style Guide (https://google.github.io/styleguide/Rguide.xml).

## Setting up GitHub for this class

Your report and code will be submitted via GitHub. The following instructions will show you how to set up your GitHub account and configure a repository so that you can submit your assignments. This workflow is shamelessly copied (with slight modifications) from Chris Paciorek and Jarod Millman's setup from STAT243 in 2014.

1. Install Git on your system (https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

1. Sign up for GitHub (https://github.com/).

1. Go to https://education.github.com/ and sign up for the student pack to get unlimited private repositories. You are a "student" and you want an "individual account".

Once you have completed these first steps, you are then ready to create your private GitHub repository for this class.

1. Locally on your machine, clone my stat-215-a repository: `git clone https://github.com/theo-s/stat-215-a`. This will create a copy of the repository on your own computer.

1. On the GitHub website, log in and create a **private** remote repository called *stat-215-a*. Add me (*theo-s*) as a collaborator for this repository (check out settings on the repo website).

1. Back in the terminal, change directories to the stat-215-a folder and set the origin of your local repository to be the remote repository that you just made: `git remote set-url origin https://github.com/USERNAME/stat-215-a.git` (Change USERNAME below to your username). This tells git which remote repository to push your changes to when you `git push`.

1. Edit *info.txt* to reflect your own information.

```
name = "Jane Smith"
SID = "0123456789"
email = "jsmith@berkeley.edu"
github_name = "janesmith"
```

Now you're ready to push to your remote repository for the first time:

1. Check git status `git status`. You should see a bunch of text including `modified:   info.txt`.

1. Add (`git add info.txt`) and commit (`git commit -m “Updated info.txt with my own information”`) your edited *info.txt* file

1. Push your changes to your copy of the remote repository (`git push` or sometimes `git push remote origin`)

1. Check that info.txt has been updated in your remote github repository by navigating to https://github.com/USERNAME/stat-215-a (change USERNAME to your username)

## Submitting your projects

To submit your projects, you will need to create a subfolder in your local `stat-215-a` folder called `lab1` (if you are submitting lab 1). Inside this folder you should have the following (exact) structure:

```
lab1/
  data/
  documents/
  homework.pdf
  lab1.Rmd
  lab1.pdf
  lab1_blind.Rmd
  lab1_blind.pdf
  R/
  other/
```

- The source of your report (with code) will be contained in the `lab1.Rmd` file.

- The compiled version of your report will be contained in `lab1.pdf`.

- You will also submit a "blind" version of each of these documents that does not include your name (`lab1_blind.Rmd` and `lab1_blind.pdf`).

- The `R/` folder will contain any extra R scripts needed to compile your report.

- The `data/` folder will contain any data you use for the lab.

- The `homework.pdf` file will contain your completed homework. Please do not include any irrelevant files.

- The `documents/` folder will contain any relevant papers or documents for the project.

- The `other/` directory can contain additional files needed to reproduce your lab (e.g. .bib files), but try to avoid depending too heavily on this directory.

Note that GitHub cannot host files more than 100 MB. If you try to push a file larger than this, GitHub will cry.

When you are ready, you need to add, commit, and push the `lab1/` folder.

At the time when the lab is due, I will run a script that automatically pulls all of your assignments into my local versions of your `stat-215-a` repositories. Please make sure to submit your labs on time. We will spend some time in the first lab having everyone submit a pretend assignment so that you are all clear on what to do.

## Peer-grading

While you probably did a lot of really cool stuff in your own report, an excellent way to learn about other cool things is to see what other people did! This includes other exploratory and modeling ideas, neat R tricks, and issues with the data that you didn't notice or think of when you were doing your own analysis. So that you each have the opportunity to see a splattering of alternative approaches to the labs, we will be doing peer-grading for this class.

For a couple of the labs, you will each receive 2 reports from your peers to grade. A detailed rubric will be provided and you will be expected to provide both written feedback as well as a numeric grade on a variety of topics including communication, quality of data cleaning, relevance of visualizations, and reproducibility (can you easily re-compile their report). 

After you have all submitted your own assignments (and shortly after the deadline), I will run a script that will automatically push two randomly selected reports into a folder called, e.g., `lab1/peer_review/`. To retrieve your allocated reports, you will need to git pull. You will have one week to review these two reports and return your feedback in the form of a google questionnaire that I will send by email to you all. I will use these two grades for your report as a guide for grading, rather than as a final decision on your grade.

Note that to reproduce your peers' reports, you will have to copy the lab's `data` folder into the folder containing your classmate's `.Rmd` file.

## Frequently asked questions

**Do I have to use R? Can I use Python instead?**

Yes, R is required for several reasons.

1. The ability to embed R code, text and LaTeX formulae in RStudio is excellent and makes reproducibility a breeze.

1. Since we are doing peer reviewing, which includes a code-review, it will be *so* much easier for everyone if we are all using the same language.

**Can I write my report using Jupyter Notebooks?**

No, sorry. One of the ways that we are ensuring that the reports are a reasonable length is to require a 12 page or less length limit. We also don't want to see any code in your final report.

**When should I start working on my lab?**

The labs, if done properly, will take you a long time. Ideally, you should be writing the report simultaneously with your analysis in order to avoid a last minute hacking together of all of your analyses. Do not leave starting the lab until the last minute. You should start as soon as you receive the lab and work on it a little bit every day (rather than in one massive chunk). If you can easily do an entire lab in less than a week, then you have missed a lot in the data cleaning process.

