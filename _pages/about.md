---
layout: archive
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Welcome :-D


I am currently a second year master student in Language Technologies Institute, School of Computer Science at Carnegie Mellon University. I am going to graduate in December, 2020. I am looking for full-time positions in **Software Engineering** or **Machine Learning**.


# Education

<hr>

* M.S. in Intelligent Information System, **Carnegie Mellon University**, Dec. 2020 (expected)
* B.S. in Telecommunications Engineering, **Beijing University of Posts and Telecommunications**, Jun. 2019


# Work Experience

<hr>

* ### GEIRINA
* **Software Engineer Intern**
* San Jose, CA, 2020.5-2020.8
  * Maintained Deep Q Network with OpenAI Gym environment for smart power supply control for power plants.


* ### Tencent (WeChat AI Team)
* **Machine Learning Engineer Intern**
* Beijing, China, 2019.4-2019.6
  * Responsible for implementing Learn To Rank pipeline


* ### Oracle
* **Full Stack Software Engineer Intern**
* Beijing, China, 2018.9-2019.2
  * Created automation testing methods by Java and **JavaScript** for testing API and UI operations for an Enterprise-level project.

# Project Experience

<hr>


* ### Attention-based End-to-End Speech Recognition System (Top %10 on Kaggle Competition)
* Machine Learning Department, Carnegie Mellon University 2020.1 - 2020.5
  * Built an Attention-based End-to-End Speech Recognition System.
  
* ### Predicting the Stock Market with Large Scale Reddit Comments Data (300GB)
* Machine Learning Department, Carnegie Mellon University. 2020.1 - 2020.5
  * Built a scalable Entity Resolution System by inverted index and **pair RDDs** to measure similarities among large texts.
  
* ### Algorithms for NLP
* Language Technologies Institute, Carnegie Mellon University, 2019.8 - 2019.12
  * Generated word alignments between English and French sentence by HMM using Viterbi and EM algorithm.
  
* ### Computer System Design
* Computer Science Deparment, Carnegie Mellon University, 2019.4 - 2019.8
  * Implemented a **dynamic memory allocator library** in C including malloc, free, calloc, realloc features.
  
  
* ### Audio Sentiment Analysis by a Parallel and Utterance-Dependent Deep Learning Network
* Department of Computer Science of Technology, Tsinghua University, 2017.10 - 2019.3
  * Designed a parallel network based on utterance-dependent LSTM and CNN for audio sentiment analysis.

# Publications

<hr>

* **Ziqian Luo**, Hua Xu, Feiyang Chen, “Audio Sentiment Analysis by Heterogeneous Signal Features Learned from Utterance-Based Parallel Neural Network,” Proc. of the Thirty-third **AAAI**, Honolulu, Jan. 2019.
* **Ziqian Luo**, Xiangrui Zeng, Min Xu, “Deep Learning-Based Strategy For Macromolecules Classification with Imbalanced Data from Cellular Electron Cryotomography,” Proc. of **IJCNN**’19, Budapest, Jul. 2019.

  

# Skills

<hr>

* **Languages:** Java, Python, C/C++, Matlab, HTML, JavaScript, VHDL, SQL
* **Frameworks:** Pytorch, TensorFlow, Keras, Scikit-learn
* **Tools:** Spark, MySQL, LaTeX, AWS, Azure, Git, Jenkins, Docker, Travis













<!--

This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

-->
