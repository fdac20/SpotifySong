# SpotifySong Final Report 

## Objectives:

For this project, we wanted to be able to show the similarities between Spotify user's music taste, using their common genres. 

## Data we used: 

We ended up using the Spotify API to gather a user's fifty top artists, which we then gathered each artists genre from, using Spotify's description of genres. 

## Models and Algorithms:

Since Spotify returned the list of genres fairly jumbled, we had to put in some work consolodating all the returned data into a usable format, so we counted each instance of a genre and then made a dictionary of each genre matching to the amount of times appreared.
After we had a count of every genre for each user, we also had a running total of the amount of genres a user listens to in their top 50 artists. By dividing the common genres by the total amount of genres for both users, we could come up with a percentage similiarity between two users.

## Primary Issues: 

We encountered a fair amount of issues when working on this project. A large one was simply working with node.js, which none of the team was quite familiar with, but the Spotify API used it so we learned as we went. 

We believe there to be two main issues with the data:

1. Genres are too specific and inaccurate 
Since we relied on the Spotify API to return the list of genres to us, we relied on it for comparisons. In the end this resulted in overly specific genres which we believe weren't entirely accurate to the artist. 

2. Comparison between two users is a fun statistic, but is trivial as far as data analysis goes
Comparing only two users is quite simple, and adding more users to compare to concurrently could be very beneficial in showing the data. A user could see how obscure their music taste in comparison to everyone who's signed in and linked their account, with more statistics and visualizations being available the more users signing up.


## Future Work: 

There is a solid amount of extra work that could improve our project. For one, consolodating genres that are similar would more accurately display results. For example, if one person has several different rap genres like Atlanta hip hop and Chicago hip hop, realisitcally, both of those genres could simply be considered hip hop for the sake of comparison. There would have to be some math to futher increase accuracy of results depending on exact genre matches, but some genres that Spotify returned seemed so non-descript. of the artist it lead us to believe that some genres existed for a just a few a rtists. 

We also in the future wished to have more stats than simply a percentage. Seeing how many artists or even songs you share of your top 50 would be a fun and interesting stat for users to see. These would be relatively easy to implement, but we believe the comparisons could go even further. Song statistics outside of genre would be intriguing comparisons, like comparing how much instrumental vs lyrcial content each user listens to, the BPM of their tracks, the time of day they are listening to music, how many hours in general, etc. There are lots of stats to unpack, and depending on how robust the Spotify API is, there could be a large selection of data to comb through for users to compare themselves with.

If users could add themselves to the large dataset of users inside our database, then they could compare music taste with all other users. There would have to be a base user that bases the comparisons for all others, but it could be fairly interesting to see if you have a more obscure music taste than other users that have used our web app.

Lastly, we believe some visualizations could really improve the the application. Graphs showing how similar the data is could really solidify the point our data makes, and would also be interesting and fun to look at for any users. 

## Org Chart:

Jared 
Kishan
Kedar
Rephael
