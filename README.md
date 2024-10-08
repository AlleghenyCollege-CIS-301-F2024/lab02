# Data Science (CS301) Lab 2 Assignment

Exploring Gene Expression Data With R

**Assigned** : Wednesday, 11 September 2024

**Due** : Wednesday, 18 September 2024

![logo](graphics/probes.png)

Figure 1: The NCI60 data set was was developed by the National Cancer Institute in the 1980’s to allow for the study of potential anti-cancer drugs. Concerns probes, which are used to detect molecular compounds, monitor cellular activity, and to deliver therapy in cells, the data allows researchers to investigate potential anti-cancer drugs in a wide variety of cell lines which have been organized (i.e., arrogated) by types of cancer.

## Objectives

The main goals of this work include the following.

- To learn how to read R-code used in real types of analysis
- To learn to read and understand basic plots
- To understand the code that produced the plots.

## Overview

When undergoing a project in data science, there will be computer code to write to manage data, calculate statistics and produce plots. Although this computer code provides the evidence of underlying trends in the data, the causality of any observed patterns is largely unknown. In fact, spotting trends is the task of the data scientist who must then decide how to understand the patterns, and decide whether results are actually important to study. Based on this finding, further decisions must  then be made to determine the next courses of action -- to explain how the trends became apart of the data.

## Learning More

Part of the motivation for this lab may be found in the YouTube video that discusses the gene expressions of Planarian worms at the following [link](https://www.youtube.com/watch?v=roZeOBZAa2Q).

Much of the knowledge that we have about the curious genetics of the stem cell function in these organisms was the result of gene expression analysis. Interested readers are invited to learn more about the biology of stem cell growth and regeneration in Planarians from Sanchez et al [1].

## Part 1: Understanding the R Code and Making Sense of the Output

Imagine that you are discussing the code and its output with someone who is new to the project. It is your task to explain to them what each part of the code is doing and what knowledge it brings. In deliverable you are to explain in clear and meaningful language _what the code is doing_. In other types of questions, you are to look at the produced plots to determine what they are conveying to the reader concerning the results.

Please note that some plots may produce many different findings in a single canvas. Your task is to draw your conclusions about the results using whatever criteria you feel is necessary to complete the question.

### Questions

You have been given an R source code file `src/geneExpAnalysis.r` which you are to run using rStudio. The questions to which you are to respond, are listed in the File `writing/reflection.md`. As you respond to each question, please remember to remove the `ToDo`’s below the question, and to periodically push your work to your GitHub repository so that it can be saved to the cloud.

## Part 2: Ethics

Please address the questions on ethical topics at the end of the File `writing/reflection.md`.

## References

[1] P. W. Reddien and A. S. Alvarado, “Fundamentals of planarian regeneration,” Annu. Rev. Cell Dev. Biol., vol. 20, pp. 725–757, 2004.

[2] Afzal, Saira, and Amber Arshad. "Ethical issues among healthcare workers using electronic medical records: A systematic review." Computer Methods and Programs in Biomedicine Update 1 (2021): 100030.

### Required Deliverables

* Complete the `reflections.md` text file with;
  + Your responses to the questions from the Parts described above.

* While you are not required to modify the source file, `src/geneExpAnalysis.r`, please install the `mosiac` library and be sure that you are able to run the code _locally_ on your machine.

### Checks for GatorGrader

For immediate feedback on submissions, we will be using Gator Grade to inform the of missing components in the submission. As you submit, you will notice that there is a thick red X that will change to a green check mark when all components have been included in the submission. You are encouraged to click on the red X to find a listing of the components to address.

## Project Assessment

The grade that a student receives on this assignment will have the following components.

- **GitHub Actions CI Build Status [up to 15%]:**: For the lab01 repository associated with this assignment students will receive a checkmark grade if their last before-the-deadline build passes. This is only checking some baseline writing and commit requirements as well as correct running of the program. An additional reduction will given if the commit log shows a cluster of commits at the end clearly used just to pass this requirement. An addition reduction will also be given if there is no commit during lab work times. All other requirements are evaluated manually.

- **Mastery of Technical Writing [up to 85%]:**: Students will also receive a checkmark grade when the responses to the writing questions presented in the `reflection.md` reveal a proficiency of both writing skills and technical knowledge. To receive a checkmark grade, the submitted writing should have correct spelling, grammar, and punctuation in addition to following the rules of Markdown and providing conceptually and technically accurate answers.

## GatorGrade

You can check the baseline writing and commit requirements for this lab assignment by running department's assignment checking `gatorgrade` tool. To use `gatorgrade`, you first need to make sure you have Python3 installed (type `python --version` to check). If you do not have Python installed, please see:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [How to Install Python 3 and Set Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Then, if you have not done so already, you need to install `gatorgrade`:

- First, [install `pipx`](https://pypa.github.io/pipx/installation/)
- Then, install `gatorgrade` with `pipx install gatorgrade`

Finally, you can run `gatorgrade`:

`gatorgrade --config config/gatorgrade.yml`

## Submitting Your Work

Use GitHub to submit your work. The commands are the following.

```
git add -A
git commit -m "add meaningful commit message"
git push
```

## Seeking Assistance

- Extra resources for using markdown include;
  - [Markdown Tidbits](https://www.youtube.com/watch?v=cdJEUAy5IyA)
  - [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- Do not forget to use the above git commands to push your work to the cloud for the instructor to grade your assignment. You can go to your GitHub repository using your browser to verify that your files have been submitted. Please see the TL’s or the instructor if you have any questions about assignment submission.

Students who have questions about this project outside of the lab time are invited to ask them in the course's Discord channel, or during instructor's or TL's office hours.
