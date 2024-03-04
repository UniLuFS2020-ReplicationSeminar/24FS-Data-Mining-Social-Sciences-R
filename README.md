# Course Description

Data analysis increasingly involves mining data from the Internet and handling big datasets. However, students often lack the knowledge and experience required to take full advantage of the Internet and social media's data opportunities. This course guides the students to move their first steps into data mining. The course offers case studies and exercises in a friendly class environment. Students will learn (by doing) how to collect and handle web data in their future work. The course covers the primary skills required to access web data confidently.

## Course prerequisites and software installation

A personal motivation to learn data mining is the only hard requirement for this course: passive, listening-only, and credit-oriented attendance styles are discouraged and incompatible with effective and durable learning.

Students are expected to have some working knowledge of the R language (key notions will be refreshed in class). Some basic statistics and programming skills (e.g., one previous course in statistics using R) are recommended to reduce the overall workload. Students are also expected to possess basic computer skills (e.g., using keyboard shortcuts, handling files and folders, and basic knowledge of the shell [[short intro](https://happygitwithr.com/shell.html#what-is-the-shell)]).

### Software requirements
For this course, there are several software tools you'll need to install and configure. Please allocate approximately 2 hours **before our first class** to complete the following eight steps carefully. In case you need support, 
1. Register at [Perusall.com](Perusall.com) with your university email and familiarize yourself with the Perusall interface;
2. Install or upgrade R and RStudio, and then install the “tidyverse” packages following [this guide](https://r4ds.hadley.nz/intro#prerequisites);
3. Register a GitHub account using your personal email and a professional username ([guide](https://happygitwithr.com/github-acct.html));
4. Install Git ([guide](https://happygitwithr.com/install-git.html));
5. Configure Git by adding your GitHub chosen username and email ([guide](https://happygitwithr.com/hello-git.html));
6. Generate and set a Personal Access Token, PAT for HTTPS protocol ([guide](https://happygitwithr.com/https-pat.html#tldr); in short in RStudio, execute `usethis::create_github_token()`, then copy the token, and finally set it running `gitcreds::gitcreds_set()` and paste it there.
7. Create a test repository on GitHub ([guide](https://happygitwithr.com/rstudio-git-github.html#make-a-repo-on-github-1); pick HTTPS).
8. Clone the test repo to your computer using RStudio ([guide](https://happygitwithr.com/rstudio-git-github.html#clone-the-test-github-repository-to-your-computer-via-rstudio); if you managed to clone, you should be all right without making a local change and pushing it.

## Structure of the course and learning outcomes

The course is structured in three blocks:

1. An introductory block covers the essential knowledge for working with big data (notions of R programming, developing reproducible code, reporting in automated notebooks, version control, and Git/GitHub; secondary datasets for social science research & MySQL).
2. A data access block focuses on web scraping and related tools (introduction to regular expressions, HTML language, XML, and JSON data structures).
3. A third block introduces more advanced data access concepts, such as API interaction, and allows students to practice with live coding sessions in class.

By the end of the course, active participants will:

1. Gain proficiency in data analysis, learning to analyze data efficiently and reproducibly. [Data analysis]
2. Understand and critically re-assess data-related issues arising in applied research problems with big data. [Data literacy]
3. Learn how to develop and debug complex code throughout the data analysis cycle (mining, tidying, analyzing, reporting). [Programming and statistical skills]
4. Develop feasible big data research designs. [Research and analytical skills]
5. Handle unstructured text and unfold the tidying process to obtain structured data. [Text mining]
