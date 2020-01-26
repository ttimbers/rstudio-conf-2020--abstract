## Script for rstudio::conf e-poster

### Slide 1

This program is a professional Master of Data Science (MDS) program at the University of British Columbia in Vancouver, BC. Given that it is a professional program, ~ 95% of all graduates go to work in industry, government or not-for-profit sectors following completion of the program. Our current cohort size is ~ 100 students.

The program is 10-months long. The first 8-months are spent on course work (split into 6 ~ one-month blocks, where students take 4 courses concurrently). Followed by a two-month-long group Capstone project. For the Capstone project, we partner with industry, academic research labs, government or organizations from not-for-profit sectors to create solutions to real-world data science problems. 

The program is young still, only 4 years old. The program curriculum was designed from scratch, and specifically for this program. Only MDS students can take these courses. The program undergoes annual review to assess where improvements can be made & ensure that it stays current. 

In the program we teach both R & Python. This is because they are the most popular programming languages for data science. Here we show a breakdown of how these languages are distributed across the courses. In some courses, students learn the same skills in both languages (e.g., general programming, data wrangling, visualization, workflows, software development and packaging) and in other courses we have chosen to specialize in one language in order to go more deeply into that topic (e.g., statistical inference in R, and machine learning in Python). 

### Slide 2

MDS has spent a lot of time considering which tools to teach to enable students to work harmoniously in both R & Python, as well as how to blend these languages within a data science project. 

Here we show an overview of all of the tools we teach in the program with which we use for working in **both** R & Python, as well as some we specifically use for blending between the two languages within a single project. 

I will now give a few examples of how and why we use some of these. 

### Slide 3

In the first month of the program, students are taught to how to program in both R & Python concurrently. To reduce cognitive load we choose to do this using a simple code editor - Jupyter (which allow allows to do autograding - more on this later). We use Jupyter for introducing and teaching both R and Python. This lets students quickly learn **one** simple editor, allowing them to then focus on learning the two languages.

### Slide 4

Starting near the end of the first month, we start moving the students into a more powerful editor - RStudio. We start with having them use this for R via R Markdown. Then a month or so later in our workflows course, we teach them to use RStudio to develop and run R scripts, as well as Python scripts. This is continued in our collaborative software development course (where they learn to package R & Python code into packages). Having one real IDE that can be used for both languages is very nice and efficient for the students as they only need to learn the in's and out's of one IDE and they can then do most of their data science things from one place. 

### Slide 5

When we teach stitching scripts together via data analysis pipelines we teach GNU Make because it is a language agnostic tool and a good introduction-level tool for pipeline automation. Alumni have reported that knowing GNU Make has facilitated their self-learning on more advanced pipeline automation tools after MDS, such as Apache Airflow and Luigi. 

### Slide 6

And for reproducibility and sharing compute environments, we focus on teaching the use of containers, such as Docker. We chose Docker for a similar reason to GNU Make - it is language agnostic, working with both R & Python (in contrast to other language specific tools like packrat and virtualenv). Additionally, Docker has added advantages in remote computing compared to using conda alone (which also works with R & Python), and thus learning Docker has several advantages.

### Slide 7

Teaching a data science program in two languages ...
