---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I’m a final year Ph.D. student at the Department of Computer Science, University of Toronto. My research explores the interplay of language, morality, and AI. I take a multidisciplinary approach drawing on natural language processing, machine learning, moral psychology, cognitive science, and computational social science. My current focus is on developing computational methodologies for understanding temporal and cultural variation in moral values informed by how people use language and AI tools.

Awards
======
* Schwartz Reisman Institute for Technology and Society Graduate Affiliate, 2022-2025.
* Cognitive Science Society Disciplinary Diversity & Integration Award, 2024.
* Schwartz Reisman Institute for Technology and Society Graduate Fellowship, 2021-2022.
* Iran’s National Elites Foundation: Recognized as elite member, 2016-2020.


Publications
======
* Ramezani, A., Stellar, J.E., Feinberg, M., and Xu, Y. Evolution of the moral lexicon. Open Mind (2024). [pdf](https://direct.mit.edu/opmi/article/doi/10.1162/opmi_a_00164/124593/Evolution-of-the-Moral-Lexicon), [code](https://osf.io/mnsjk/?view_only=02b9f8d85b414bc797d51d25ac6801ff)

* Ramezani, A., Liu, E., Lee, S., Xu, Y. Quantifying the emergence of moral foundational lexicon in child language development. PNAS Nexus (2024). [pdf](https://academic.oup.com/pnasnexus/article/3/8/pgae278/7727703?login=true), [code](https://osf.io/knu6s/).

* Ramezani, A., and Xu, Y. Moral association graph: A cognitive model for moral inference. In Proceedings of the 46th Annual
Meeting of the Cognitive Science Society. **Disciplinary Diversity & Integration Award**. [pdf](https://escholarship.org/uc/item/8qj2b5k0), [code](https://osf.io/pe6qt/wiki/home/?view_only=6781f237174a4eb7ae2b0e826fb2fb8c). To appear in topiCS, 2024.

* Ramezani, A., and Xu, Y. Knowledge of cultural moral norms in large language models. In Proceedings of the 61th Annual Meeting the Association for Computational Linguistics: ACL 2023. [pdf](https://arxiv.org/pdf/2306.01857.pdf), [code](https://github.com/AidaRamezani/cultural_inference).

* Ramezani, A., Stellar, J.E., Feinberg, M., and Xu, Y. Evolution of moral semantics through metaphorization. In Proceedings of the 44th Annual
Meeting of the Cognitive Science Society. [pdf](https://escholarship.org/uc/item/668700sf), [code](https://osf.io/mnsjk/?view_only=02b9f8d85b414bc797d51d25ac6801ff).

* Ramezani, A., Liu, E., Ferreira Pinto Jr., R., Lee, S., Xu, Y. The emergence of moral foundations in child language development. In Proceedings of
the 44th Annual Meeting of the Cognitive Science Society. [pdf](https://escholarship.org/uc/item/3qv9h3j9).

* Ramezani, A., Zhu, Z., Rudzicz, F., and Xu, Y. An unsupervised framework for
tracing textual sources of moral change. Findings of the Association for Computational Linguistics: EMNLP 2021. [pdf](https://aclanthology.org/2021.findings-emnlp.105.pdf), [code](https://github.com/AidaRamezani/moral-source-tracing).



Education
======
* Ph.D. in Computer Science, University of Toronto, September 2020 – Present
* B.S. in Computer Engineering, Sharif University of Technology, September 2016 - July 2020


<!-- A data-driven personal website

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
