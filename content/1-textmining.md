---
title: Text-Mining
nav: false
---

# What is Data Mining?

Pattern matching
- Identify similarities in a large dataset
    - Overarching trends across a whole set
    - Association within sets
    - Categorization of new items being added to a set

- Identify differences
    - Outliers and anomalies

- Combine the two
    - Clusters of similar groups with indications of outlier groups

Example:
- Francis Bacon

# Data Mining Vocabulary

Computational processes
- Machine learning
- Training corpus
- Distribution analysis
- NLP (natural language processing)

Modifying documents for input
- Corpus
- Chunks
- Tokens

Metadata

# How does Data Mining Work?

An example of distribution analysis in topic modeling: *Latent Dirichlet Analysis (LDA)*
1. Randomly assign each word in the corpus to a topic
2. Look at Word 1 in Topic A from Document X. Assume all other words in Topic A and Document X are properly distributed.
    - How often does Word 1 appear in Document X? How often do the other words in Topic A appear in Document X? Multiply these together (with some statistical fudging).
    - Do the same calculations for all topics with Word 1 and Document X. With each topic, create a probability curve by comparing probabilities with the probability created using Word 1/Topic A/Document X.
    - If the probability curve is more certain for one of these topics, move Word 1 into the new topic. If not, leave it in Topic A.
3. Repeat ad nauseam.

Example: 
- Hearing topics

# Different Kinds of Text Mining
<div class="row">
    <div class="col-md-4">
    {% capture text %}
        - Basic in-classroom use
    {% endcapture %}
    {% include card.md text=text title="Word Clouds" %}
    </div>
    <div class="col-md-4">
    {% capture text %}
        - Basic in-classroom use
    {% endcapture %}
    {% include card.md text=text title="Word Clouds" %}
    </div>
    <div class="col-md-4">
    {% capture text %}
        - Basic in-classroom use
    {% endcapture %}
    {% include card.md text=text title="Word Clouds" %}
    </div>
</div>


N-grams
- One element of corpus linguistics
- Basic in-classroom use or simple change-over-time analysis

Corpus Linguistics
- Advanced in-classroom use
- N-grams with more flexibility
- Concordance comparison
- Comparing smaller differences in copora (keyness)

Topic Modeling
- Advanced in-classroom use
- Comparing large trends in corpora

Adding Natural-Language Processing
- Part-of-speech tagging
- Dependency parsing
- Named Entity Recognition (NER)

# Limitations and Errors in Data Mining

Be cognizant of your question as you gather data
- Data lies (if it's collected in inappropriate ways). What's in your set?
- Data from NY and LA between 1920-1940 and 200-2010 can't be used to make claims about patterns in the US between 1900 and 2010

Be aware of the limits of data mining
- You need computer readable files

Be aware of what you can munge
- If your transcription/OCR always turns the word "like" into the word "lilce"... consistency in errors is still consistency

# Introduction

One amazingly useful GitHub feature is [GitHub Pages](https://guides.github.com/features/pages/){:target='_blank'}.
It provides free static web hosting from any repository.
Gh-pages is intended to host relatively simple sites for your GitHub portfolio, project, or documentation.
Because it is free and a valuable transferable skill, this is a great option for teaching and learning.

Many organizations are using GitHub to collaboratively create and publish public workshop websites. 
For example: 

- [Programming Historian](http://programminghistorian.org/)
- [Software Carpentry](https://software-carpentry.org/), [Data Carpentry](http://www.datacarpentry.org/), [Library Carpentry](https://librarycarpentry.org/)
- this site!

{% capture text %}Note:
There are *soft* limits and guidelines for gh-pages usage: sites should be < 1GB, use < 100GB bandwidth per month, and make < 10 builds per hour.
If your site exceeds these quotas, GitHub will send you a notice asking you to modify the repository.
All content must follow the [community guidelines](https://help.github.com/articles/github-community-guidelines/), e.g. no violence, obscene sex, or illegal stuff.{% endcapture %}
{% include alert.md text=text color=secondary %}

# workshop-template-b

`workshop-template-b` is a Jekyll project to create a simple workshop website, with a [Bootstrap](https://getbootstrap.com/){:target='_blank'} theme, designed for hosting on [gh-pages](https://pages.github.com/){:target='_blank'}.

It works best for about 5 pages of instructions, plus index, all written in Markdown. 
The navigation to the main pages is exposed at top and bottom of each page for easy stepping through the lessons.

## Why?

Rather than making slides for a workshop, why not make a website? 
It's easier to write, access, share, and reuse. 
GitHub and gh-pages makes this super easy.

It is a better [Open Educational Resource](https://en.wikipedia.org/wiki/Open_educational_resources){:target='_blank'} since anyone can easily fork and adapt!
