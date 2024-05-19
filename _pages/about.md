---
permalink: /
title: "[![Typing SVG](https://readme-typing-svg.demolab.com/?lines=Hello%F0%9F%91%8B%2C+I'm+Jainish+Savaliya,+an+AI/ML+Enthusiast!;Welcome+to+my+Website&width=2000)](https://git.io/typing-svg)"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---




This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).


![Illustation](/images/Illustation.jpg){: .align-right width='300px}

About Me
======

🔍 **Data Scientist** with expertise in machine learning, statistical modeling, and big data engineering. Skilled in orchestrating end-to-end data pipelines, extracting insights from complex datasets, and developing predictive models to drive data-driven decisions. Adept at utilizing cutting-edge tools and technologies including Python, R, SQL, PySpark, TensorFlow, Hadoop, Spark, and cloud platforms like AWS.

📈 Proven ability to design scalable data solutions, exemplified by developing a high-performance pipeline to process 500GB of Reddit data with 98% accuracy. Experienced in transforming raw data to optimized formats like Parquet, accelerating query performance by 20%. Proficient in applying advanced analytics techniques like ensemble modeling to achieve over 80% predictive accuracy.

🚀 Committed to tackling intricate data challenges and delivering impactful, visualized insights. Previous projects encompassed domains like ecommerce analytics, urban taxi optimization, music streaming pipelines, and healthcare cost prediction. Passionate about leveraging data to solve real-world problems and consistently driving quantifiable improvements of 10-25% in key metrics.

🤝 Possess strong technical skills complemented by excellence in communicating complex findings to diverse stakeholders. Looking to leverage my interdisciplinary expertise to unearth innovative data-driven solutions in a collaborative team environment.

---

### Skills

- **Methodologies:** SDLC, Agile, Waterfall
- **Programming:** Python, R, SQL, PySpark, Scala  
- **ML/AI:** TensorFlow, PyTorch, scikit-learn, Linear/Logistic Regression, Decision Trees, Time Series, Ensembles, Deep Learning
- **Data Engineering:** Spark, Hadoop, Hive, Airflow 
- **Cloud:** AWS (EC2, Lambda, S3, RDS, etc.), Docker
- **Databases:** MySQL, PostgreSQL, MongoDB, Cassandra
- **Visualization:** Tableau, Power BI, Matplotlib, Seaborn  
- **Tools:** NumPy, Pandas, SciPy, VSCode, PyCharm, Sagemaker, Git

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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
