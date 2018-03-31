# Music Analysis


Name of Group: Group 4 (NoName)

Team Members: Christine Syvertson, Madhav Vadalia, Reena Daniel, Anthony Cusumano

# Project Description/Outline:

Our group is looking to analyze why music is popular. We will take popularity charts from Billboard and Spotify sites. We will combine these lists with the Spotify API and Lyrics database to get additional attribute information about these songs. We will compare how these attributes influence popularity. Our final analysis will compare how these songs and attributes change over time.

Datasources:
-Billboard 1964-2015 Songs + Lyrics from Kaggle
	-Description
		-50 years of Billboard Year-End Hot 100
		-Scraped from wikipedias entry for year end songs
		-5100 rows
	-Uses: Analysis of popular songs over time

-Spotify's Worldwide Daily Song Ranking from Kaggle
	-Description: 
		-2017 - 2018 daily top songs from multiple regions
		- +2,000,000 rows
	-Use: Analysis of popular songs

-Spotify API
	-Description:
		-Contains track, album, and usage characteristics
		-Can use to pull label information
	-Use: Pull additional attribute data of popular songs (as needed)

-Lyrics Database from www.UsableDatabases.com
	-Description
		-9,820 Artists
		-115,338 Songs
	-Use: Sentiment analysis within lyrics

Research Questions to Ask:

- What characteristics of a song make it popular over time
	- influenced by label?
	- influenced by Genre?
	- influenced by region?
	- influenced by Sentiment of the lyrics?

Rough Breakdown of Tasks:
-Get API Key for Spotify
-Get Datasets in csv 
	-Lyrics Database
	-Spotify's Worldwide Daily Song Ranking from Kaggle
	-Billboard 1964-2015 Songs + Lyrics from Kaggle

-JOIN Lyrics Database to Spotify Song Rankings (for sentiment analysis)
-JOIN Billboard to Spotify API to get metadata about genre and label
-JOIN Spotify Song Rankings to Spotify API to get metadata about genre and label

-Do Vader Analysis to get a sentiment analysis of the songs

-Answer Research Questions using visualizations
	-ideas:x-axis is time; y-axis is influence category