---
type: "project" # DON'T TOUCH THIS ! :)
date: "2020-05-16" # Date you first upload your project.
# Title of your project (we like creative title)
title: "Functional Connectivity in Schizophrenia patients with and without Auditory Hallucinations"

# List the names of the collaborators within the [ ]. If alone, simple put your name within []
names: [Jagruti Pershad, Daisy Hu]

# Your project GitHub repository URL
github_repo: https://github.com/24jagruti11/Schiz_Auditory_hallucination.git

# If you are working on a project that has website, indicate the full url including "https://" below or leave it empty.
website:

# List +- 4 keywords that best describe your project within []. Note that the project summary also involves a number of key words. Those are listed on top of the [github repository](https://github.com/brainhack-school2020/project_template), click `manage topics`.
# Please only lowercase letters
tags: [Schizophrenia, fMRI, Auditory Hallucination, Functional Connectivity]

# Summarize your project in < ~75 words. This description will appear at the top of your page and on the list page with other projects..

summary: "Each project repository should have a markdown file explaining the background and objectives of the project, as well as a summary of the results, and links to the different deliverables of the project. Project reports are incorporated in the BHS [website](https://school.brainhackmtl.org/project)."

# If you want to add a cover image (listpage and image in the right), add it to your directory and indicate the name
# below with the extension.
image: "bhs2020.png"
---
<!-- This is an html comment and this won't appear in the rendered page. You are now editing the "content" area, the core of your description. Everything that you can do in markdown is allowed below. We added a couple of comments to guide your through documenting your progress. -->

## Project definition

### Background

Inspired by the [Recurse Centre](https://www.recurse.com/) initiative (formally known as the "hacker school"), Brainhack School was established in 2018 with the mission to train students from multidisciplinary backgrounds to a panoply of reproducible tools for neural data science, using a project-based approach. Following an initial 3-weeks long pilot, a 4th week was added with an intensive bootcamp, so that students could choose what tools to learn more deeply in their projects. As the course became integrated in standard curriculum at different universities, the formula seemed to be working. In order to streamline the different stages of the project, some standard template and milestones needed to be incorporated in a github-based workflow. The "project template" project (which is also our first BHS meta-project) aims at establishing such a standardized template. You can check the following [video](https://youtu.be/PTYs_JFKsHI) where Pierre Bellec gives an overview of the Brainhack school.

<iframe width="560" height="315" src="https://www.youtube.com/embed/PTYs_JFKsHI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Tools

The "project template" project will rely on the following technologies:
 * Markdown, to structure the text.
 * The Hugo website framework which is used by the BHS website. This makes it possible to easily add the markdown project description to the website.
 * Adding the project to the website relies on github, through pull requests.

### Data

Ultimately, the project template will be used by all BHS participants. Data on the different projects will be aggregareted on the [following page](https://school.brainhackmtl.org/project). This will serve as an additional example gallery in the years to come for future brainhack school students. Many reports from [BHS 2019](https://github.com/mtl-brainhack-school-2019) already used this template.

### Deliverables

At the end of this project, we will have:
 - Git repository
 - Codescript

## Results

### Progress overview

The project involved importing data on a github repository, using SciNet teach cluster for the preprocessing of the data and parcellation. Preprocessing involved running MRIQC to generate quality metric report, fMRIPrep for preprocessing of the data, Ciftify Clean for signal cleaning and Ciftify for the visualisation of the data. Parcellation helped to divide brain regions based on brain activty where groups of similar voxels are averaged to reduce the effect of random noise effects.  MACHINE LEARNING

### Tools I learned during this project

 
 fMRI Data Processing with Nilearn
 fMRI Data Visualization

### Results

#### Deliverable 1: report template

A complete README summarizing the entire project and its results.

#### Deliverable 2: project gallery

There is not yet a project gallery, as BHS 2020 is the first edition that will incorporate it on the website. You can still check out the [2019 BHS github organization](https://github.com/mtl-brainhack-school-2019)

##### ECG pupilometry pipeline by Marce Kauffmann

The repository of this project can be found [here](https://github.com/mtl-brainhack-school-2019/ecg_pupillometry_pipeline_kaufmann). The objective was to create a processing pipeline for ECG and pupillometry data. The motivation behind this task is that Marcel's lab (MIST Lab @ Polytechnique Montreal) was conducting a Human-Robot-Interaction user study. The repo features:
 * a [video introduction](http://www.youtube.com/watch/8ZVCNeX42_A) to the project.
 * a presentation [made in a jupyter notebook](https://github.com/mtl-brainhack-school-2019/ecg_pupillometry_pipeline_kaufmann/blob/master/BrainHackPresentation.ipynb) on the results of the project.
 * Notebooks for all analyses.
 * Detailed requirements files, making it easy for others to replicate the environment of the notebook.
 * An overview of the results in the markdown document.

##### Other projects
Here are other good examples of repositories:
- [Learning to manipulate biosignals with python](https://github.com/mtl-brainhack-school-2019/franclespinas-biosignals) by François Lespinasse
- [Run multivariate anaylysis to relate behavioral and electropyhysiological data](https://github.com/mtl-brainhack-school-2019/PLS_PV_Behaviour)
- [PET pipeline automation and structural MRI exploration](https://github.com/mtl-brainhack-school-2019/rwickens-sMRI-PET) by Rebekah Wickens
- [Working with PSG [EEG] data from Parkinson's patients](https://github.com/mtl-brainhack-school-2019/Soraya-sleep-data-in-PD-patients) by Cryomatrix
- [Exploring Brain Functional Activation in Adolescents Who Attempted Suicide](https://github.com/mtl-brainhack-school-2019/Anthony-Gifuni-repo) by Anthony Gifuni

#### Deliverable 3: Instructions

 To be made available soon.

## Conclusion and acknowledgement

The BHS team hope you will find this template helpful in documenting your project. Developping this template was a group effort, and benefitted from the feedback and ideas of all BHS students over the years.
