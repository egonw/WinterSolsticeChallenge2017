# Winter Solstice Challenge 2017

Egon Willighagen ([@egonw](https://github.com/egonw)) recently issued an interesting [winter solstice challenge](http://chem-bla-ics.blogspot.nl/2017/11/winter-solstice-challenge-what-is-your.html): calculating your open knowledge score. This is loosely defined as a measure for the openness of your own research output as well as the research you cite. Of course, it can be extended multiple layers deeper, assessing the openness of the knowledge trail leading to your own results. Egon issued a prize both for the highest 'score' and for the best method to calculate the score (including the [openness of the method and the tools/platforms used](https://twitter.com/MsPhelps/status/935180455334334473)). Bravo!

I love winter, I love challenges and I care a lot about open science. So I decided to take this one on. Before starting, I set the following parameters for myself:

- I will only use **fully open tools** (openly available, based on open data, open methodology). As second best, I will consider tools that are openly available, but where the data and/or methodology are not open. I will not use tools that require a paid license, even if provided by my institution;
- I will **make use of my publication record as currently available** in the tools I choose (i.e. I will not update ORCID prior to this exercise, or quickly upload a few of my older papers to a public repository - I might do that afterwards, though!);
- As challenged by Jeroen Bosman, I will **[predict my results beforehand](https://twitter.com/MsPhelps/status/940659850543030273)**;
- I will **not be perfectionist about this**, but rather try to deliver some method and outcome in a reasonable amount of time, for others (or myself) to improve on later.

## Approach

### Step 1: Retrieve DOIs for own research output from ORCID
For this I made use of the [ROpenSci](https://ropensci.org/) package [rorcid](https://github.com/ropensci/rorcid), written by Scott Chamberlain ([@sckott](https://github.com/sckott). 
I used the same package to create a variable for first and last name, to include in the output of the script.  

### STEP 2: Retrieve DOIs for references cited by own output using 
This is why the [Initiative for Open Citations (I4OC)](https://i4oc.org) is such an important development - it can provide a truly open citation corpus to use for any application.  Currently, over [50% of references in CrossRef are open](https://twitter.com/i4oc_org/status/934103494323138560). Have you signed [the petition](http://issi-society.org/open-citations-letter) yet to ask publishers who are dragging their feet to get on board? Currently, over 50% of citations are open.  



### STEP 3: Check OA availability of own output and cited references using OADOI
(degree 0: 34/50=68.0% ; degree 1: 51/190=26.7%; aggregated (68+0.5(26.7))/1.5=54.2%
