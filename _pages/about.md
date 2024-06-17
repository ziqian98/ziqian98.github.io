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

<hr>

I am a research software engineer in Oracle Health and AI. I received my Master's degree in Computer Science from Carnegie Mellon University, advised by Prof. [Teruko Mitamura](https://www.cs.cmu.edu/~teruko/). 

In my previous experiences, I have a diverse academic and industrial background, including Multimodal AI, Model Compression & Efficient ML, Graph Neural Networks, Computer Vision, Natural Language Processing, AI for Healthcare, Data Augmentation, Large-Scale ML, Speech & Audio, and solid software engineering experiences in algorithm design, data structures, problem-solving, and complexity. I’m also active in academics and have served as a reviewer for many top-tier AI/ML conferences, like ICLR, ACL, NeurIPS, etc.

I have been contemplating how machines can transcend their computational limitations to comprehend human intelligence. My aim is to create computationally efficient machine learning and deep learning models and algorithms, establishing the computational foundations that will enable computers to analyze, recognize, and predict subtle human communicative behaviors in social interactions.


# Research Interests

<hr>

`Multimodal Machine Learning`: representation, alignment, translation, fusion, and co-learning of heterogeneous data

`Natural Language Processing`: text representation, syntactic parsing, semantic analysis, text generation

`Multimodal Sentiment Analysis`: text, audio, video, facial expressions, and physiological signals

`Computer Vision`: image processing, object detection, image segmentation, scene understanding



# Services

<hr>

Conference/Journal reviewer: ACL, ICLR, AAAI, IJCAI, KDD, CVPR, NAACL, NeurIPS, ACMMM, Elsevier, Peerj, MDPI

# Education

<hr>

* M.S. in Computer Science, **Carnegie Mellon University**, Dec. 2020
* B.S. in Telecommunications Engineering, **Beijing University of Posts and Telecommunications**, Jun. 2019

<h1 style="color: blue;">Experience</h1>

<hr>

* ### Oracle 
  * **Software Engineer**, Feb 2021 - Current
    * Health and AI, Cloud Infrasturcture, Multi-Cloud Migration, Edge Cloud

* ### GEIRINA
  * **Machine Learning Engineer Intern**, May 2020 - Aug 2020
    * Maintained Deep Q Network with OpenAI Gym environment for smart power supply control for power plants


* ### Tencent
  * **Machine Learning Engineer Intern**, Apr 2019 - Jun 2019
    * Responsible for implementing Learn To Rank pipeline in WeChat AI


* ### Oracle
  * **Full Stack Software Engineer Intern**, Sep 2018 - Feb 2019
    * Created automation testing methods for testing UI and API actions in frontend and backend.

# Projects & Publications

<hr>
  
### Project 1: Multimodal Audio-Text Sentiment Analysis with Deep Fusion Models
<br />

  <div style="display: flex; align-items: center;">
    <div style="flex: 0 0 auto; margin-right: 10px;">
      <img src="/images/project1.jpg" alt="Image Title" width="300" height="300">
    </div>
    <div style="flex: 1 1 auto;">
      The project aims to explore cutting-edge research in the field of multimodal audio-text sentiment analysis. Sentiment analysis has garnered widespread attention in both academia and industry in recent years, with most studies focusing on text-based sentiment analysis. However, real-world information often originates from multiple modalities, including audio and text. Therefore, in this project, we integrate audio and text, considering the task of multimodal sentiment analysis, and propose a novel fusion strategy comprising both multi-feature fusion and multi-modality fusion to enhance the accuracy of audio-text sentiment analysis. We introduce the DFF-ATMF (Deep Feature Fusion - Audio and Text Modality Fusion) model, consisting of two parallel branches: an audio modality-based branch and a text modality-based branch. Its core mechanisms involve the fusion of multiple feature vectors and attention mechanisms across multiple modalities. Through experiments conducted on the CMU-MOSI dataset and the recently released CMU-MOSEI dataset, sourced from YouTube for sentiment analysis, our DFF-ATMF model demonstrates highly competitive results. Additionally, leveraging attention weight distribution heatmaps, we illustrate the complementary and robust nature of the deep features learned by the DFF-ATMF model. Remarkably, our model also achieves new state-of-the-art results on the IEMOCAP dataset, underscoring the generalization capability of our proposed fusion strategy for multimodal emotion recognition.
    </div>
  </div>

  > #Multimodal Sentiment Analysis, #Emotion Recognition, #Deep Fusion Models

  * Publications
    * **Ziqian Luo**, "Knowledge-guided Aspect-based Summarization," Proc. of the International Conference on Communications, Computing and Artificial Intelligence **CCCAI**, June, 2023.
    * **Ziqian Luo**, Hua Xu, Feiyang Chen, “Audio Sentiment Analysis by Heterogeneous Signal Features Learned from Utterance-Based Parallel Neural Network,” Proc. of the Thirty-third **AAAI**, Honolulu, Jan. 2019.
    * **Ziqian Luo**, Hua Xu, Feiyang Chen, “Utterance-Based Audio Sentiment Analysis Learned by a Parallel Combination of CNN and LSTM,” arXiv preprint, Nov. 2018.
    * Feiyang Chen, **Ziqian Luo**, “Sentiment Analysis using Deep Robust Complementary Fusion of Multi-Features and Multi-Modalities,” arXiv preprint, Mar. 2019.


