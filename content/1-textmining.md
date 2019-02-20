---
title: Text-Mining
nav: true
---
<br>

# What is Text Mining?

<br>

Mathematically rigorous inquiries into the relationship between words in a large corpus of text.

- Text mining helps researchers detect **patterns** and **connections** in large volumes of textual material, allowing them to draw conclusions from a **large body of text** that they would not be able to otherwise read, synthesize, and incorporate into their scholarship.

{% include figure.html img="openbook.jpg" alt="too many books" width="80%" %}

Text Mining is often about **counting words**:
- Words matter
- Words hang together in interesting ways...

{% include figure.html img="painting1.jpg" alt="painting" width="75%" %}

---

## Text Mining involves pattern matching:

- Identify **similarities** in a large corpus
    - Overarching trends across a whole set of texts
    - Association within sets
    - Categorization of new items being added to a set

- Identify **differences**
    - Outliers and anomalies between texts

- Combine the two
    - Clusters of similar groups with indications of outlier groups

---

{% include figure.html img="mine.jpg" alt="mine" width="75%" %}

---

## A Few Types of Text Mining:

<br>

{% capture text %}
- Analyzing a text for a sequence of words
- Possible use: Change-over-time analysis
- Example: [https://books.google.com/ngrams](https://books.google.com/ngrams){:target='_blank'}
{% endcapture %}
{% include card.md text=text title="N-grams" %}
{% include figure.html img="ngram.jpg" alt="mine" caption="Google Books Ngram Viewer" width="100%" %}

{% capture text %}
- Part-of-speech tagging
- Possible use: Extract and categorize entities such as person names, organizations, etc.
- Example: [Six Degrees of Francis Bacon](http://www.sixdegreesoffrancisbacon.com/?ids=10000473&min_confidence=60&type=network){:target='_blank'}
{% endcapture %}
{% include card.md text=text title="Named Entity Recognition" %}
{% include figure.html img="nlp.jpg" caption="Named Entity Recognition" width="100%" %}

{% capture text %}
- Simple approach to analytical partitioning
- Elements of data visualization: size, color, distance of words can be used as elements of argumentation
- Example: [TagCrowd.com](https://tagcrowd.com/){:target='_blank'} or [WordItOut](https://worditout.com/word-cloud/create){:target='_blank'} (try it using <a href="../data/nightingale_text.txt" target="blank">this text</a>)
{% endcapture %}
{% include card.md text=text title="Word Clouds" %}
{% include figure.html img="wordcloud.jpg" alt="wordcloud" caption="A word cloud made with <a target='_blank' href='https://voyant-tools.org/'>Voyant Tools</a>" width="100%" %}
    
{% capture text %}
- Comparing large trends in corpora
- Iterative algorithm identifies a set of topics related to a set of documents
- Example: [Mining the Dispatch](http://dsl.richmond.edu/dispatch/pages/intro){:target='_blank'}
{% endcapture %}
{% include card.md text=text title="Topic Modeling" %}
   
{% include figure.html img="text.jpg" alt="mine" width="75%" %}
{% include figure.html img="topics.jpg" alt="mine" width="100%" %}
{% include figure.html img="soundtopic.jpg" alt="mine" width="100%" %}

---

## Limitations and Errors in Text Mining:
{% capture text %}
1. Be cognizant of your question as you gather data
- Data lies (if it's collected in inappropriate ways). What's in your set?
- Data from NY and LA between 1920-1940 and 200-2010 can't be used to make claims about patterns in the US between 1900 and 2010

2. Be aware of the limits of text mining
- You need computer readable files

3. Be aware of what you can munge
- If your transcription/OCR ([Optical Character Recognition](https://en.wikipedia.org/wiki/Optical_character_recognition){:target='_blank'}) always turns the word "like" into the word "lilce"... consistency in errors is still consistency
{% endcapture %}
{% include card.md text=text %}