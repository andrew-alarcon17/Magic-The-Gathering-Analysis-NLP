# Magic-The-Gathering-Analysis-and-NLP


## Data Description:
This data consists of all the information present on Magic the Gathering cards, such as color identity, converted mana cost, power, toughness, text (description), and rarity to name a few.


## Project Summary:
For this project, I wanted to explore the presence of creatures within each color of mana, along with those that are multi colored, and colorless. Some of the attributes that were visualized were the distributions of power, toughness, and mana cost of creatures.
Another important attribute to a creature is its text (description). These descriptions often tell the ability or abilities that a creature may have. These abilities often can change the behavior of entire matches by being able to chain together a series of moves to be used to your advantage. I wanted the first part of this project to end on a brief look at the descriptions of these creatures, while part two being a bigger deep dive to see if we can predict the rarity type of a creature based only on its description.


## Data Analysis:
Throughout all of the 5 colors of MTG, the power and toughness of legendary creatures and non-legendary creatures were analyzed.

Mana Distributions of All Cards:



Creatures of All Colors (Including Colorless and Multi-Colored)


Power and Toughness of Legendary Creatures:


## Findings:
Creatures that were labeled as legendary were correctly predicted as rare cards 86.7% of the time based on the text in its description through the integration of a Logistic Regression Tf-Idf model. In the data analyzing portion of this project, I found that it is not only power and toughness that decides how rare a card may be, so I decided to look further into the descriptions of these creatures. Often, a creature's abilities have the power to alter the bahavior of many turns, and entire games at times.

Below are common words found in rare legendary creatures.


<img src="https://github.com/andrew-alarcon17/Movie_Genre_Prediction/blob/main/Movie_Plots_Vis/Heatmap_crop.png" width="500">


