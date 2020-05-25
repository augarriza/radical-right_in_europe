# Radical-right parties in Europe and their supporters
*DAFT March 2020, Ironhack Berlin, May 22nd*

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Workflow](#workflow)
- [Notebooks Explanation](#notebooks-explanation)
- [Conclusions](#conclusion)

## Project Description
The european political arena has been re-shaped in the last years due to the increasing power of radical-right parties, specially after the refugee crisis in 2015. My main goal with this analysis is to verify whether some prejudices about the people supporting these parties are actually true. 
In order to do that I analised data collected mainly on the last round (2018) of the European Social Survey (ESS): https://www.europeansocialsurvey.org

## Questions & Hypotheses
There are several commonly shared ideas about people voting for radical-right parties. I focused on four:
1. They are uneducated
2. They are uninformed
3. They are struggling economically
4. They dislike immigration

## Workflow
Among all the european countries for which there is data available at the ESS portal, I centered my analysis around 5 and the main radical-parties in them: Germany (AFD), France (FN), Italy (Lega), Poland (PiS) and Hungary (Fidesz, Jobbik). I chose to focus on these countries so as to have different cultural and socio-economic scenarios:
-Germany&France vs Italy vs Poland&Hungary : North vs South vs East
-Germany&Italy vs France: "new" vs "old" phenomenon
-Germany&France vs Poland&Hungary: radical-right in the opposition vs ruling

For all countries, I isolated the individuals who had voted for radical-right parties in the last national elections. In order to bring perspective into my analysis, I also grouped all the individuals who had voted for non right-radical parties into a group of contrast. This way, I could analyse not only the differences in radical-right supporters among countries but also the differences in each country between radical-right and non-radical supporters.

## Notebooks Explanation
#### MULTI_humanvalues_analysis_2018_round9.ipynb
The survey contains a very interesting set of 21 questions about human values. The respondents were asked to indicate on a scale from 1 to 6, how close they feel to the a statement they were presented, 1 meaning they feel pretty much alike and 6, not at all.
To have a look at the questions, go to section H: https://www.europeansocialsurvey.org/docs/round9/fieldwork/united_kingdom/ESS9_questionnaires_GB.pdf
In this notebook, I analyse the average scores of each group at each question.

#### MULTI_immigration_2018_analysis.ipynb
In this notebook I analyse the attitudes of our two groups (analysis vs contract, radical-right vs non-radical) towards immigration through three different questions:
1. Is immigration good or bad for the country´s economy?
2. Does immigration undermine or enrich the country´s cultural life?
3. Do immigrants make the country a worse or better place to live?

#### MULTI_sociodemo_analysis_2018_round9.ipynb
In this notebook I analyse several socio-economical aspects of our two groups:
1. Age
2. Where they live: big city/outskirts of a big city/small city/country village/countryside
3. Years of full-time education completed
4. Household´s total income (10 different deciles).
To check the different deciles for DE, go to "Liste 44": https://www.europeansocialsurvey.org/docs/round9/fieldwork/germany/ESS9_showcards_DE.pdf
The showcards for each country are available at the ESS website (check URL above)
5. Feeling about household´s income

#### MULTI_timenews_2018_analysis.ipynb
In this notebook I analyse the time each group spends watching/reading/listening to news about politics and current affairs (minutes per day).

#### MULTI_trust_2018_analysis.ipynb
In this notebook I analyse the attitudes of our two groups towards politics through four questions:
1. Trust in country´s parliament
2. Trust in politicians
3. Trust in the European Parliament
4. Did the European unification go too far already or should it go further?

#### MULTI_unemployed_analysis_2018.ipynb
In this notebook I checked how many of the respondents where unemployed when they participated in the survey

#### TIMESERIES_Attitudes_towards_immigration.ipynb & TIMESERIES_Trust_in_politicians_and_EU.ipynb
My analysis was based on the answers collected on the last round of the ESS, that took place in 2018. However, in these two notebooks I collected data over time on attitudes towards immigration and politics in order to analyse how they evolved over time. There are 9 different points in time, which correspond to every year in which the survey was conducted:
Round 1: 2002
Round 2: 2004
Round 3: 2006
Round 4: 2008
Round 5: 2010
Round 6: 2012
Round 7: 2014
Round 8: 2016
Round 9: 2018

## Conclusions
Out of my 4 main hypotheses, none could be validated for all countries. Also, there is no country in our analysis for wich all 4 hypotheses could be validated.



