# NYT: Topic Modeling New York Times censorship articles, 1914-1918

### Introduction
This natural-language processing project, still in construction though with workable code, uses Python packages 
to read in OCR-based .xml files of ProQuest's historical database of New York Times articles.
I am grateful to the University of Chicago Regenstein Library's staff for giving me access to this data while I was still a MAPSS student as
well as to a fellow student and friend in the MACSS program (anon for now until this project is cleaner and more presentable
following further future collaborative work) who introduced me to the exciting world of natural-language processing.

### Context, Data
This project began as a final project for a UChicago course on the history of censorship. The goal was to
use innovative methods such as Latent Derelict Allocation which have only recently been introduced into the
digital humanities and historical methods in particular. The code reads in the .xml files, filters them
for only articles containing the words 'censor' and 'censorship' (of course one could exeriment with these limit words
more in the future), and extracts their years. We can then check the frequency of censorship articles per year over time
from the data's range of 1877-1922.

### Project Design, Contribution
Given this wide range of dates, I ultimately narrowed down the date range to 1914 to 1918 (roughly during the First World War).
Checking the long-run frequencies of 'censor'/'censorship' related articles, I saw a massive spike in the number of articles
during this time--not surprising given historical research of censorship during the period, but to visualize the
number of articles quantitatively was astounding and never previously computed. Using LDA, topic models of the full
five-year period were found in addition to topic models for each individual year. Such topic models can help historians
to see latent themes across the articles which could prove to be useful exploratory and hypothesis-generating objects
for historians in the future. NLP has been increasingly used in social scientific and humanities methods from survey analysis to
the study of literature; I would love to contribute to its use in historical method in the future, not as a replacement but
as an innovate supplement to already-existing methods.

### In Progress
More details and files containing more specific findings soon to come.
