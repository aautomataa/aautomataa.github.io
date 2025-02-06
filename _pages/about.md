---
permalink: /
title: "⭐ Welcome to my website! ⭐"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<<div style="background-color: #f9f9f9; padding: 15px; border-radius: 10px; border: 2px solid #ccc; margin: 0 20px;">
  <h3 style="text-align: center; color: #4CAF50; font-size: 1.5em;">
    My AI Fantasy
  </h3>
  <p style="font-weight: bold; font-size: 1em; color: #333;">
    Departing from the Babel of von Neumann architectures, I traversed the mist-laden forests of backpropagation. In the pantheon of convolutional kernels, I witnessed the ascent of feature pyramids. Now standing beneath the observational dome of transformers, I decipher cosmic lexicons hidden within high-dimensional manifolds.
  </p>
</div>

Academic Journey
======
My academic journey has been driven by a curiosity for cutting-edge technologies and a commitment to
applying theoretical knowledge to practical problems. I independently completed Stanford’s renowned
cs231n course, successfully implementing all assignments on GitHub. This experience deepened my
understanding of deep learning architectures, neural networks, and computer vision, while also honing
my ability to tackle complex problems with a structured and analytical approach. Additionally, I
contributed to a Human Activity Recognition (HAR) project under the mentorship of a faculty member, where I applied machine learning techniques to real-world datasets and co-authored a research
manuscript. Currently, I am writing an independent research paper as the sole author, focusing on
developing a novel deep learning algorithm. These experiences have strengthened my research, coding, and technical writing skills, and encouraged me to explore more interesting things! 

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.