<hr>

### Project 2: Knowledge-Enhanced Aspect-based Summarization with BART
<br />

  <div style="display: flex; align-items: center;">
    <div style="flex: 0 0 auto; margin-right: 10px;">
      <img src="/images/project2.jpg" alt="Image Title" style="border:0" width="300" height="300">
    </div>
    <div style="flex: 1 1 auto;">
      This project aims to explore how to leverage external knowledge to enhance the performance of the BART model in aspect-based summarization tasks. Contextualized pre-trained models, such as BERT and BART, have demonstrated significant potential in various natural language processing tasks, pushing state-of-the-art results to new levels. While studies have shown that these pre-trained models have captured different types of knowledge due to the massive corpora they have been trained on, injecting task-specific external knowledge often leads to further improvements. In this project, we select aspect-based abstractive summarization as a case study and investigate two different approaches to integrate external knowledge into BART. One approach involves using a knowledge graph, while the other involves using human-defined sequence-level scores. Experimental results indicate that both methods yield improvements over the vanilla BART model.
    </div>
  </div>

  > #Pre-trained Models, #Knowledge Graph, #Natural Language Processing

  * Publications
    * **Ziqian Luo**, "Knowledge-guided Aspect-based Summarization," Proc. of the International Conference on Communications, Computing and Artificial Intelligence **CCCAI**, Jun 2023.
    * Xueting Pan, **Ziqian Luo**, Lisang Zhou, "Navigating the Landscape of Distributed File Systems: Architectures, Implementations, and Considerations," In Journal of Innovations in Applied Engineering and Technology, 2(1), 1–12, Nov 2023.
    
<hr>

### Project 3: Multi-Path Deep Learning for Imbalanced Data Classification in Cryo-Electron Tomography
<br />

  <div style="display: flex; align-items: center;">
    <div style="flex: 0 0 auto; margin-right: 10px;">
      <img src="/images/project3.jpg" alt="Image Title" width="300" height="300">
    </div>
    <div style="flex: 1 1 auto;">
      This project focuses on developing a deep learning-based strategy for the classification of cellular macromolecular complexes captured by Cryo-electron tomography (Cryo-ET), particularly addressing the challenge of imbalanced data. Imbalanced data often leads to unsatisfactory performance of deep learning models as they tend to prioritize major classes while ignoring classes with small amounts of data. In this study, we propose a range of strategies to effectively handle imbalanced data, including data sampling, bagging, boosting, Genetic Programming-based methods, and a novel multi-path convolutional neural network (CNN) model inspired by Inception 3D network. Our multi-path CNN model combines focal loss and mixup techniques to expand the dataset, allowing each path to specialize in a specific type of data and enabling the network to learn the optimal combinations of paths to enhance classification performance. Moreover, extensive experiments have been conducted to demonstrate the flexibility of our proposed method in coping with different numbers of classes by adjusting the number of paths in the multi-path model. This project represents the first application of deep learning methods for dealing with imbalanced data in the internal tissue classification of cell macromolecular complexes, thus opening up a new avenue for cell classification in the field of computational biology.
    </div>
  </div>

  > #Imbalanced Data, #Cryo-Electron Tomography, #Cell Classification, #Computational Biology

  * Publications
    * **Ziqian Luo**, Xiangrui Zeng, Min Xu, “Deep Learning-Based Strategy For Macromolecules Classification with Imbalanced Data from Cellular Electron Cryotomography,” Proc. of **IJCNN**’19, Budapest, Jul 2019.
    * Xueting Pan, **Ziqian Luo**, Lisang Zhou, "Comprehensive Survey of State-of-the-Art Convolutional Neural Network Architectures and Their Applications in Image Classification," In Journal of Innovations in Applied Engineering and Technology, 1(1), 1–16, Mar 2022.


<hr>
    
### Project 4: Optimizing Vision Transformers for Edge Computing
<br />

  <div style="display: flex; align-items: center;">
    <div style="flex: 0 0 auto; margin-right: 10px;">
      <img src="/images/project4.jpg" alt="Image Title" width="300" height="300">
    </div>
    <div style="flex: 1 1 auto;">
      The project aims to tackle the challenges of deploying Vision Transformers (ViT) in resource-constrained environments. Vision Transformers have revolutionized computer vision, surpassing traditional models in performance. However, their deployment is often limited by significant computational and memory requirements. This project evaluates and integrates four key model compression techniques—quantization, low-rank approximation, knowledge distillation, and pruning—to optimize ViTs. Through a thorough comparative analysis and extensive experimental evaluations, the project seeks to achieve a balanced compromise between model accuracy and computational efficiency, enabling the practical use of Vision Transformers in edge computing devices.
    </div>
  </div>

  > #Vision Transformers, #Model Compression, #Edge Computing, #Resource Optimization, #Knowledge Distillation

  * Publications
    * Feiyang Chen, **Ziqian Luo**, Lisang Zhou, Xueting Pan, Ying Jiang, “Comprehensive Survey of Model Compression and Speed up for Vision Transformers,” In Journal of Information, Technology and Policy, 1(1), 1–12, Apr 2024.
    * Lisang Zhou, **Ziqian Luo**, Xueting Pan, "Machine learning-based system reliability analysis with Gaussian Process Regression", In Journal of Computational Methods in Engineering Application, 3(1), 1–23, Nov 2023.


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
