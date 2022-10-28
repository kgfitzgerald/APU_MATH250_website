---
title: "MATH 250 Final Project"
---

## Timeline

Choose project teams by **Tuesday, October 4**

Project Work Session 1: **Tuesday, October 4**

Proposal due **Wednesday, October 12**

Project Work Session 2: **Thursday, October 13**

Project Work Session 3: **Thursday, October 27**

Data cleaning & preliminary EDA due **Thursday, October 27**

Project Work Session 4: **Thursday, November 10**

Draft report due **Thursday, November 17** 

In-class Peer Review  **Thursday, December 1**

Peer feedback due **Tuesday, December 6**

Project Work Session 5: **Thursday, December 8**

Final written report due **Saturday, December 10** 

Presentation: **TBD (during Final Exam time slot Dec 12 - 16)**

## Introduction & grading summary

**TL;DR**: *Pick a dataset and do something with it. That is your 
final project.*

The purpose of the final project is to apply what you’ve learned throughout the semester to investigate an interesting data-driven research question by analyzing a real-world dataset of your choosing. 

The project will be completed in self-assigned teams of 2-3. You should choose a dataset for your project based on your group's interests. The goal of this project is for you to demonstrate proficiency in the techniques we have covered in this class (and beyond, if you like!) and apply them to a dataset to analyze it in a meaningful way. 

### Logistics

You should sign up for a team of 2-3 on Canvas no later than **Tuesday, October 4**. 

The four primary deliverables for the final project are

- A written, reproducible report detailing your analysis
- An RStudio Cloud project repository corresponding to your report
- An oral presentation during finals week
- Formal peer review on another team's project

### Grading summary

The grade breakdown is as follows:

Total                                                   | 100 pts
--------------------------------------------------------|--------
**Project proposal**                                    | 5 pts
**Preliminary EDA**                                     | 5 pts
**Rough Draft**                                    | 5 pts
**Written report**                                      | 45 pts
**Project repo & reproducibility**                      | 10 pts
**Peer feedback**                                       | 5 pts
**Slides**                                              | 10 pts
**Oral presentation**                                   | 15 pts

**<i>Note: No late projects are accepted.</i>**

## Data sources

In order for you to have the greatest chance of success with this project it is important that you choose a manageable dataset. This means that the data should be readily accessible and large enough that multiple relationships can be explored. Your dataset must have **at least 500 observations and at least ten variables (or has been approved by Dr. Fitz)**. The dataset should include a rich mix of categorical, discrete numeric, and continuous numeric data. 

**Data sets that can't be used:** 

- Data sets that have been used for class examples or assignments. 
- Data sets from Kaggle.
- Data sets analyzed in another course.

No two groups can analyze the same dataset, so I encourage you to be creative! 

Some resources that may be helpful:

