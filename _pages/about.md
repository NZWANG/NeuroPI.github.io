---
permalink: /
title: "Homepage of NeuroPI"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Dr. WANG Nizhuan is the director of NeuroPI Lab. Currently he is a Research Assistant Professor, Principal Investigator (PI), PhD student and postdoc fellow supervisor (Prof. Dr. Wai Ting Siok Group) of Department of Chinese and Bilingual Studies, The Hong Kong Polytechnic University, Hong Kong. Before that he was a Research Associate Professor (Prof. Dr. Dinggang Shen Group) at School of Biomedical Engineering, ShanghaiTech University (2022.01-2024.01). Also, he was a full Professor & PI of School of Computer Engineering, the Director of ARtificial Intelligence & Neuro-informatics Engineering (ARINE) Laboratory, and the Head of Department of Software Engineering (2019.08-2021.07), Jiangsu Ocean University from Mar. 2018 to Dec. 2021. In addition, he was a tenure-track Assistant Professor & PI and the Deputy Head (Medical Information Engineering Department) of Shenzhen University (2016.06-2018.03). He received the degrees of B.S., M.S. and Ph.D. from Heilongjiang University (in 2010), Shanghai Maritime University (in 2012 and 2016), respectively. He is a senior member of Chinese Biomedical Engineering Society, a member of Chinese Artificial Intelligence Society, a member of Chinese Neuroscience Society, a member of the board of the Shanghai Association for Noetic Science, a member of OHBM, the Program Committee member of 2018 IEEE ICIA, 2022 Chinese Conference on Biometric Recognition (CCBR), 2025 Pacific Asia Conference on Language, Information and Computation (PACLIC), and the 40th AAAI Conference on Artificial Intelligence (AAAI-26), the Session Chairs of 2017 IEEE ICIA and 2018 ICIS, the Keynote Speaker of 2020 ICMLCA, the Program Committee Chair and Keynote Speaker of 2021 ICBIC, Keynote Speaker of 2022 ICBIC, Guest Associate Editor of Frontiers in Neuroscience and Review Editor of Frontiers in Human Neuroscience and Frontiers in Radiology. He was awarded “Shanghai Outstanding Master Thesis” in 2014 and “Shanghai Outstanding Graduate” in 2012. At his Ph.D. study stage, he was awarded “China National Scholarship for Distinguished Doctoral Students” twice in 2013 and 2015, respectively. He also won 2018 Finalist Winners of Young Scholar Award of the 5th Symposium of Research and Application on Neuroimage and EEG, the second prize of the 4th Lianyungang Natural Science Outstanding Academic Achievement Award in 2018, the Shanghai Science and Technology Progress Award in 2018, the Excellent Instructor of the National University Computer Ability Challenge Award in 2019, the Excellent Undergraduate Thesis Supervisor of Jiangsu Province Award in 2020 and the Excellent Master Thesis Supervisor of Jiangsu Ocean University in 2023. He was selected as the high-level talents of “Six Talent Peaks” in Jiangsu Province in Sep., 2018, Huaguoshan Mountain Talent Plan - Doctors for Innovation and Entrepreneurship (Innovation) of Lianyungang City in Dec., 2019, and the Vice President of Science and Technology of Jiangsu Province in Aug., 2021. His research fields include machine learning and artificial intelligence, brain-machine interface, multimodal signals analysis, medical big data, neurolinguistics and its related disorders, neuroplasticity, brain connectomics, brain diseases, mental health monitoring, natural language processing, etc. He has published over 90 scientific papers in many journals and conferences, i.e., IEEE TMI, J Med Internet Res, J Alzheimer's Dis, IEEE TIM, IEEE TBME, IEEE JBHI, IEEE TNSRE, IEEE Access, Hum Brain Mapp, Magn Reson Imaging, Brain Lang, J Neurolinguistics, Front Neurosci, Front Psychol, AAAI, MICCAI, IEEE ICME, etc. He serves as the reviewer of many top journals such as Nat Comput Sci, Neuroimage, Hum Brain Mapp, IEEE Transactions, MED IMAGE ANAL, etc. 

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
