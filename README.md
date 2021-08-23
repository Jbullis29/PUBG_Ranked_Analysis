# PUBG: BATTLEGROUNDS Analysis

## Do You Know What it Takes to Win?
The 2021 PUBG Mobile Global Championship has a $6,000,000 prize pool. But that's not all the PUBG related money up for grabs. There are also numerous esports betting sites where anyone (including you) can place a wager on most aspects of the game, by staking either real money or in-game items. Hoping to win big, we used machine learning to try to predict the chances of a given player winning. 

## Wait! What Even is PUBG: BATTLEGOUNDS?

PUBG: BATTLEGROUNDS is a battle royale shooter game in which 100 people are pitted against each other, sometimes in teams, to scavenge, kill, and survive. The game ends when only one player (or team) remains. There are multiple maps and players are randomly assigned to maps. 

To begin, you must personalize your character. There are many options available including gender presentation, skin color, and hair color.

The character creation page where [Justin](https://github.com/Justin) is making his character
![alt text](https://github.com/Jbullis29/PUBG_Ranked_Analysis/blob/master/pictures/Justin-toon.jpg)

Once your character looks the way you want it to, you can enter your dashboard. Here you can change your profile to add personal information, choose which style of game you wish to play, make in-game purchases, and other options to enhance and personalize your gaming experience. 

This is [Katie](https://github.com/KStrange89)'s dashboard:
![alt text](https://github.com/Jbullis29/PUBG_Ranked_Analysis/blob/master/pictures/Katie-dashboard.jpg)

Once you have started a game, you are put into a waiting room while other players are added. In the waiting room, you can duel other players without having to be concerned about damage taken effecting gameplay. However, because a key aspect of the game is equipment collection, you begin with no equipment, and so if players choose to duel in the waiting room, they must do so using only punches and kicks. 

When there are 100 players and the game has begun, everyone is in an airplane flying over the map. You then choose where to jump out of the plane. Everyone has a standard PUBG parachute, however alternative parachutes can be purchased in-game for a unique look. 

Here is [AJ](https://github.com/AJ-Paine) in the waiting room:
![alt text](https://github.com/Jbullis29/PUBG_Ranked_Analysis/blob/master/pictures/AJ-waiting.png)

and [TravBZ](https://github.com/Travbz) flying over the map
![alt text](https://github.com/Jbullis29/PUBG_Ranked_Analysis/blob/master/pictures/TravBZ-plane.jpg)

and [Jordan](https://github.com/Jbullis29) flying over a different map
![alt text](https://github.com/Jbullis29/PUBG_Ranked_Analysis/blob/master/pictures/JBZ-plane.JPG)

and [Leah](https://github.com/leahdill) using the standard issue parachute
![alt text](https://github.com/Jbullis29/PUBG_Ranked_Analysis/blob/master/pictures/Leah-chute.jpg)

and [TravBZ](https://github.com/Travbz) with a parachute skin he earned through gameplay
![alt text](https://github.com/Jbullis29/PUBG_Ranked_Analysis/blob/master/pictures/TravBZ-chute.jpg)

After safely landing, you have to get equipment-armor, weapons, vehicles, etc. to use in your fight. There are also consumables that can be used to restore your health. Every few minutes, the playable area shrinks. Any players outside the playable area take continuous damage until they die or reenter the playable area. This forces remaining players closer together and speeds up the game as it becomes harder to hide from the enemy. 

This is just one example of a vehicle that can be driven, courtesy of [TravBZ](https://github.com/Travbz)
![alt text](https://github.com/Jbullis29/PUBG_Ranked_Analysis/blob/master/pictures/TravBZ-car.jpg)

this is [TravBZ](https://github.com/Travbz) on the hunt for better equipment
![alt text](https://github.com/Jbullis29/PUBG_Ranked_Analysis/blob/master/pictures/TravBZ-run.jpg)

and this is [Katie](https://github.com/KStrange89) picking up some equipment
![alt text](https://github.com/Jbullis29/PUBG_Ranked_Analysis/blob/master/pictures/Katie-pickup.jpg)

While skill definitely plays a role in who wins and loses, there is also a certain amount of luck. Was the area you chose to land filled with awesome equipment and few opposing players? Or did you have to fight off a lot of other players for mediocre stuff?

Here we have [Jordan](https://github.com/Jbullis29) displaying both luck and skill
![alt text](https://github.com/Jbullis29/PUBG_Ranked_Analysis/blob/master/pictures/JBZ-winner.jpg)



## What We Did

This project was intended to analyze and visualize data from PUBG matches with the end goal of using machine learning to identify the most important features and predict outcomes based on those features. 

To do this, we utilized Python via Jupyter Notebook to make an API call from PUBG's developer API. Weds cleaned using Pandas before employing [Scikit-Learn](https://scikit-learn.org/stable/index.html) to evaluate different machine learning models. 

We preprocessed the data in [Scikit-Learn](https://scikit-learn.org/stable/index.html) by splitting it into training and test data, scaling where necessary.

We used Tableau and Matplotlib to create visualizations and then built a webpage using HTML, Javascript, CSS and Bootstrap to disply these visualizations.

## Built With
* Bootstrap
* CSS
* HTML
* Javascript
* Jupyter Notebook
* Pandas
* Python
* [Scikit-Learn](https://scikit-learn.org/stable/index.html)

## Deployment
View the deployed webpage here... https://jbullis29.github.io/PUBG_Ranked_Analysis/

## Sources
* PUBG API: https://developer.pubg.com/?locale=en

## Want to Play?
* https://store.steampowered.com/app/578080/PUBG_BATTLEGROUNDS/
* Also available for mobile download (free) in the Apple Store and Google Play Store!

## Wanna Bet?
* https://www.esports-betting.pro/pubg/
* If you might have a gambling addiction, the National Problem Gambling Helpline Network (1-800-522-4700) offers free, confidential help 24/7/365. Don't hesitate to reach out if you might need help.
