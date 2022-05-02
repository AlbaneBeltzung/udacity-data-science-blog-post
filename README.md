# udacity-data-science-blog-post

This is the repo for my "Write a Data Science Blog Post" project for the Udacity Data Scientist Nanodegree Project.

1) Business Understanding
There are common debates in the IT world, for which it seems hard to find the correct response. Debates range from the hardware equipment (mechanical or silent key board), operating systems (iOS, Windows, Linux), or coding standards (tab or space). It does however, also reach to our spoken langugage. In this analysis I would like to investigate the pronounciation of the file type .GIF.

There are three most used ways to pronounce it. Having said that, the majority of IT specialists seems to use one of the two top options.
* .GIF with a hard G like "gift"
* .GIF with a soft G like "jiff"
* .GIF where each character is being pronounced G.I.F.

In order to investigate the right pronounciation we need to understand what is the global preference. Furthermore, since there's usually not one global right way, I would like to include the underlying language family. For this purpose I am going to integrate country related data in this analysis and hope to answer these three questions:
a) What's the globally preferred way to saying GIF? 
b) Are there any language specific preferences to the pronounciation?
c) Can you derive someone's country of origin based on their .GIF pronounciation?

2) Data Understanding
The data in use comes from the Stackoverflow yearly survey. Each row represents a respondents answer to the survey.

3) Prepare Data
We prepared the data by gathering and assessing it. After these two initial steps I moved forward with cleaning the data in order to make it the most usable for answering my queries.

4) Data Modeling
Data visualisation were performed usinng matplotlib and seaborn libraries.

5) Evaluate Results
The analysis lead to the following answers per question:
a) The global preference to pronounce .GIF is with a hard g.
b) Taking in example european responses only, and applying a mapping from Country to a countries indo-european language family, there were clear differences to be recognized depending on the underlying family langugage.
c) For the last question we looked into group of Countries speaking a derivative of italic-romance language. Even in this group I could find disparities.  Gallo-iberian (French) and italo-dalmatian (Italian) spaces would pronounce a soft G, whereas the ibero-romance area (Spanish, Portuguese) would use a hard G. The answer is therefore a shade of grey. It is not directly possible to predict someone home Country by hearing them pronounce GIF - but inside Europe it's possible to make strong, geopolitical area assumptions.





