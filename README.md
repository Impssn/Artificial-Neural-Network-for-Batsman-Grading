#  Artificial-Neural-Network-for-Batsman-Grading :
Nowadays the IPL (Indian Premier League) is getting popular and the Auction 
in which the players for their sides are bought by all of the Franchises is also 
an important Key Factor. So in this Algorithm we will be helping those 
Franchises predict the performance of each Batsman in the upcoming Season 
by giving all the Batsmen a Grade (‘A’ or ‘B’ or ‘C’). This is done by using 
the IPL Batsman Rank list, Orange-cap list (Top 10) for the previous half 
decade and the Total runs scored by each Individual Batsman in the Last 
Season.

#Methodology used :
➔ A maximum mark of 5 would be given to the most run scorer list (i.e. the 
top 10 batsmen will be getting 5, 10-25 will get 4, 25-50 will get 3, 50-75 will get 
2 and 75-100 will get 1).
➔ A player will get 10 marks for each time he appears in the Orange-cap list 
at the Top 5 , A player will get 5 marks for each time he appears in 5-10 
positions in the Orange-cap list.
➔ A player will get 0.5 marks for each percent of runs that he has contributed 
in the Total Team runs for the entire Season (Only previous season) and will 
get 1 mark for each percent of runs in contribution of Total runs scored by his 
Team in all the Winning matches.

#Output :
➔Players of ‘1’ Grade(Grade A) perform exceptionally well and of ‘2’ Grade (Grade B) perform in 
2.5 or 3 matches out of 5 finally the ‘0’ Graded (Grade C) player performs only Rarely and is not much reliable.

#Clustering Algorithm used :
➔We use K-means Clustering Algorithm for this Machine Learning Model Implementation
