# Remaster the Tidyverse

This repository contains editable class materials built by Garrett Grolemund for two separate one day workshops:

* **Welcome to the Tidyverse**
    
    A gentle introduction to R and its Tidyverse that focuses on learning to do Exploratory Data Analysis with the [ggplot2](https://ggplot2.tidyverse.org/), [dplyr](https://dplyr.tidyverse.org/), [broom](https://broom.tidyverse.org/), [modelr](https://modelr.tidyverse.org/), and [rmarkdown](https://rmarkdown.rstudio.com/) packages. The course focuses on doing data science, not writing code; but by the end of the day students will find that they have gained confidence writing code with R.
    
* **Data Wrangling with the Tidyverse**
    
    An introduction to wrangling lists and tabular data in R with the [tidyr](https://tidyr.tidyverse.org/), [stringr](https://stringr.tidyverse.org/), [forcats](https://forcats.tidyverse.org/), [lubridate](https://lubridate.tidyverse.org/), and [purrr](https://purrr.tidyverse.org/) packages. The course focuses on creating and using tidy tables and is designed to be a sequel to _Welcome to the Tidyverse_.
    
The workshops can be taught sequentially as a two day workshop

Each course directory contains the editable Apple Keynote slides that I present during class, as well as the R Markdown files that I give to the students. The R Markdown files contain the scaffolded exercises that students work through during class. All of the material is copyrighted under the [Creative Commons BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) copyright to make the material easy to reuse. I encourage you to reuse it and adapt it to your own courses as you like! **Sorry, I do not work in PowerPoint and will not be providing PowerPoint versions of the slides.**

Both courses are ready to teach as is—I've taught them several times in this format with pleasing results, but this is my _development_ repository, which means that you can expect slight changes to the courses from time to time. If you plan to use this material, I suggest that you [fork a copy of this repository](https://help.github.com/en/articles/fork-a-repo). This will give you your own stable material to work from.

# Logistics

I've developed an efficient way to deliver the course that I encourage you to try:

1. When scheduling a venue, _ensure_ that the classroom has power strips for the students and wireless internet.
1. About a week ahead of the class, email the students the [workshop set up instructions](/Welcome-To-The-Tidyverse). These remind students to bring a laptop and a power cord, tell students how to download the free software that we will use in class, and ask students to create a free RStudio Cloud account. I do not tell students this unless they are having severe installation bugs, but we won't use these local copies during the workshop. They are only backups in case the classroom wireless network fails. I generally do not have students download slides, etc. ahead of time.
1. Set up an [rstudio.cloud](https://rstudio.cloud/learn/guide) project for the students to use on the day of class. Pre-install all of the packages that students will use and upload all of the course materials to the project directory. Be sure to open and knit one of the student exercises to prompt RStudio Cloud to also install all of the packages related to kniting R Markdown documents.
1. Under the settings (gear) icon, click Access and then make the project viewable by everyone.
1. Copy the project URL and paste it over the analagous URL in the 01-Introduction slide decks.

On the day of the course:

1. Have students visit the URL when prompted by the slides.
1. Demonstrate what will happen when they do. It will take ~35 seconds for everyone's project to open.
1. Have students immediately click "Save a Permanent Copy" at the top of their project.

At this point, each student will have an indentical instance of R and RStudio to run their exercises in. They will also have access to all of the course materials, which are included in the project. You can show students how to download these materials to their project locally (if they wish) when prompted by the slides. Students will have access to their permanent copies of the RStudio Cloud project, and the work they did therein, forever. Like most things **RStudio Cloud no longer supports support Internet Explorer.**

Click the links below to see example RStudio Cloud projects for recent versions of each of the workshops:

* [Welcome to the Tidyverse](https://rstudio.cloud/project/385945)
* [Data Wrangling with the Tidyverse](https://rstudio.cloud/project/385988)

# Why not have students work locally?

I've adopted this workflow because it drastically reduces the amount of time I waste at the beginning of class fixing student's installation bugs.

This may be controversial, but I've come to accept that I'm there to teach students a specific, high value skill. Not to be their tech support. I expect students to be able to handle R install issues on their own or with other resources—especially when the install issues are side effects of security settings or OS's that students choose to use for their own reasons, as many of them are.

A small number of students will not be able to log on to the internet without help, but I've found that I or a TA can help these students during one of the many student exercise sections without delaying the whole class.

# Other tips

1. I usually play a [looping slide show](https://github.com/rstudio-education/remaster-the-tidyverse/blob/master/Welcome-To-The-Tidyverse/keynotes/00-Preclass-loop.key) before class. It can let students know they are in the right place, remind them to connect to the wireless, or do some useful pre-teaching. It's a bit like arriving early to the movies—but with fewer trivia questions.
1. Don't neglect the beginning warm up activity where students talk to each other. A lively discussion at the start of the day will set the tone for the rest of the day. I notice that students are much more engaged, much more talkative, and ask more questions if I begin the day with some sort of free-for-all. In short, it makes class more fun to teach. If you find yourself starting the second day in the middle of an unfinished unit, be sure to insert a warm up meet and re-greet discussion at the start of class—or don't and see what I'm talking about.
1. The timers end with a beep. If it is audible, it will help you regain student attention at the end of an exercise, especially if the exercise involves discussion.
1. Slides are cheap, so I use a lot of them. Don't feel like you need to dwell on each slide—there's no time for that.
1. Use the Tower of Babel picture in the intro to point out that there are multiple ways to do many things in R—and that's OK. The ones you are teaching happen to work well together as a system because they share a common syntax and intuition. Learning one will help students learn the rest. When a student inevitably asks why not do X another way, don't argue. If the student feels confident doing X the other way, then he or she should; but for today the student should try the new way. He or she might like it, but it is OK if they do not.
1. Have fun!
