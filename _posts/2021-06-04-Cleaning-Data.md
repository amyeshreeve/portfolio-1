---
layout: post
title:  "Cleaning & Clarifying Synagogue Data"
date:   2021-06-04 9:06:05
categories: post
---

I used data compiled from the 1900-1 & 1907-8 Jewish Yearbooks and the 1939 WPA Survey of Manhattan, New York to map and understand Jewish organizations in the borough.

## Reasoning and Assumptions

The purpose of this study is to discern historical trends from organization naming patterns. Many of these organizations are synagoges, but others are minyanim, charity societies, or unions.
While I may eventually expand the study beyond Manhattan, I believe this is a fairly representative sample for a few reasons.
First, there are 1,016 Jewish organizations in this data. Their dates of founding range from 1654 to 1939, so the data is capable of showing change of historical change.
I used New York City instead of the United States for two reasons. First, because New York had such a large Jewish community, there were social structures in place that kept track of organizations (like the Jewish Yearbook). 
These social structures kept records because there were so many Jewish organizations that it became necessary to keep a record of them for potential congregants. 
I used this data because it is the data that exists. Secondly, I am using New York because a more concentrated Jewish population means that organizations must diversify their names. 
While many may have originally opted for traditional names (Beth Israel etc.), they needed to distinguish themselves from neighboring organizations. 
It would not be helpful to look at national naming practices because sparsely populated Jewish organizations did not require unique names. 
Even if a clear national dataset did exist, it would not help answer my questions.  


### Duplicates

I am measuring a few things from the data. Most importantly, I am recording the names of the organizations. 
Frequently, there were repeat names in the dataset. If the [Ackman notes](https://genealogy.cjh.org/synagogue-map-resources) suspected a duplicate, I removed the suspected repeat. 
Even if the notes did not notice this, if I found two congregations with similar years of establishment and names, I often removed one.
If the congregations were located on the same street, I assumed they were duplicates.
Even if two names were very similar and had the same year of organization, I kept both organizations if they were geographically distant. 
This is because several organizations identified themselves as being a branch of another organization.  


### Name Errors

Many names included words that appeared to be misspellings of common Hebrew words. I did **not** correct these spellings. I think they display the variety of transliteration common in the time period.
Additionally, it is interesting to see how different groups used different transliterations based on their linguistic backgrounds.

If there was a clear misspelling of an English word, I took the liberty of correcting it, blaming it on the Works Progress enumerator or bad printing technology.  


### Name topics

I created three topics within the organization names. The categories are: names, adjectives, religious indicators, and organizational indicators,
Obviously, these are not clean or separate areas. "Names" refers to proper names, usually those from the Hebrew Bible or Rabbinic history. "Adjectives" refers to Hebrew or Yiddish words in the name
that could describe a congregation. We face one issue already: many of these adjectives work as normal Yiddish names. For example, "Sholem" means peace, and "Klein" means small, but
"Sholem Klein" could be your next-door neighbor. This is an issue for some religious indicators as well. "Relgious indicators" refers strictly to religious nouns. These refer to prayer,
ritual immersion, and religious texts/places. Again, there is not a perfect distinction. "Organizational indicators" refers to words that could explain the type of organization. 
The vast majority of names are mostly in Hebrew. Organizational indicators are the exception because they are often English words (e.g., society, synagogue, association).

Were later synagogues more likely to use religious inicators? Were earlier synagogues more likely to invoke known Biblical figures? These are not clean-cut topics. However, they may be able
to give insight into trends of immigration and assimilation.  


### Year

I recorded the date that these organizations were founded. I based the ‘year’ included in my data on the year of organization instead of the year of establishment when both were included. 
My rationale for this is that the name of the congregation was likely decided upon before property was acquired. 
This date is crucial to the project because it allows for distinctions to be made over time.  


### Location Association

Many synagogues and organizations referenced a European location in their names. This may indicate place of emigration or ideological association.
To date, many Chassidic groups identify themselves with European places they are not from because that is where their ancestors or Rebbe's ancestors were from (Satmar, Bobov, etc.).
I decided, however, that an association with a rabbi indicated a willingness to be associated with the town from which the rabbi originated. 
In cases where there was no noted location and several locations could be assumed from the name, I did not make this assumption myself.
This occured several times because Yiddish names for Eastern European towns are often different from their Polish/Ukranian/Russian names, which are different from the standardized names.

Some groups simply aligned themselves with a nation-state or region. In these cases, I allowed the mapping software (MatplotLib) to place this near the capital.

I labeled organizations with the country where their village or town is now located. While anachronistic, this is more helpful in mapping and interpreting the data in a meaningful way. 
I also recorded the location of each synagogue in New York. This way, I can map immigration/location associated by neighborhood. 
Fortunately, this data was standardized--save two streets, every location still existed.   


### Movement

To track trends among different ideological groups, I tracked both minhag (cultural group) and denomination.
I only noted the denomination if the movement was stated in the record in the Jewish Yearbook. 
Even if something like “Chasidim” was in the name, I did not mark the organization as Chassidic or Orthodox. 
I did not want to impose an anachronistic view of Judaic movements onto these names.  


### Minhag

I assumed that most organizations followed the Ashkenazic minhag unless one of two things was recorded in the data. 
First, I recorded an organization as Sephardic if the Ackman notes or Jewish Yearbook specified that the congregation is Sephardic. 
I also recorded a group as Sephardic if the name of the congregation has some form of the word Sephardic in it (S’fard, S’phardim, etc).

I avoided making extrapolations based upon location because there were many Sephardim living in Eastern Europe as a result of numerous inquisitions.

I regret that my assumptions are inherently Ashkenormative—that is, focused primarily upon Ashkenazi communities. 
However, because Sephardic communities were less common, it can be assumed that Sephardic organizations would be
more likely to identify themselves as such in their name to welcome other Sephardim.  

