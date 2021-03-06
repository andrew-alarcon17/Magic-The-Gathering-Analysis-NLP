# Magic-The-Gathering-Analysis-and-NLP


## Data Description:
This data consists of all the information present on Magic the Gathering cards, such as color identity, converted mana cost, power, toughness, text (description), and rarity to name a few.


## Project Summary:
For this project, I wanted to explore the presence of creatures within each color of mana, along with those that are multi colored, and colorless. Some of the attributes that were visualized were the distributions of power, toughness, and mana cost of creatures.
Another important attribute to a creature is its text (description). These descriptions often tell the ability or abilities that a creature may have. These abilities often can change the behavior of entire matches by being able to chain together a series of moves to be used to your advantage. I wanted the first part of this project to end on a brief look at the descriptions of these creatures, while part two being a bigger deep dive to see if we can predict the rarity type of a creature based only on its description.


## Data Analysis:
Throughout all of the 5 colors of MTG, the power and toughness of legendary creatures and non-legendary creatures were analyzed.

Mana Distributions of All Cards:

<img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Mana%20Distr/Forest.png" width="180"> <img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Mana%20Distr/Island.png" width="180"> 
<img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Mana%20Distr/Mountain.png" width="180"> <img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Mana%20Distr/Plains.png" width="180"> <img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Mana%20Distr/Swamp.png" width="180"> 


Creatures of All Colors (Including Colorless and Multi-Colored)

<img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Multi%20%26%20Colorless%20Creatures.png" width="300"> 

Power and Toughness of All Creatures:

<img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/P%26T%20Scatter.png" width="400"> 


Power Distribution of Legendary Creatures by Color:

<img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Legendary%20Power/Forest%20Power.png" width="180"> <img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Legendary%20Power/Island%20Power.png" width="180"> <img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Legendary%20Power/Mountain%20Power.png" width="180"> <img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Legendary%20Power/Plains%20Power.png" width="180"> <img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Legendary%20Power/Swamp%20Power.png" width="180"> 



Toughness Distribution of Legendary Creatures by Color:

<img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Legendary%20Toughness/Forest%20Toughness.png" width="180"> <img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Legendary%20Toughness/Island%20Toughness.png" width="180"> <img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Legendary%20Toughness/Mountain%20Toughness.png" width="180"> <img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Legendary%20Toughness/Plains%20Toughness.png" width="180"> <img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20Analyzing/Legendary%20Toughness/Swamp%20Toughness.png" width="180"> 

## Findings:
Creatures that were labeled as legendary were correctly predicted as rare cards 86.7% of the time based on the text in its description through the integration of a Logistic Regression Tf-Idf model. In the data analyzing portion of this project, I found that it is not only power and toughness that decides how rare a card may be, so I decided to look further into the descriptions of these creatures. Often, a creature's abilities have the power to alter the bahavior of many turns, and entire games at times.

Below are common words found in rare legendary creatures.


<img src="https://github.com/andrew-alarcon17/Magic-The-Gathering-Analysis-NLP/blob/main/Charts/MTG%20NLP/Rare%20Legendaries%20Word%20Cloud.png" width="400">


