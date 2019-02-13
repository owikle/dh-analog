---
title: Text-Mining
nav: true
---

# What is Text Mining?

{% capture text %}
**A research practice that involves using computer algorithms to discover information in large amounts of unstructured text**

OR

**Mathematically rigorous inquiries into the relationship between words in a large corpus of text**
{% endcapture %}
{% include card.md text=text %}

*Text mining helps researchers detect patterns and connections in large volumes of textual material, allowing them to draw conclusions from a large body of text that they would not be able to otherwise read, synthesize, and incorporate into their scholarship.*

Text Mining is often about counting words:
- Words matter
- Words hang together in interesting ways
{% include figure.html img="painting1.jpg" alt="painting" width="50%" %}

---

## Text Mining involves pattern matching:

- Identify similarities in a large corpus
    - Overarching trends across a whole set
    - Association within sets
    - Categorization of new items being added to a set

- Identify differences
    - Outliers and anomalies

- Combine the two
    - Clusters of similar groups with indications of outlier groups

---

{% include figure.html img="mine.jpg" alt="mine" width="50%" %}

## Text Mining Vocabulary

*Mining*:
- Exploratory

*Computational processes*:
- Machine learning
- Training corpus
- Distribution analysis

*Modifying documents for input*:
- Unstructured Text
- Corpus
- Chunks
- Tokens

---

## A Few Types of Text Mining:

<div class="row">
    <div class="col-md-12">
    {% capture text %}
        - Analyzing a text for a sequence of words
        - Possible use: Change-over-time analysis
        - Example: [https://books.google.com/ngrams](https://books.google.com/ngrams){:target='_blank'}
    {% endcapture %}
    {% include card.md text=text title="N-grams" %}
    </div>
</div>
<div class="row">
    <div class="col-md-12">
    {% capture text %}
        - Simple approach to analytical partitioning
        - Elements of data visualization: size, color, distance of words can be used as elements of argumentation
        - Example:
    {% endcapture %}
    {% include card.md text=text title="Word Clouds" %}
    </div>
</div>
<div class="row">
    <div class="col-md-12">
    {% capture text %}
        - Comparing large trends in corpora
    {% endcapture %}
    {% include card.md text=text title="Topic Modeling" %}
    </div>
</div>

---

## Limitation and Errors in Text Mining:
{% capture text %}
1. Be cognizant of your question as you gather data
- Data lies (if it's collected in inappropriate ways). What's in your set?
- Data from NY and LA between 1920-1940 and 200-2010 can't be used to make claims about patterns in the US between 1900 and 2010

2. Be aware of the limits of data mining
- You need computer readable files

3. Be aware of what you can munge
- If your transcription/OCR always turns the word "like" into the word "lilce"... consistency in errors is still consistency
{% endcapture %}
{% include card.md text=text %}