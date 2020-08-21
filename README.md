# Football Analytics Scoreline Analysis

This repository contains a number of personal projects relating to football analytics. They were completed before beginning my Data Science MSc.

## 1) The Most Dangerous Scoreline in Football

"2-0 is the most dangerous lead in football", a phrase that every football fan is sure to have heard more times than they care to count. But why is the use of this phrase such commonplace from commentators and fans alike? and how did it become this way?

The concept behind the phrase is that the winning team may feel too 'comfortable' causing them to lose concentration or become less motivated. This can result in the opposition team scoring a goal to reduce the deficit to just one goal, at which point the opposition team also have the 'momentum' and are more likely to score again. It has also been hypothesised that the phrase may have been coined by broadcasters in an attempt to keep viewers interested in the game. So that's the theory behind the concept, but is there any evidence to support the idea that a two goal lead is in fact dangerous?

This report hopes to answer this very question. To do so, a model will be created with the aim of calculating the probability of each outcome of a football game. That is, by using the minutes played as well as the current scoreline of any given game, find out the probability that a team will win, lose or draw. The result of the model will then be explored.


## 2) How football managers can approach different Game States

The previous report demonstrated a model used to calculate the likelihood of each potential outcome of a game of football (win, draw, loss). The ‘value’ of scoring a goal was found and the model showed that not all goals scored have the same ‘value’. Both the current scoreline and minutes played at the time the goal is scored have an impact on how many more points a team can expect to receive by scoring a goal. In this article these findings will be used to explore a number of game states and discuss possible actions that could be made by managers and coaches in order to increase the number of points they can expect to receive. As the same model is being used, the same scope of inference and limitations from the previous report apply.

Below is the plot showing the number of points a team can expect to receive based on the current scoreline and minutes played in the game. This is identical to the plot from the previous article and will be used to analyse the different game states. The game states that will be analysed are: level game, winning by one goal and losing by one goal (represented by the orange, red and purple lines). These were chosen as they are the most common scorelines and therefore most likely game states for a team to find themselves in.


## 3) In-game results probability model using the Poisson distribution

In a previous report on this blog, the popular phrase ‘2-0 is the most dangerous lead in football’ was investigated. Unsurprisingly to most readers, a two goal lead was found to actually be a very safe lead. However this report did raise the questions: What about the quality of the teams involved? What about home advantage?


The following report aims to showcase a model that will take these factors into account. Using the Poisson distribution, this model will be capable of finding in-game win, draw and loss probabilities at any minute of the game. Data from the first 37 gameweeks of the 2019/20 Premier League season will be used to create the model which will then be used to give in-game win probabilities for any game in the final week. The accuracy of the model will then be discussed.
