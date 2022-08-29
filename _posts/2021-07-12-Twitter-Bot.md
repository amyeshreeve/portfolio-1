---
title: "This Used to be a Synagogue Bot"
layout: post
date:   2021-07-12 11:00:00
categories: post
---

This is (for now) the final installment in my synagogue data analysis. Using the data I gathered, I constructed a Twitter Bot using Twitter and Google APIs. This bot posts Google Streetview images of the places where synagogues and Jewish organizations used to be located.  
Find the bot [here](https://twitter.com/OldShulSpots).

## Construction

This bot is based on the [everylotbot developed by Neil Freeman](https://github.com/fitnr/everylotbot). Initially, I geocoded the recorded addresses with [geopy](https://pypi.org/project/geopy/). Then, I used [SQL Alchemy](https://www.sqlalchemy.org/) to convert my .csv to an SQL database.  
To create the bot, I created a Twitter developer account and got my project approved. I needed the Twitter API key to automate tweeting. I also needed a fresh, new Twitter account to post on.  
I also needed a Google Streetview API. I created a developer account. This API takes the streetview images for coordinates so I don't have to manually gather these images.  
Then, I tested the bot!

## Okay...but why?
We've gotten through the technical stuff. I used a bunch of APIs and little Python packages to make my known addresses into tweets with pictures. But why?  
This project is an example of commemorative geography. It is one thing to see a list of 1,016 addresses and recognize that they are in New York. It is another thing to see the places where Jewish immigrants used to gather.
People following this bot get regular reminders that New York City used to be...different. Different people lived and gathered there and had a different way of life. This bot encourages people to explore their own cities and wonder "What used to be here? Who gathered here?"  
This also encourages us to consider the city as an immigration destination. The way Jewish immigrants were geographically subjugated is the same way other immigrant groups are treated now.  
Finally, this bot lets us take a look at the sheer number of small organizations that used to make their homes in apartment buildings. Now, most people go to a synagogue to gather. In a different time, people held morning minyan in their neighbor's cramped apartment. Judaism was
less centralized. Of course, these geographically linked relgious communities still exist in New York. Crown Heights, Borough Park, and Williamsburg are famous for their Charedi/Chassidic communities. These communities are often still named for European locations (i.e. Lubavitch for Lyubavichi, Satmar for Satu Mare, and Bobov for Bobowa).  
What changed? It seems that for some, the more closely they follow Orthodox tenents, the more important they find a particular location. Is this perhaps a way of holding onto the past? A way of hoping for a similar future?

## Future of the project
I hope to gain access to records for the other boroughs of New York, especially Brooklyn, so that I can perform similar analyses. Because Manhattan had such a centralized Jewish community, many people were keeping records. This doesn't appear to be the case in Brooklyn until a later date.  
I also hope to do topic analysis for the names of synagogues in my current dataset. (This was actually the original intent of this project!) There may be nothing of significance in the names other than geographic indicators, though.