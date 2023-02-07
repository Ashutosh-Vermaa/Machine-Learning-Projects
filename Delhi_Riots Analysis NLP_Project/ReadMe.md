## Aim or Problem Statement
Analysing the political inclination of two media houses- Times of India and The Hindu

<img src="[https://images.pexels.com/photos/3030823/pexels-photo-3030823.jpeg?cs=srgb&dl=pexels-suzy-hazelwood-3030823.jpg&fm=jpg](https://wallpapercave.com/wp/wp4059913.jpg)" data-canonical-src="[https://images.pexels.com/photos/3030823/pexels-photo-3030823.jpeg?cs=srgb&dl=pexels-suzy-hazelwood-3030823.jpg&fm=jpg](https://wallpapercave.com/wp/wp4059913.jpg)" width="700" height="400" />

<!-- ![This is an image](https://images.pexels.com/photos/3030823/pexels-photo-3030823.jpeg?cs=srgb&dl=pexels-suzy-hazelwood-3030823.jpg&fm=jpg) This is another way to upload images. Since this is a comment, it won't reflect in the file -->

## Outline
1. 

## Background
I was interested in examining the political inclination of Indian media houses by analysing a particlular event. I chose two Indian media houses- Times of India (ToI) and The Hindu and the delhi riots 2020 event for my analysis. 

## Data Collection
I used Google news API to scrap the news articles from the two mentioned media houses. I collected the links to the articles containing the key phrase 'Delhi Riots" from ToI and The Hindu. This was followed by retrieving the articles body while interating over all the collected links. 

## Data Cleansing
Data collection was followed by pre-processing or cleaning of the data. As and when required, I applied word tokenization and sentence tokenization, stemming/lemmatization, removed stop words. Moreover, one can consider removing punctuations too which I have not done. 

## Tools Applied
I applied the Named Entity Recognition to get the character names, places and dates. The Character names gives an idea of the important people linked to the event, dates give us the time period around the riots and the places gives us the places linked to the riot site.

Furthermore, I wanted to explore who are being accused of the riots. For that, I used sentence tokenization and searched the sentences that contained the word accused or consiprator. Then, I retrieved the characters using NER from these sentences. Interstingly enough, the names are similar to the names I got from the entire corpus. It shows that the these are the people who are involved in the matter in one or the other way e.g. accused, judges, advocates, witnesses etc.

Next, I used spacy to get the noun phrases that are there in the text. The noun phrases gave an overall idea of the event.
Additionally, I wanted to look at the sub-events or topics in the whole event of Delhi riots. I used topic modelling for the same. I obtained 15 topics from the text, some of them being about pathan poiting gun at the cops, cops being attacked by residents, three accused are being talked about, bodies recovered from drains, Bhagirathi river, school and students etc.
Finally, I visualized the NER tags. The dimension of the vectors of NER tags was reduced using t-SNE and they were plotted using plotly.

## Conclusion
When applied these tools on the two corpora separately, I couldn't find anything that can reveal something about the political inclination of these two media houses. One of the reasons for the same could be that the choice of the event for analysis was not good. Because in case of a tragedy like riots, almost all the media houses will show negative sentiment.

P.s- I have done the analysis on the combined corpus of text of both the corpora since they separately didn't differ in providing insights into the event.



