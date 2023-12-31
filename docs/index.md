# GEN220: Highthroughput Biological Data Analysis - Fall 2023

See the [Syllabus](Resources/Syllabus) [PDF](Resources/Syllabus.pdf)
for an overview of lecture topics.

Examples worked during class will be uploaded in [this working repository](https://github.com/biodataprog/GEN220_2023_examples).
To check it out and keep it update.
```
git clone https://github.com/biodataprog/GEN220_2023_examples.git
cd GEN220_2023_examples
# ... time passes, new examples are uploaded
git pull # to get the latest version of the files

# let's also checkout the example datasets for the class
cd ..
git clone https://github.com/biodataprog/GEN220_data.git
```
# Resources
* HPCC instructions on using [SSH keys](https://hpcc.ucr.edu/manuals/access/login/#a-ssh-login-from-terminal)
* Access HPCC via [web](https://hpcc.ucr.edu/manuals/access/login/#b-web-based-access)
* [Github workflows](Resources/Git_tutorial) and [Software Carpentry Github Tutorial](http://swcarpentry.github.io/git-novice/)
* [Software Carpentry UNIX/Shell Novice Tutorial](http://swcarpentry.github.io/shell-novice/)
* [UNIX command reference 1](https://rumorscity.com/wp-content/uploads/2014/08/10-Linux-Unix-Command-Cheat-Sheet-011.jpg)
* [UNIX command reference 2](UNIX/img/FOSS_CheatSheet.jpg)
* [Shell Scripting Tutorial](https://www.shellscript.sh/)
* [Intro to Command-Line from HPCC](http://hpcc.ucr.edu/manuals_linux-basics_cmdline-basics.html)

# Major Topic Areas
* [UNIX](UNIX) Shell scripting and using [HPCC](http://hpcc.ucr.edu)
* [Python](Python) Programming
* [Bioinformatics](Bioinfomatics) analysis methods
* Editors
  * [VIM/VI](http://hpcc.ucr.edu/manuals_linux-basics_vim.html)
  * [Nano](https://www.howtogeek.com/howto/42980/the-beginners-guide-to-nano-the-linux-command-line-text-editor/)
  * [Emacs](https://www.gnu.org/software/emacs/tour/)
  * [Emacs Manual](https://www.gnu.org/software/emacs/manual/html_node/emacs/index.html)
  * [Visual Studio](https://visualstudio.microsoft.com/) - see [HPCC INSTRUCTIONS](https://hpcc.ucr.edu/manuals/hpc_cluster/selected_software/vscode/) - there is also a web-version you can run if you only have a tablet, the HPCC instructions will help set this up too.

# Homework

* HW1 - [Intro](Assignments/HW1) [PDF](Assignments/HW1.pdf)
* HW2 - [Airports](Assignments/HW2) [PDF](Assignments/HW2.pdf)
* HW3 - [Table Seating and Scattergories](Assignments/HW3) [PDF](Assignments/HW3.pdf)
* HW4 
* HW5

# Project

* [Project Team Ideas](Assignments/Project_Ideas) [PDF](Assignments/Project_Ideas.pdf)
* [Project Team Report Template](Assignments/Project_Report_Template) [PDF](Assignments/Project_Report_Template.pdf)
* [Project Presentation Info](Assignments/Project_Presentation) [PDF](Assignments/Project_Presentation.pdf)

# Lectures

The course will be divided into three topic areas.

## UNIX
1. [Course Intro / UNIX I: Cmdline](UNIX/00_Login_Notebook) [PDF](UNIX/00_Login_Notebook.pdf)
1. [UNIX: Running Tools](UNIX/01_Tools) [PDF](UNIX/01_Tools.pdf)
1. [UNIX: Analysis and Programming](UNIX/02_Analysis_summary) [PDF](UNIX/02_Analysis_summary.pdf)
1. [UNIX: Misc Tricks](UNIX/03_Advanced_UNIX_DataProcessing) [PDF](UNIX/03_Advanced_UNIX_DataProcessing.pdf)

## Python
1. [Python: Intro](Python/01_Python_Intro) [PDF](Python/01_Python_Intro.pdf)
1. [Python: Logic,Loops,IO](Python/02_Loops_IO) [PDF](Python/02_Loops_IO.pdf)
1. [Python: Dictionaries and Functions](Python/03_Dict_Func.md) [PDF](Python/03_Dict_Func.pdf)
1. [Python: Workshop](Python/04_Workshop) [PDF](Python/04_Workshop.pdf)
1. [Python: Regular Expressions](Python/05_String_patterns) [PDF](Python/05_String_patterns.pdf)
1. [Python: Packages/BioPython](Python/06_Packages) [PDF](Python/06_Packages.pdf)

## Bioinformatics and Genomics
1. [Bioinformatics: Basics and BLAST](Bioinformatics/Basic_Bioinformatics) [PDF](Bioinformatics/Basic_Bioinformatics.pdf)
1. [Bioinformatics: Short Reads](Bioinformatics/Short_read_aligning) [PDF](Bioinformatics/Short_read_aligning.pdf)
1. [Bioinformatics: RNASeq](Bioinformatics/RNASeq) [PDF](Bioinformatics/RNASeq.pdf)
2. [Bioinformatics: Microbiome](Bioinformatics/Microbiome_data) [PDF](Bioinformatics/Microbiome_data.pdf)
1. [Bioinformatics: Variation and SNPs](Bioinformatics/Variants) [PDF](Bioinformatics/Variants.pdf)
1. [Bioinformatics: Data Ranges](Bioinformatics/Ranges_Features_overlap) [PDF](Bioinformatics/Ranges_Features_overlap.pdf)
1. [Phylogeny and Gene Families](Bioinformatics/Phylogeny_families) [PDF](Bioinformatics/Phylogeny_families.pdf)
1. [Bioinformatics: Protein domains](Bioinformatics/Protein_domains) [PDF](Bioinformatics/Protein_domains.pdf)
1. [Bioinformatics: Orthology](Bioinformatics/Orthology) [PDF](Bioinformatics/Orthology.pdf)
2. [Bioinformatics: Genome Browsers](Bioinformatics/Genome_Browsers) [PDF](Bioinformatics/Genome_Browsers.pdf)
1. [Bioinformatics: Workshop - parsing data](Bioinformatics/Workshop_parsing) [PDF](Bioinformatics/Workshop_parsing.pdf)


## Other skills and Tools
1. [Data viz with R](Misc/Rplotting) [PDF](Misc/Rplotting.pdf)
1. [R basics](Misc/Rplotting) - Rstudio on HPCC [http://rstudio.hpcc.ucr.edu](http://rstudio.hpcc.ucr.edu/), [https://rstudio.cloud/](https://rstudio.cloud/) or install [Rstudio](https://rstudio.com/products/rstudio/download/#download) on your own computer.
   - Also see [Data Carpentry DataViz](https://datacarpentry.org/R-genomics/05-data-visualization.html)
1. [Building Websites](Misc/Building_Websites) using github.io [PDF](Misc/Building_Websites.pdf)
