# Partisan bias in political news reporting during election periods in Taiwan and the US
This research project delves into the pervasive issue of media bias during election periods, focusing on the United States and Taiwan. By employing various quantitative methods and curated datasets, the study seeks to address key research questions surrounding the extent of partisan bias, identification of biased keywords, and a cross-country comparison of media bias. The project's preliminary findings suggest that while both countries exhibit similar biases, the nature and degree of polarization differ, with news outlets primarily covering candidate-focused issues rather than party-focused ones. By shedding light on the role of media bias in shaping public opinion within politically polarized contexts, this study contributes significantly to the fields of data science and political communications.

## Background
* The 2020 US presidential election was a highly contested and polarizing event, exposing deep political divisions within the country
* The 2020 Taiwan presidential election was characterized by a polarized political climate, influenced by the 2019 Hong Kong protests and the values of democracy and the China challenge.
* Taiwan's polarization is largely driven by issues related to national identity and cross-strait relations with China, the US's polarization is more focused on issues related to race, immigration, and economic inequality
* Media bias in news coverage played a significant role in influencing the election outcome.
→ Examining the role of news bias in shaping public opinion is essential in understanding the election outcomes in both countries
<img src="img/background.png?raw=true"/>

## Research questions

1. To what extent do conservative and liberal media outlets exhibit news media bias in their coverage of the presidential election?
2. How does this bias compare to publicly funded non-profit news media?
3. What are the most likely biased keywords in news coverage of the presidential election?
4. Which country exhibits more media bias, Taiwan or the United States?

### My Hypothesis:
**the performance of classification models is good**
→ **Easier to find difference between news sources**

## Data sources


* "NELA-GT-2020" dataset from Harvard Dataverse
    * a large multi-labeled news dataset for the study of misinformation in news articles
    * contains nearly 1.8M news articles from 519 sources collected between 01/01/2020 and 12/31/2020
    * has a subset collection of election news articles from 403 different media.
* I chose the news articles from FOX news, CNN, and PBS,
    * 7663 observations from CNN 
    * 3926 observations from Fox news
    * 2280 observations from PBS