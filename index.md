## Portfolio

---

### Graph-to-Text Transformation for Utilizing Text-based Transformer Models
[![](https://img.shields.io/badge/GitHub-View%20on%20GitHub-blue
)](https://github.com/barel-guy/Graph-to-Text)

This project explores the potential of transforming graph-structured data into a textual format for processing by traditional Text-based Transformer models. Drawing inspiration from the work by (Dwivedi & Bresson 2021), we diverge from their approach of reconfiguring the transformer architecture to suit graph data, and instead, steer towards manipulating graph data for effective use with text-based transformers. We facilitate this transformation by transcribing the nodes and edges of the graph into a sequential textual format. The Depth-First Search (DFS) algorithm is leveraged to traverse the graph, simultaneously extracting the labels from the nodes and edges. In doing so, we successfully transmute the non-sequential structure of a graph into a format that is well-suited for sequential processing methods. This transformed data is then fed into a standard text-based Transformer, specifically utilizing the LongFormer model. The project was evaluated on the ZINC molecule dataset with the task of graph property regression for constrained solubility. The results were promising, as Text-based Transformers demonstrated a notable ability to interpret and process this restructured data format when presented with transformed graph structures as text sequences.

<img src="images/figure1.png?raw=true"/>



---
### Exploring Israeli Politics through NLP: A Study of Sentiment Analysis and Network Structures in the Knesset
[![](https://img.shields.io/badge/GitHub-View%20on%20GitHub-blue
)](https://github.com/barel-guy/Graph-to-Text)

Transcripts from legislative debates are a potent source of rich data, providing unrivaled access to the sentiments, attitudes, and perspectives of politicians and their respective parties on some of society's most pressing issues. An analysis of such data can provide remarkable insights into democratic processes, making them an attractive focus for researchers across various fields. Recently, there's been growing interest in treating 'text as data' among computer, political, and social scientists. On one hand, computer scientists specializing in Natural Language Processing (NLP) have adapted sentiment analysis methods, primarily developed for analyzing product reviews and blogs, to the political sphere. On the other hand, political and social scientists have begun leveraging computational methods to analyze debate participants' articulated positions. In this context, the transcripts from the Israeli Knesset committees stand out as a unique dataset. As Israel's national legislature, the Knesset plays a crucial role in shaping the country's policies. The committees within the Knesset, responsible for discussing and making decisions on a wide array of subjects ranging from foreign affairs and defense to education, culture, and health, provide a remarkable opportunity to delve into the intricacies of Israeli politics.
In this project, we contribute to this expanding research domain by conducting an in-depth sentiment analysis of transcripts from five Knesset committees. Our starting point is the 'Open Knesset' project, from which we extract the committee transcripts. The sentiment classification for each utterance within these transcripts is performed using the HeBert model, an advanced model based on the BERT architecture tailored for Hebrew. Our analysis proceeds to examine the impact of various factors on sentiment distribution such as time, party affiliation, and the presence of committee chairmen. Furthermore, we illustrate the interactions through comprehensive graph analysis based on sentiment results. Our project aims to provide valuable insights into the emotional dynamics within the Knesset's legislative discussions and debates. We hope that our findings will not only enhance the understanding of Israeli democratic processes but also stimulate future research avenues in this area.

<img src="images/graphs.png?raw=true"/>

---
### Bug Repair Project
[![](https://img.shields.io/badge/GitHub-View%20on%20GitHub-blue
)](https://github.com/barel-guy/Graph-to-Text)

When managing a software project, it is common using a version management system like git and a bug tracking system like Jira. Then, a bug description is added to the tracker when a bug occurs. Each bug description has several textual properties. When a bug is found in a certain function, it can be solved by various changes. For example, any change can be defined by the lines added or removed, the number of functions changed, Etc.
In this project, I would like to find the connection between the description of the bug, the faulty function, and the actions taken to fix the bug to build a Machine Learning model that can recommend those actions.

<img src="images/bug_repair.png?raw=true"/>

---