- [R Data Sources for Regression Analysis](https://rfun.library.duke.edu/blog/data-sources-for-regression-analysis/)
- [FiveThirtyEight data](https://data.fivethirtyeight.com/)
- [TidyTuesday](https://github.com/rfordatascience/tidytuesday)


Additional options:

- [World Health Organization](https://www.who.int/gho/database/en/)
- [The National Bureau of Economic Research](https://data.nber.org/data/)
- [International Monetary Fund](https://data.imf.org/?sk=388DFA60-1D26-4ADE-B505-A05A558D9A42&sId=1479329328660)
- [General Social Survey](http://gss.norc.org/)
- [United Nations Data](http://data.un.org/)
- [United Nations Statistics Division](https://unstats.un.org/home/)
- [U.K. Data](https://data.gov.uk/)
- [U.S. Data](https://www.data.gov/)
- [U.S. Census Data](https://www.census.gov/data.html)
- [European Statistics](https://ec.europa.eu/eurostat/)
- [Statistics Canada](https://www.statcan.gc.ca/eng/start)
- [Pew Research](https://www.pewresearch.org/download-datasets/)
- [UNICEF](https://data.unicef.org/)
- [CDC](https://www.cdc.gov/datastatistics/index.html)
- [World Bank](https://datacatalog.worldbank.org/)
- [Election Studies](https://electionstudies.org//)

All analyses must be done in RStudio, and your final written report and 
analysis **must be reproducible**. This means that you must create an R Markdown document attached to a RStudio project repository that will create your written report exactly upon knitting.

## Project proposal 

There are two main purposes of the project proposal:

- To help you think about the project early, so you can get a head start on finding data, reading relevant literature, thinking about the questions you wish to answer, etc.
- To ensure that the data you wish to analyze, methods you plan to use, and the scope of your analysis are feasible and will help you be successful for this project.

Choose **three** substantially different datasets you are interested in analyzing. For each dataset, include the following 3 sections in the proposal: 

### Data description & background

- Identify the source of the data, 
- When and how it was originally collected (by the original data curator, not necessarily how you found the data), and 
- Provide a brief description of the observations 

### Research question

- Describe the research topic along with a concise statement of the research question and hypotheses.

### Data set

- Use the `glimpse` function to provide a glimpse of the data set.

- Place the file containing your data in the `data` folder of the project repo. 

### Submission 

Submit the PDF of your proposal on Canvas by midnight on **Wednesday, October 12**. I will provide feedback on your proposal to help you determine a data set to use for the project. 

### Notes 

- Project proposals should have no more than 1-2 pages of **text** (not including the output from `glimpse`). That is, be concise!
- You **must** use one of the data sets in the proposal for the final project, unless instructed otherwise by Dr. Fitz. 

### Proposal grading 

The project proposal will be graded as follows:

Total                                                   | 5 pts
--------------------------------------------------------|-------
**Data description/background**                                   | 2 pts
**Research questions**                                  | 2 pts
**Results**                                             | 1 pts

## Data cleaning & Preliminary EDA

The purpose of this step is to help scaffold steady progress and give you an opportunity to get early feedback on your analysis plan. The `cleaning-eda.Rmd` file in your RStudio Cloud repo should include reproducible data cleaning steps that begin with reading in your original data file and outputting the data file used for analysis. You should also include preliminary exploratory data analysis and a brief description of your analysis plan. This will be evaluated through RStudio Cloud; you do not need to submit this on Canvas. 

Your cleaning & EDA steps should include:

+ Cleaning variable names

+ Converting to appropriate data types (factors, dates, etc) 

+ Re-ordering factor levels as needed

+ Investigating and handle missing data

+ Visualizing each variable (or at least 10 if you have a large number), noting any issues or notable features

+ Describing your analysis plan for answering your research question

    + What types of visualizations or summary tables will you create?

    + What types of models or inference procedures will you run, if any? 

You should save the clean data as a .RDS file. 

This part of the project will be graded as follows:

Total                                                   | 5 pts
--------------------------------------------------------|-------
**Original & cleaned datasets included**                | 1 pt
**Reproducible data cleaning**                          | 2 pts
**EDA**                                                 | 1 pt
**Future analysis plan**                                | 1 pt

## Rough Draft report 

The purpose of the rough draft and peer review is to give you an opportunity to get feedback on your analysis before the final product. 

Your team will write the rough draft in the `written-report.Rmd` file in your project repo and submit the pdf or html to Canvas. 

Below is a brief description of the sections to focus on in the draft: 

#### Introduction and data

The introduction provides motivation and context for your research. Describe your topic (citing sources) and provide a concise, clear statement of your research question and hypotheses.

Then, identify the source of the data, when and how it was collected, the cases, a general description of relevant variables.

#### Methodology 

The methodology section should include visualizations and summary statistics relevant to your research question. You should also justify the choice of statistical method(s) used to answer your research question.

#### Results 

Showcase how you arrived at answers to your research question using the
techniques we have learned in class (and beyond, if you’re feeling adventurous).

Provide only the main results from your analysis. The goal is not to do an exhaustive data analysis (calculate every possible statistic and perform every possible procedure for all variables). Rather, you should demonstrate that you are proficient at asking meaningful questions and answering them using data, that you are skilled in interpreting and presenting results, and that you can accomplish these tasks using R. More is not better.

As you work on the draft, the focus should be on the analysis and less on crafting the final report. **Your draft must include a reasonable attempt at each analysis component - exploratory data analysis, inference or modeling, and deriving initial results and conclusions.**

This part of the project will be graded as follows:

Total                                                   | 5 pts
--------------------------------------------------------|-------
**Introduction & Data**                                 | 1 pt
**Methodology**                                         | 1 pts
**Results**                                             | 1 pt
**Neatness & Organization**                             | 2 pt


## Peer review

Critically reviewing others' work is a crucial part of the scientific process, and giving constructive feedback is an important skill that must be practiced. The process can enhance your ability to self-assess and improve your own work as well.

You will be assigned a team to review. Time will be spent on peer review in class on **Thursday, December 1**, and your team will have until class-time on **Tuesday, December 6** to provide a detailed critique about the written report and data analysis. This feedback is intended to help you create a high quality final project, as well as give you experience reading and constructively critiquing the work of others.

Peer feedback will be graded on the extent to which it comprehensively and constructively addresses the components of the partner team's report: the research context and motivation, exploratory data analysis, and any inference, modeling, or conclusions. 

## Written report

Your final report must be written using R Markdown. All team members must contribute meaningfully to the analysis and are responsible for what's contained in the final report. Before you finalize your report, make sure the printing of code chunks is turned off with the option `echo = FALSE`.


**Submit the final report on Canvas under the <i>Final Report & Repo</i> assignment.** Your final report must match your RStudio Cloud repository *exactly*. The mandatory components of the report are below. You are free to add additional sections as necessary. The report, including visualizations, should be **no more than 10 pages long.** There is no minimum page requirement; however, you must comprehensively address all of the aspects mentioned below.

The written report is worth 45 points, broken down as follows:

Total                                                   | 45 pts
--------------------------------------------------------|-------
**Introduction/data**                                   | 5 pts
**Methodology**                                         | 10 pts
**Results**                                             | 15 pts
**Discussion**                                          | 10 pts
**Formatting**                                          | 5 pts

#### Introduction and data

The introduction provides motivation and context for your research. Describe your topic (citing sources) and provide a concise, clear statement of your research question and hypotheses.

Then identify the source of the data, when and how it was collected, the cases, a general description of relevant variables.

#### Methodology 

The methodology section should include visualizations and summary statistics relevant to your research question. You should also justify the choice of statistical method(s) used to answer your research question.

#### Results 

Showcase how you arrived at answers to your research question using the
techniques we have learned in class (and beyond, if you’re feeling adventurous).

Provide only the main results from your analysis. The goal is not to do an exhaustive data analysis (calculate every possible statistic and perform every possible procedure for all variables). Rather, you should demonstrate that you are proficient at asking meaningful questions and answering them using data,  that you are skilled in interpreting and presenting results, and that you can  accomplish these tasks using R. More is not necessarily better.

#### Discussion

This section is a conclusion and discussion. This will require a summary of what you have learned about your research question along with statistical arguments supporting your conclusions. You should critique your own methods and provide suggestions for improving your analysis and future work. Any potential issues pertaining to the reliability and validity of your data and the appropriateness of the statistical analyses should also be discussed. Additionally, include a brief paragraph on ideas for future work.

### Formatting

This is an assessment of the overall presentation and formatting of the written report.

## Slides + Oral Presentation

### Slides 

In addition to the write-up, your team must also create presentation
slides that summarize and showcase your project. Introduce your research question and dataset, showcase visualizations, and provide some conclusions. These slides should serve as a brief visual accompaniment to your write-up and will be graded for content and quality. The slides are due on Canvas by the time of the presentation during finals week.

Here is a *<u>suggested</u>* outline as you think through the slides; you do *<u>not</u>* have to use this exact format for the slide deck.

- Title Slide
- Slide 1: Introduce the topic and motivation
- Slide 2: Introduce the data
- Slide 3 - 4: Highlights from EDA
- Slide 4 - 5: Inference / modeling
- Slide 6: Conclusions + future work


### Oral presentation

During our final exam time slot, your group will give an oral presentation of your project. While all members are expected to contribute to the presentation and are responsible for the final product, not all group members must present. Feel free to leverage the individual strengths of your team members. For example, one person may excel in written communication, another in visual communication, and another in oral communication. Not all roles need to be shared equally among all team members so long as the overall work load is distributed fairly. 

The oral presentation should be approximately 10-12 minutes, with about 5 minutes for questions. 

## Project repository

All written work (with exception of presentation slides) should be reproducible, and the RStudio project repo should be neatly organized. 

The repo should have the following structure:

- `README`: Short project description and data dictionary
- `written-report.Rmd` & `written-report.pdf`
- `/data`: Folder that contains the data set for the final project.
- `project-proposal.Rmd` & `project-proposal.pdf`
- `/presentation`: Folder with the presentation slides. 
  - If your presentation slides are online, you can put a link to the slides in a `README.md` file in the `presentation` folder.
  
Points for reproducibility + organization will be based on the reproducibility of the written report and the organization of the project  repo. The repo should be neatly organized as described above, there should be no extraneous files, all text in the README should be easily readable.

## Peer teamwork evaluation

You will be asked to fill out a survey where you provide feedback on your team dynamic & your team members contributions, and self-assess your own contributions. 

## Grading details

Grading of the project will take into account the following:

- Content - What is the quality of research and/or policy question and relevancy of data to those questions?
- Correctness - Are statistical procedures carried out and explained correctly?
- Writing and Presentation - What is the quality of the statistical presentation, writing, and explanations?
- Creativity and Critical Thought - Is the project carefully thought out? Are the limitations carefully considered? Does it appear that time and effort went into the planning and implementation of the project?

A general breakdown of scoring is as follows:

- *90%-100%*: Outstanding effort. Students understand how to apply all statistical 
concepts, can put the results into a cogent argument, can identify weaknesses in 
the argument, and can clearly communicate the results to others.
- *80%-89%*: Good effort. Students understand most of the concepts, put together 
an adequate argument, identify some weaknesses of their argument, and communicate 
most results clearly to others.
- *70%-79%*: Passing effort. Students have misunderstanding of concepts in several 
areas, have some trouble putting results together in a cogent argument, and communication 
of results is sometimes unclear.
- *60%-69%*: Struggling effort. Students are making some effort, but have misunderstanding 
of many concepts and are unable to put together a cogent argument. Communication 
of results is unclear.
- *Below 60%*: Students are not making a sufficient effort.

## Late work policy

**There is no late work accepted on this project.** Be sure to turn in your work early to avoid any technological mishaps.

## Additional notes and tips

The project is very open ended. For instance, in creating a compelling 
visualization(s) of your data in R, there is no limit on what tools or 
packages you may use. You do not need to visualize all of the data at once. A single high quality visualization will receive a much higher grade than a large number of poor quality visualizations.


### Tips

- Ask questions if any of the expectations are 
unclear.

- *Code*: In your write up your code should be hidden (`echo = FALSE`) so that your document is neat and easy to read. However, your document should include all your code such that if I re-knit your .Rmd file I should be able to obtain the results you presented. 
  - **Exception:** If you want to highlight something 
specific about a piece of code, you're welcome to show that portion. 
- Make sure each team member is contributing, both in terms of quality and quantity of contribution.
- All team members are expected to contribute equally to the completion of this assignment and group assessments will be given at its completion - anyone judged to not have sufficient contributed to the final product will have their grade adjusted accordingly. While different teams members may have different backgrounds and strengths, it is the responsibility of every team member to understand how and why all code and approaches in  the assignment works.
- Finally, pay attention to details in your write-up and presentation. Neatness, coherency, and clarity will count.

### Formatting + communication 

#### Suppress Code, Warnings, & Messages

- Include the following code in a code chunk at the top of your .Rmd file to suppress all code, warnings, and other messages. Use the code chunk header `{r set-up, include = FALSE}` to suppress this set up code. 


```r
knitr::opts_chunk$set(echo = FALSE,
                      warning = FALSE, 
                      message = FALSE)
```

#### Headers

- Use headers to clearly label each section. Make sure there is a space between the last `#` and the title, so the header renders correctly. For example, `###Section Title` will not render as header, but `### Section Title` will. 

#### References 

- Include all references in a section called "References" at the end of the report. 
- This course does not have specific requirements for formatting citations and references.
- See [Section 4.5](https://bookdown.org/yihui/rmarkdown-cookbook/bibliography.html) of the R Markdown Cookbook to learn about the citation functionality in R Markdown. 

#### Appendix

- If you have additional work that does not fit or does not belong in the body of the report, you may put it at the end of the document in section called "Appendix". 
- The items in the appendix should be properly labeled. 
- The appendix should only be for additional material. The reader should be able to fully understand your report without viewing content in the appendix.

#### Resize figures

- Resize plots and figures, so you have more space for the narrative. 
    - **Resize individual figures**: Use the code chunk header `{r plot1, fig.height = 3, fig.width = 5}`, replacing `plot1` with a meaningful label and the height and width with values appropriate for your write up.
    - **Resize all figures**: Include the `fig_width` and `fig_height` options in your YAML header as shown below:

```
---
title: "Your Title"
author: "Team Name + Group Members"
output: 
  pdf_document:
    fig_width: 5
    fig_height: 3
---
```
 
Replace the height and width values with values appropriate for your write up.

#### Arranging plots

Arrange plots in a grid, instead of one after the other. This is especially useful when displaying plots for exploratory data analysis and to check assumptions. 

- If you're using ggplot2 functions, the `patchwork` package makes it easy to arrange plots in a grid. See the documentation and examples [here](https://patchwork.data-imaginist.com/).

- If you're using base R function, i.e. when using the `emplogit` functions, put the code `par(mfrow = c(rows,columns))` before the code to make the plots. For example, `par(mfrow = c(2,3))` will arrange plots in a grid with 2 rows and 3 columns.

#### Plot titles and axis labels

Be sure all plot titles and axis labels are visible and easy to read. 

- Use informative titles, <u>not</u> variable names, for titles and axis labels.
- Use `coord_flip()` to flip the *x* and *y* axes on the plot. This is useful if you a bar plot with an x-axis that is difficult to read due to overlapping text. 

❌ **NO! The x-axis is hard to read because the names overlap.**


```r
ggplot(data = mpg, aes(x = manufacturer)) +
  geom_bar()
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-3-1.png" width="672" />

✅ **YES! Names are readable**


```r
ggplot(data = mpg, aes(x = manufacturer)) +
  geom_bar() +
  coord_flip()
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-4-1.png" width="672" />

#### Do a little more to make the plot look professional!

- Informative title and axis labels
- Flipped coordinates to make names readable
- Arranged bars based on count
- Capitalized manufacturer names
- *Optional: Added color - Use a coordinated color scheme throughout paper / presentation*
- *Optional: Applied a theme - Use same theme throughout paper / presentation*


```r
mpg %>%
  count(manufacturer) %>%
  mutate(manufacturer = str_to_title(manufacturer)) %>%
  ggplot(aes(x = fct_reorder(manufacturer,n), y = n)) +
  geom_bar(stat = "identity", fill = "steelblue") +
  coord_flip() +
  labs(x = "Manufacturer", 
       y = "Count", 
       title = "The most common manufacturer is Dodge") +
  theme_bw() 
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-5-1.png" width="672" />


#### Tables and model output

- Use the `kable` function from the knitr package to neatly output all tables and model output. This will also ensure all model coefficients are displayed. 
  - Use the `digits` argument to display only 3 or 4 significant digits. 
  - Use the `caption` argument to add captions to your table. 



```r
model <- lm(mpg ~ hp, data = mtcars)
tidy(model) %>%
  kable(digits = 3)
```



|term        | estimate| std.error| statistic| p.value|
|:-----------|--------:|---------:|---------:|-------:|
|(Intercept) |   30.099|     1.634|    18.421|       0|
|hp          |   -0.068|     0.010|    -6.742|       0|


#### Guidelines for communicating results 

- **Don't use variable names in your narrative!** Use descriptive terms, so the reader understands your narrative without relying on the codebook.
  - ❌ There is a negative linear relationship between mpg and hp.
  - ✅ There is a negative linear relationship between a car's fuel economy (in miles per gallon) and its horsepower.
- **Know your audience:** Your report should be written for a general audience who has an understanding of statistics at the level of MATH 250.
- **Avoid subject matter jargon:** Don't assume the audience knows all of the specific terminology related to your subject area. If you must use jargon, include a brief definition the first time you introduce a term. 
- **Tell the "so what":** Your report and presentation should be more than a list of interpretations and technical definitions. Focus on what the results mean, i.e. what you want the audience to know about your topic after reading your report or viewing your presentation. 
- **Tell a story:** All visualizations, tables, model output, and narrative should tell a cohesive story!
- **Use one voice:** Though multiple people are writing the report, it should read as if it's from a single author. At least one team member should read through the report before submission to ensure it reads like a cohesive document.

### Additional resources

- [R for Data Science](https://r4ds.had.co.nz/)
- [R Markdown Cookbook](https://bookdown.org/yihui/rmarkdown-cookbook/)
- [Slides in R using Xaringan](https://slides.yihui.org/xaringan/#1)
- Data visualization
  - [ggplot2 Reference](https://ggplot2.tidyverse.org/reference/index.html)
  - [ggplot2: Elegant Graphics for Data Analysis](https://ggplot2-book.org/)
  - [Data Visualization: A Practice Introduction](https://socviz.co/index.html)
  - [Patchwork R Package](https://patchwork.data-imaginist.com/index.html)




