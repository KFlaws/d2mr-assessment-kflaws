# Assessment

## Instructions

1. Complete the basic information section in full. Confirm all links are correct and accessible, and that all materials are in the same project subdirectory as this assessment file, or that you have provided clear instructions for accessing external materials.
2. Complete any items in the additional information section as needed.
3. Check off any objectives you are attempting to demonstrate, and indicate where a met objective should count toward your 20 unique objectives.
4. Optionally, complete the unassessed objectives section, which may earn points toward the 20 additional objectives-based points.
4. Optionally, complete the reflection section, which may earn engagement points.
5. Submit a link to the GitHub subdirectory containing this file in the corresponding Canvas assignment.

## Basic information

Name: Kristen Flaws

CNetID: 12454764 <!-- your cnet id is the first part of your uchi email, not a number -->

Section: 1

Mini-project title: Mini-Assignment-1

Submission date: 01/18/2025

Project GitHub subdirectory URL: [06_r-programming/01_hello-world/Mini-Assignment-1.R](https://github.com/KFlaws/d2mr-assessment-kflaws/blob/main/06_r-programming/01_hello-world/Mini-Assignment-1.R) <!-- in the future, link to the subdirectory rather than the file itself -->

URL or instructions to access additional materials, if needed:


## Additional information

1. Did you complete the project with direct collaborators or general support? If so, who did you collaborate with and what was/were their contribution(s)? No
    1. Direct collaborators (students who will be turning in a version of the same project) and their contributions:
    2. General support (students who helped you with debugging, conceptual understanding, or the like) and their contributions:
2. Did you use LLMs or other AI models to generate text or code for this project? If so, which tools did you use and how did you use them? Remember in this class you *are* allowed (even encouraged) to use these tools for help with coding, but not for writing text. This can be very brief, just one or two sentences is fine unless you have more you'd like to add.
    1. I used ChatGPT to tell me why my code was running but I was not receiving the output I wanted so I could make the necessary adjustments.
3. For off-the-menu projects only, did you complete the project as proposed? If not, what changed?
    1. N/A

## Assessed Objectives

Mark an objective attempt for any learning objectives you believe you have demonstrated in this assignment.

Mark when an objective attempt should count toward the 20 unique objectives requirement. If your attempt is successful, your grader will mark the standard as met on your objective-tracker document.

Below each learning objective is a list of general expectations for meeting that objective. You should aim to meet all expectations to earn a point for meeting the objective, but these are not rigid requirements. For example, writing a complex and creative function that uses multiple arguments and returns a complex output could meet the "parse and define functions and arguments" objective, even if it is only used in one context. 

### GitHub and R Studio

1.  Create and maintain a repo with sensible organization and naming conventions

    1.  All folder and file names are informative
    2.  Uses relative paths correctly
    3.  Does not have duplicate/redundant elements

        -   [ ] Objective attempt
        -   [X] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments: Although you're working in the assessment repo fork, for this objective you need to show us the ability to create and maintain your own original repo that can show understanding and applicability of GitHub best practices.

2.  Maintain an informative and up-to-date README.md

    1.  Includes description of repo purpose, data use, research questions, etc.
    2.  Outlines the repo structure with file tree or similar

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

3.  Integrate a GitHub repo with an R studio project, including .gitignore file

    1.  All scripts run and all notebooks render if the repo is cloned to another location
    2.  .gitingore comprehensively excludes unnecessary, private, and very large files and is be commeted appropriately

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

4.  Effectively use version control

    1.  Used frequent, informative commit messages
    2.  Relies on document revisions rather than manually created new versions

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

### R programming

5.  Find, install, require, and load R packages

    1. No errors occur when running scripts in a new environment and/or comments sufficiently explain package installation requirements
    2. Uses more than one function to install/load/require packages

        -   [ ] Objective attempt
        -   [X] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments: Your script is written in base R (no packages).

6.  Use arithmetic, comparison, and logical operators

    1. Uses all three types of operators
    2. Uses multiple operators in data transformation pipelines and/or inline R code

        -   [ ] Objective attempt
        -   [X] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments: 
            - While arithmetic and comparison operators are correctly used in this script, logical operators are not explicitly used, like & (and), | (or), ! (not), etc. 
            - There are no data transformation pipelines in the script, and because it is an .R script (not a .Rmd file), there is no inline R code. You could meet this objective in something other than those 2 recommendations, but it would need to be a more complex context.

7.  Parse and define functions and arguments

    1. Defines at least one function with at least one argument
    2. Runs without error and produces expected output in at least 2 contexts
    3. Functions are well-documented with comments

        -   [ ] Objective attempt
        -   [X] Unique objective attempt
        -   [X] Objective met
        -   Grader comments:

8.  Parse and write conditional statements and/or loops

    1. Uses conditional in multiple contexts, including dplyr pipelines
    2. Uses multiple types of conditional/loop functions (e.g., `if_else()`, `case_when()`, `for`, `while`)

        -   [ ] Objective attempt
        -   [X] Unique objective attempt
        -   [X] Objective met
        -   Grader comments: `if-else` and `while` are used

### Tidyverse

9.  Use `readr` functions to read in and write out data

    1. Reads in data from at least one source in code chunk or sourced script
    2. Writes out intermediate and/or final datasets in code chunks or sourced scripts

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

10. Use `dplyr` and `tidyr` functions to transform data

    1. Uses at least 3 unique `dplyr` functions
    2. Uses at least 1 `tidyr` function in a data transformation pipeline
    3. Combines `dplyr` and `tidyr` functions in a data transformation pipeline

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

11. Use `stringr` functions to work with string variables

    1. Uses ate least 2 unique `stringr` functions 
    2. Uses `stringr` functions in a data transformation pipeline

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

12. Use `forcats` functions to work with factor variables

    1. Uses ate least 2 unique `forcats` functions or one function in 2 unique contexts (with different purposes)
    2. Uses `forcats` functions in a data transformation pipeline

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

### Data visualization with ggplot2

13. Produce 1- and 2-variable plots with `geom_*` layers

    1. Creates at least 2 figures with different `geom_*` layers (e.g., a scatter plot and a bar plot)
    2. At least one plot is multi-variable

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

14. Use dynamic aesthetics to group data

    1. Uses at least 2 unique data-mapped `aes()` arguments (e.g., color, shape, size) to group data in a plot in one or multiple plots

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

15. Use facets to create parallel plots

    1. Uses facets in at least 2 ways (e.g., using both `facet_wrap()` and `facet_grid()`), modifying the number of rows and columns, using free vs fixed scales, etc.)
    2. Combines facets with other dynamic grouping aesthetics

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

