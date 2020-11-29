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
We also seemed to run into a

## Future Work: 

There is a solid amount of extra work that could improve our project. For one, consolodating genres that are similar would more accurately display results. For example, if one person has several different rap genres like Atlanta hip hop and Chicago hip hop, realisitcally, both of those genres could simply be considered hip hop for the sake of comparison. There would have to be some math to futher increase accuracy of results depending on exact genre matches, but some genres that Spotify returned seemed so non-descript. of the artist it lead us to believe that some genres existed soley for a few or even just one artist.

## Org Chart:

Jared 
Kishan
Kedar
Rephael
