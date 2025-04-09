# Introduction
Recently I had applied to a Data Analytics internship for the Antlanta Braves where the final question of the application was " Who is the most underrated player in the MLB?". With the Mets recently signing Clay Holmes at that time and moving him to starting pitcher it got me thinking. It feels that when we look intto hitting we consider the matchups of hitters versus specific pitchers and different analytical approaches that tell us where a batter should be hitting in the lineup and if they should be facing a specific pitcher. But when it comes to pitching it feels almost archaic that pitchers are given specific lengths of the game based on their positional roles and sometimes has no analytical backing. My argument in that application, and what I want to look into in this project is that what if there is a more efficent way for team to strategicly use their pitching staff. If we knock down the contructs of positional value and purely look at their abilities inning to inning over a large scale, we might be able to see that there are more efficent ways to go about this. 

# What I am going to do
My plan is to build a model that calculates a pitchers FIP per inning pitched. I am using FIP instead of ERA to try and be able to nail down a pitchers efficeny outside the team they play for and solely look at their personal efficency on a per inning basis. This will also work outside the constructs of intangibles as every inning has the same intrinsic value as the rules apply the same during every inning of baseball. 

# Some issues I will definetly run into
Because of the style of managerial success in baseball, certain relievers will have marginal advantages over starting pitchers. This is because of the fact that managers will throw lefties against lefties, making the same hitters other pitchers face statistically worse, even though the pitcher might not inherently be anny better. 