16. Create publication-quality plots using `theme` and `labs` layers

    1. Plots have informative titles, axis labels, and legends
    2. Fonts are stylized professionally and legibly (e.g., adjusted size/angle/justification)
    3. Variables display in plain English (e.g., "Age (years)" not "child_age_yrs"
    4. Uses at least 1 static aesthetic (e.g., color, shape, size) that improves visual clarity without mapping to data

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

### Data analysis

17. Perform simple descriptive analyses with multiple data types

    1. Calculates summary/descriptive statistics for at least 1 numeric variable (e.g., mean, standard deviation) 
    2. Calculates summary/descriptive statistics for at least 1 non-numeric variable (e.g., frequencies, proportions)
    3. Presents results in narrative text, table, or plot

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

18. Perform simple hypothesis testing analyses for multiple data types

    1. Performs at least 1 hypothesis test for numeric data (e.g., t-tests, linear regression)
    2. Performs at least 1 hypothesis test for factor data (e.g., chi-square, ANOVA)
    3. Presents results in narrative text, table, or plot

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

19. Present and interpret statistics in manuscript narrative

    1. Presents and interprets results of analyses in narrative text, like the results section of a journal article, including all information appropriate for a given analysis (e.g., effect size, p-value, confidence interval -- dependent on analysis type and results)
    2. Discriminates between statistically signficiant and non-signficant statistics, where applicable
    3. Discriminates between informative and non-informative statistics and presents only the former in narrative text
    4. Uses dynamic inline R code to render data-dependent text

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

### BibTeX

20. Render APA7 in-text citations with BibTeX syntax for multiple citation forms

    1. Cites at least 3 sources in-text
    2. Uses at least 2 citation forms (e.g., (Author, Year), Author (Year), etc.)
    3. May use `cite_r()` to cite R and R packages

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

21. Render an APA7 references page from a .bib file

    1. Includes all sources cited in-text
    2. Formats references in APA7 style
    3. Presents accurate, complete, and error-free references
    4. May include R and R package citations with `cite_r()`
    5. May include references not cited in-text

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

### Notebooks and code chunks

22. Create and effectively use code chunks following best practices

    1.  Uses informative names/labels
    2.  Includes frequent, informative comments
    3.  Follows the "1-chunk-1-thing" rule
    4.  Chunks are distributed throughout the manuscript, sensibly placed near the text they support

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments: 
        
23. Use code chunks to set up a quarto document

    1. Sources at least 1 .R script and/or reads in necessary data
    2. Loads packages in at least 1 code chunk
    3. Sets preferences/options in at least 1 code chunk
    4. Organizes setup chunks sensibly

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

24. Render publication-quality tables, figures, and images from code chunks

    1. Produces at least 1 table or image with a caption
    2. Produces at least 1 figure/plot with a markdown caption
    3. Captions are informative, complete, and render correctly
    4. All tables and figures are referenced in the narrative text (e.g., Figure 1)
    5. References render without error and link to the correct table/figure in pdf/html output

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

25. Execute descriptive analyses and/or hypothesis testing in code chunks

    1. At least 1 code chunk executes a descriptive analysis (e.g., `summary()`, `table()`)
    2. At least 1 code chunk executes a hypothesis test (e.g., `t.test()`, `chisq.test()`)
    3. Results are presented in narrative text, table, or plot
    4. Results are not displayed as raw R output
    5. Chunks are organized sensibly and appear near the text they support

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

### R Markdown and quarto

26. Create and maintain a quarto document YAML header
    
    1. Includes all necessary metadata, output options, and formatting options necessary to render an APA styled document (or other specified style if appropriate for the project)

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

27. Use quarto R Markdown to compose an academic manuscript

    1. Uses at least 2 unique text styles (e.g., bold, italics, code)
    2. Uses at least 2 unique header levels
    3. Includes at least 1 list
    4. Includes at least 1 footnote

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

28. Use inline R variables to replace static text

    1. Replaces static text with inline R references in at least 3 unique numeric contexts
    2. Replaces static text with inline R references in at least 1 character context
    3. Ideally, uses inline R references for all data-dependent text

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

29. Run inline R functions to render dynamic data-dependent text

    1. Uses inline R functions to render at least 3 unique data-dependent text outputs (e.g., performs rounding, calculates means, subtracts one list length from another, etc. -- inline rather than in a code chunk)

    -   [ ] Objective attempt
    -   [ ] Unique objective attempt
    -   [ ] Objective met
    -   Grader comments:

30. Use `knitr` and quarto to produce an APA7 formatted 1-click PDF manuscript

    1. Produces a PDF output that is formatted in APA7 style
    2. PDF includes all necessary elements (e.g., title page, abstract, body, references)
    3. PDF renders without error and includes all text, tables, and figures
    4. No additional steps are needed (e.g., finding data, determining necessary packages to install and load, running unsourced scripts)

        -   [ ] Objective attempt
        -   [ ] Unique objective attempt
        -   [ ] Objective met
        -   Grader comments:

## Unassessed Objectives & Off-the-Syllabus Skills

You may earn points toward the 20 additional objectives-based points by demonstrating any of the following skills, or by demonstrating "off-the-syllabus"" skills related to the course but not directly covered in class. These cannot count toward demonstration of 20 unique objectives.

## Unassessed learning objectives

The following learning objectives are not required for the course grade but are important for your development as a data scientist. They may be demonstrated in the mini-projects as part of the additional 20 points earned beyond the 20 for unique, assessed standards.

You are not required to demonstrate these objectives in your independent project, but incorporating them can enhance the overall quality of your project and add to the engagement component of the project grade.

### Troubleshooting, debugging, and best practices

1.  use frequent, informative comments in code and markdown
2.  find and understand documentation for R packages and functions
3.  follow a debugging workflow with independent and collaborative strategies
4.  parse and investigate error messages
5.  follow a coding style guide

### RStudio & R

6.  customize RStudio
7.  use BibTeX with `citr` and Zotero integration
8.  parse and write complex `for` and `while` loops
9.  create and use intermediate datasets
10. determine when code is better suited for a sourced script vs. a notebook chunk and source scripts appropriately

### Conceptual skills

11. explain and apply the “grammar of graphics”
12. name and differentiate R data types
13. name and differentiate R objects
14. define “tidy” data and explain its advantages and disadvantages
15. recognize and interpret common data visualizations
16. determine most appropriate visualizations and analyses for specific research questions and data

### Unassessed objectives evaluation

If you believe you have demonstrated any of the above skills sufficiently to count toward the 20 additional objectives-based points, please indicate which objective(s) you believe you have met and provide a brief explanation of how you have met each objective.

<!-- Explanation of demonstrated unassessed objectives below this line -->
I believe I have demonstrated unassessed objectives 1, 2, 3, 4, 5, and 8 in this assignment. I met unassessed objective 1 by providing frequent comments throughout my assignment showing my thought process of the steps I was taking. I met unassessed objective 2 through downloading relevant packages and learning the r functions that were required for me to complete the assignment (assigning a function, conditionals, and the 'while' loop). For unassessed objective 3, I brought my questions to slack, ChatGPT, other students, and Dr.Dowling in order to find out why my code was not working in the way I had intended and looked for problem solving solutions. I met unassessed objective 4 by evaluating each of the error messages I received and either looking them up, asking a peer, or simply trying something else to see if it solved my issue. Many times, by looking at the error message I was able to figure out what was wrong and made easy adjustments. For example, I was using commas between my paste0 output options and I was receiving an error message. I did not have the {} in the correct place, so my code was not running properly and was not recognizing the reason for the commas. For unassessed objective 5, I followed Dr. Dowlings examples and coding style to help influence my own. And finally, for unassessed objective 8, I demonstrated use of a 'while' loop following my conditionals.

<!-- Explanation of demonstrated unassessed objectives above this line -->

### Off-the-syllabus skills evaluation

If you have demonstrated any off-the-syllabus skills related to the course but not directly covered in class, please describe the skill(s) and how you have demonstrated them in your project. These may include things like building Quarto websites, working with non-tabular data, creating Shiny or other interactive applications, etc. Menu items marked "OtS" should demonstrate these skills, but you may demonstrate them in any other menu item or off-the-menu project.

<!-- Explanation of demonstrated off-the-syllabus skills below this line -->
I do not believe I demonstrated any off-the-syllabus skills in this project.

<!-- Explanation of demonstrated off-the-syllabus skills above this line -->


## Reflection

Optionally, you may provide a brief reflection on your experience with this project. What did you learn? What would you do differently next time? What was the most challenging part of the project? What was the most rewarding? You do not have to answer these questions directly; they are just meant to help you think about your experience.

Thoughtful reflections may earn engagement points.


<!-- Reflection below this line -->
This project, although relatively basic was difficult for me! When I first started, I felt like I couldn't get anything to work in the way I intended and I was getting very frustrated. I was encountering a lot of little problems that now seem very obvious, but before were stopping me in my tracks. For example, I was very confused why I could create my whole code, to what I thought was correct, but when I when to test it nothing happened. I was not clicking the 'run' button at the top to actually tell my code to run. Later, when I did run my code, I would test outputs and again I kept receiving error messages. I used ChatGPT to tell me what the issue was and I realized I was not using quotations around the names i was attempting to input, so R thought it was an undefined variable. Again, now these problems seem so obvious but now I know for the future! The most rewarding part of this project was finishing and having all of my codes run as intended! I was so proud of myself when I finished and although I know the projects are only going to get more difficult, I feel much more confident in how I will approach them, and even excited to explore more of R.

<!-- Do not edit below this line. -->

## Grader feedback

-   Grader: ND + ML
-   Date: 1/20/25
-   Points toward unique objectives (up to 20): 2
-   Additional points (up to 20): 3
-   TA provisional engagement points (up to 10):
-   Final approved engagement points (up to 10): 4
-   Total points (up to 50): 9

Engagement points are awarded for going above and beyond the expectations of the project and are not guaranteed on any given submission.. Demonstrating the assessed learning objectives earns you points in those categories, but engagement points are awarded for exceptional effort, creativity, or skill.

TAs may recommend engagement points provisionally, but the instructor will make the final decision on engagement points.

Additional comments: 

Unassessed objectives met:

-   [ ] 1 use frequent, informative comments in code and markdown
    -   Note: good comments in your code, but no markdown to include comments in
-   [X] 2 find and understand documentation for R packages and functions
-   [X] 3 follow a debugging workflow with independent and collaborative strategies
-   [X] 4 parse and investigate error messages
-   [ ] 5 follow a coding style guide
    -   Note: Your code is well-organized and easy to follow, but there aren't enough components to show consistent use of style (e.g., you've only got one function, so it's not clear what style rule you are using for naming functions or how you'd apply it to many functions/objects). If you want to attempt this in a future project, use the reflection in the assessment to explain how you made decisions about style and how you followed them consistently. 
-   [ ] 8 parse and write complex `for` and `while` loops
    -   Note: You did you a while loop, but it's not "complex." You've got the hang of it in principle though, so I think you can hit this one on your next project!

ND: Great job! It's clear you put a lot of thought into your process and what you learned. Although you're not getting credit for all the objectives you attempted, I am confident that you are gaining (or have already gained!) those skills. It's just a matter of incorporating them into your work. I'm assigning 4 engagement points for: pushing yourself to get past a super steep early learning curve, asking for help (and learning from it very quickly), and challenging yourself to take on more than just the bare minimum, like working in that while loop even if it's not quite "complex" yet. Keep up the great work!

ML:
1. For unique objectives: Good job! A creative use of a built-in function `sample()`.
2. Unassessed objectives evaluation: While 2, 3, and 4 are demonstrated in this assignment, 5 and 8 are not quite achieved as expected. 
    - For 5, improvement on naming styles, spacing, and bracing could be made. For example, `helloworld` should be `hello_world` to follow `snake_case` convention. 
    - For 8, no complex `for` and `while` loops are included.
3. Reflection: Your reflection shows significant personal growth from overcoming initial frustrations to successfully completing your project, which is a key part of learning. Well done!
