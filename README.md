# European_Footabll_Leagues_Machine_Learning_Project

For this project, I work with 2021-2022 season data for the top 5 European football leagues. 
The data was acquired from FBref. 

More info about the data can be found in the Dataset_info and Data_exploration files

The goal of this project was to use machine learning to examine professional footballers by 
their recorded actions rather than just their position.

To accomplish this I used a multi-layered k-means clustering approach to group
players based on different player statistics. See the presentation for a nice visual of the process.

The player statistics spanned Passing, Shooting, Defense, Shot Creating Actions, and Possession statistics.

The project resulted in 12 distinct groups with different shared characteristics. The descriptions of these groups 
and examples of players in the groups can be found in the Project_Presentation file.

An additional and unplanned result of this project was making a similarity function. This function took in a 
player's name and returned the ten most similar players to that player. I was able to use this tool to look
through the data for potential undervalued players. This can be found in the Similarity_Functions file.

Lastly, I have included HTML files with the code and output to make viewing the project easier. Enjoy.
