---
title: Webscrapping the BGG Top 50
date: 2024-02-18 
categories: [Python, Webscrapping, Boardgame]
tags: [TAG]     # TAG names should always be lowercase
toc: false
comments: false
---




Board games have become a major hobby in the last 30 years. The board game market has grown 
significantly and is expected to generate over three billion dollars in the US alone. With this
boom in popularity, I thought it would be appropriate to look at and explore the most popular games
according to the website www.BoardGameGeek.com, since it's the leading website for all things relating
to board games. Their website features a top 50 ranking that is updated monthly according to user ratings
of the most popular board games. It also has an extensive database with a ton of information on most 
board games as well as a large community forum that is very active. Luckily there is a forum post that archives
top 50 games since the list began. I thought it would be interesting to look at the games on the list
and how they've changed over the years. I built a webscraper to take all the information from the forum
post and then save all the information in a csv file. The scraper is built in a jupyter notebook and has 3 files.
The main called Web_scrappingTop50.ipynb is the main file that contains the bulk of the code and is the one that
would needed to be run to create your own csv containing the data. The customFunc.ipynb contains several
custom functions that help with extract the information from the webscrapping. The replacingNames.ipynb 
file is there because there are some inconsistencies in how some board game names are written, so to make analysis
easier I preprocess those names so that any analysis done later is not plagued with these issues. 

[![githublink](img/GitHub_Logo_White.png){:width="100px" .light}](https://github.com/Khrono5/WebScrappingBGGtop50)
[![githublink](img/GitHub_Logo_White.png){:width="100px" .dark}](https://github.com/Khrono5/WebScrappingBGGtop50)

[![githublink](img/GitHub_Logo_White.png){:width="100px" .light}]

[![githublink](img/GitHub_Logo_White.png){:width="100px" .dark}]