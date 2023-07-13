# US News Outlets Dataset

Welcome to the News Outlets dataset! Here you will find a comprehensive list of (mostly U.S.) news sources operating Facebook. This list encompasses well-known established news domains as well as under-the-radar Facebook pages that assert themselves as news providers.

In total, we have gathered 12,638 distinct news domains associated with 14,451 Facebook pages. These news sources, along with their corresponding Facebook pages, are actively monitored by the [CheckMyNews extension](https://github.com/CHOUAKIsalim/CheckMyNews) to collect the news-related posts received by users. 


# Dataset Description

The dataset contains two types of news outlets:

## 1. Established News Sites: 
These are news outlets that have been extensively reviewed and surveyed by independent data providers, namely News Guard and Media Bias Fact Check. The Established News Sites list contains 4,149 news domains associated with 4,323 Facebook pages.

## 2. Under-the-Radar News Sites: 
This list includes web domains that are linked to Facebook pages claiming to be news organizations, irrespective of their reputation and popularity. It includes all Facebook pages that promoted political ads from June 2018 to June 2020 and identified themselves as "News Media." Additionally, we extracted the corresponding websites mentioned in the "About" sections of these Facebook pages. The list contains 8,489 distinct domains associated with 10,128 Facebook pages.

# Usage
The "news_outlets_dataset.csv" file contains the comprehensive dataset of news outlets. Each line in the CSV file represents a Facebook page that claims to be a news provider, at the moment of our data collection. The file is structured with the following six columns:

1. page_id: This column contains the unique Facebook identifier of the Facebook page.
2. url: This column provides the link to the respective Facebook page.
3. domain: This column represents the associated website linked to the Facebook page. In most cases, this domain corresponds to a news domain, as the Facebook pages claim to be news sources.
4. type: This column indicates whether the news source is classified as "established" or "under-the-radar".
5. partisanship: This column represents an aggregated evaluation of the political orientation of the news source. This information is aggregated based on the assessments from Media Bias Fact Check and News Guard. Thus, it is only mentioned for established news sources.
6. quality: This column offers an aggregated evaluation of the news source's quality, categorized as "Factual," "Misinformation," or "Mixed". This evaluation is sourced from Media Bias Fact Check and News Guard and is available only for established news sources.


# Contact
For any inquiries or further information regarding this project, please contact salim.chouaki@inria.fr.


We hope this dataset proves to be a valuable resource for researchers and analysts in the field of news media studies. Feel free to utilize it for research, analysis, or any other purpose you deem appropriate. 





