# Voyant-Tutorial
>![dsl_logo](https://user-images.githubusercontent.com/46492847/54776994-ab00dd80-4be7-11e9-9849-68a8fe697c15.png)

[@brock_dsl](https://twitter.com/brock_dsl)

Voyant is a web-based, open source text reading and analysis environment. It is designed to facilitate reading and interpretive practices for digital humanities students and scholars. Using Voyant, you can study texts and corpuses from the web or from your own collections. You can also develop your own text analysis tools using code available on their [GitHub page](https://github.com/sgsinclair/Voyant).
This tutorial goes over some of the tools available through Voyant and shows you how to use them with the pre-loaded Shakespeare corpus in Voyant. You can follow along with your own corpus or digitized texts if you'd prefer.

## Getting Started
1. Start by opening [Voyant](voyant-tools.org) in your web browser. There are two ways to open a corpus or text for analysis. The first is to choose **open**. This will give you the option to work with one of the pre-loaded corpuses in Voyant - the complete works of William Shakespeare, and the complete works of Jane Austen. These are good resources if you're curious to see what you can do in Voyant, or if you happen to be working on research about either of these corpuses.
2. To upload your own text or corpus, choose **upload**. From here, choose files from your computer to analyze. Voyant can recognize plain text, HTML, XML, PDF, RTF, and MS Word formats. Depending on how many files you upload, it could take a few minutes for Voyant to create a corpus.
3. Once you've chosen a preloaded corpus or uploaded your own, you'll see your Voyant "dashboard". This tutorial will go in depth into all of the default tools Voyant chooses for you, as well as how you can customize this dashboard to show any visualization tools you want.
> Voyant tools are meant to interact with one another - meaning that if you click on a term in one visualization, the other visualizations 
> will change accordingly. 

## The Cirrus
![image](https://user-images.githubusercontent.com/46492847/54688387-e8843e80-4af3-11e9-8e50-0101b23cbbe0.png)
* A **cirrus** is a word cloud that visualizes the highest frequency words in a corpus
* It provides a convenient, though somewhat reductive view of the content of your corpus
* Hovering over words in the cirrus shows exact word frequency, and clicking on the word will cause other tools to react

![image](https://user-images.githubusercontent.com/46492847/54690920-ca6d0d00-4af8-11e9-8ab9-50b19ad8504a.png)

* The green arrow is pointing to the terms slider. This allows you to adjust the number of words displayed in the cirrus. The minimum number of words you can include is 25, the maximum is 500 words, and the scale moves in increments of 25.
* To make other adjustments to the cirrus like changing the colour palette and the font, choose the options tool - where the pink arrow is pointing
* Voyant creates a cirrus from the whole corpus by default, but you can create a cirrus from just one document in the corpus by adjusting the scale - click where the blue arrow is pointing to do this 

## The Reader
![image](https://user-images.githubusercontent.com/46492847/54691079-06a06d80-4af9-11e9-8bad-fd7c6db1d162.png)
* A **text reader** is exactly what it sounds like - a way to read documents in the corpus
* Text is loaded as needed so as not to overwhelm the system
* The space underneath the text is called the **prospect viewer**. This part shows an overview of the entire corpus, which is helpful when you're working with a large corpus that contains multiple documents
* The bars represent each document in the corpus - length of the document is represented horizontally and vertically, meaning that the taller/wider a bar is, the longer the corresponding document is
* The blue line represents where in the corpus we're reading, and you can click anywhere along the corpus to jump around

## Trends
![image](https://user-images.githubusercontent.com/46492847/54691171-2c2d7700-4af9-11e9-89ce-d96baf015824.png)
* The **trends** tool is a line graph showing a word's distribution across a corpus or text
* Each series is colour coordinated with the word it represents
* You can hover over any point in the graph for information about the point, including the word, the frequency, and the document it occurs in
* To look at trends for one document in a corpus, hover over a point and double click - here you can choose to see trends for either the term you double clicked, or the document

![image](https://user-images.githubusercontent.com/46492847/54691870-66e3df00-4afa-11e9-9e93-635527feb11b.png)

* When you choose this view, the document is separated into segments to make it easier to analyze
* The segments will all be approximately the same length, but you can change the number of segments in the options menu

## Summary
![image](https://user-images.githubusercontent.com/46492847/54691979-9abf0480-4afa-11e9-8a66-7e34805aa03e.png)
* The **summary** tool is a textual overview of the corpus
* Components of the summary tool depend on the length and style of the corpus
* Options for the summary tool include:
  * Number of words per document
  * Vocabulary density per document
  * Average words per sentence in each document

## Contexts
![image](https://user-images.githubusercontent.com/46492847/54692780-ef16b400-4afb-11e9-9f74-b86f004238f0.png)
* The **contexts** tool shows each occurrence of a keyword with a bit of surrounding text
* This tool is a good way to analyze how certain terms are used in different contexts
* Keywords can be changed with the menu

## The Sky is the Limit!
* The tools we just talked about are Voyant's default tools, but there are so many other tools and options to explore!
* These are all of the available tools in Voyant:

![image](https://user-images.githubusercontent.com/46492847/54692853-09e92880-4afc-11e9-9101-a5a49380ade3.png)![image](https://user-images.githubusercontent.com/46492847/54692887-18374480-4afc-11e9-898d-3a9dc1607ffc.png)
* Some of these tools are more useful for analyzing an entire corpus, while others are suited for individual documents
* Play around with some of the tools and see what works best!
* For aesthetics and readability's sake, the Voyant dashboard won't allow you to have more than 5 tools displayed at a time
* To swap one tool for another, choose the windows button at the top of the tool you want to replace

![image](https://user-images.githubusercontent.com/46492847/54692976-3bfa8a80-4afc-11e9-855a-4fb6ff082675.png)
