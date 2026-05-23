Comparative Topic Modelling of Christian and Buddhist Spiritual Texts

Digital Humanities Project

Student: Marina Saleh

Program: Digital and Public Humanities

University: Ca’ Foscari University of Venice



---

Project Overview

This project explores the use of Digital Humanities methodologies for the comparative analysis of Christian and Buddhist spiritual texts. The project combines corpus preparation, metadata organization, TEI/XML encoding, and computational text analysis using Voyant Tools.


The goal of the project is to investigate recurring spiritual and thematic patterns across different religious traditions through digital and computational approaches.

---

Research Questions

What themes recur in Christian and Buddhist texts?

How can computational analysis support textual interpretation?

What are the limitations of NLP for spiritual and historical corpora?

---

Corpus Contents

Christian Texts

Hymn of Jesus

John 21:18

Prayer to St. Raphael

Buddhist Text

The Confession of Sin

---
Project Structure

text

dh-topic-modelling-project/


│── corpus

│    ├── hymn_of_jesus.txt

│    ├── john21.txt

│    ├── st_raphael_prayer_healing.txt

│    └── confession_of_sin.txt



│── metadata.csv

│── john21_tei.xml

│── visuals

│── README.md

---

Metadata

The corpus was organized using metadata in CSV format. Each text was classified according to:

* title

* religious tradition

* genre

* thematic focus

Metadata supports corpus organization and comparative computational analysis.

---

TEI/XML Encoding

A small excerpt from John 21 was encoded in TEI/XML format to demonstrate machine-readable textual structuring within Digital Humanities workflows.

The encoding includes:

* `<TEI>`

* `<teiHeader>`

* `<lg>`

* `<l>`

---

Computational Analysis

The corpus was analyzed using Voyant Tools.

Methods included:

* word frequency analysis

* topic modelling

* semantic links visualization

* trends analysis

* corpus visualization

---

Main Findings

The analysis revealed recurring spiritual themes such as:

* suffering

* morality

* healing

* salvation

* enlightenment

* spiritual transformation


Christian texts emphasized relational spirituality and divine figures such as Jesus and Raphael, while the Buddhist text focused more strongly on purification and enlightenment.


---

Limitations

This project also highlights several methodological limitations in Digital Humanities and computational text analysis.

Small Corpus Size

The corpus contains only a limited number of texts, which restricts the statistical depth of topic modelling and frequency analysis.

Translation Issues

The analysis relies primarily on English translations rather than original languages, which may alter semantic nuance and vocabulary distribution.

Noisy Data

Web-based textual sources may contain formatting inconsistencies or residual non-textual material that can influence computational results.

NLP Limitations

Natural Language Processing tools cannot fully capture symbolic meaning, theological complexity, or spiritual nuance within religious texts.

Interpretative Challenges

Computational methods reveal lexical patterns and thematic trends, but interpretation still depends on human critical reading and contextual understanding.

---

Conclusion

This project demonstrates how Digital Humanities methodologies can support comparative textual analysis through metadata organization, TEI/XML encoding, and computational corpus analysis.

The project also emphasizes the importance of combining quantitative methods with human interpretation when studying spiritual and historical texts.

---

Tools Used

* Voyant Tools

* Oxygen XML Editor

* TEI/XML

* GitHub

---


Sources

Christian Texts

* Sacred Texts Archive
* Bible Gateway
* EWTN

Buddhist Text

* Sacred Texts Archive
