---
title: "Challenges in Statistical Analysis of Data Collected by a Bandit Algorithm: An Empirical Exploration in Applications to Adaptively Randomized Experiments"
authors: 
- Joseph Jay Williams
- Jacob Nogas
- admin 
- Hammad Shaikh
- Sofia S Villar
- Audrey Durand
- Anna Rafferty
date: "2021-03-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Challenges in Statistical Analysis of Data Collected by a Bandit Algorithm: An Empirical Exploration in Applications to Adaptively Randomized Experiments"
publication_short: ""

abstract: Multi-armed bandit algorithms have been argued for decades as useful for adaptively randomized experiments. In such experiments, an algorithm varies which arms (e.g. alternative interventions to help students learn) are assigned to participants, with the goal of assigning higher-reward arms to as many participants as possible. We applied the bandit algorithm Thompson Sampling (TS) to run adaptive experiments in three university classes. Instructors saw great value in trying to rapidly use data to give their students in the experiments better arms (e.g. better explanations of a concept). Our deployment, however, illustrated a major barrier for scientists and practitioners to use such adaptive experiments, i.e., a lack of quantifiable insight into how much statistical analysis of specific real-world experiments is impacted (Pallmann et al, 2018; FDA, 2019), compared to traditional uniform random assignment. We therefore use our case study of the ubiquitous two-arm binary reward setting to empirically investigate the impact of using Thompson Sampling instead of uniform random assignment. In this setting, using common statistical hypothesis tests, we show that collecting data with TS can as much as double the False Positive Rate (FPR; incorrectly reporting differences when none exist) and the False Negative Rate (FNR; failing to report differences when they exist). We empirically illustrate how and why this occurs–maximizing rewards can lead to biased estimates of arm means (which increases false positives), as well as reduced confidence in estimates of means (which increases false negatives). We find that even when two arms have equal reward, TS can misleadingly allocate many participants to one arm. We show this problem persists using different statistical tests and a Bayesian analysis of the data. We show how two methods for incorporating knowledge of the bandit algorithm into the statistical test can help, but do not eliminate the issues in drawing inferences from adaptive data collection. These empirical results illustrate the nature of the problems to be solved, for more widespread application of bandit algorithms to adaptive real-world experiments, by incorporating statistical considerations into applying, developing, and evaluating bandit algorithms.

tags:
- Source Themes
featured: false

links:
- name: Custom Link
  url: https://arxiv.org/pdf/2103.12198.pdf
url_pdf: https://arxiv.org/pdf/2103.12198.pdf
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

