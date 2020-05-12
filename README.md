# okc_nlp_project
NLP Clustering Project for OkCupid's Dataset

OkCupid matches people by asking a lot of questions and assigning weights based on importance. However, I was curious if one could cluster or match people by their essay responses. OkCupid asks users to describe themselves as well and in this dataset, it asked the following questions:
essay0- My self summary
essay1- What I’m doing with my life
essay2- I’m really good at
essay3- The first thing people usually notice about me
essay4- Favorite books, movies, show, music, and food
essay5- The six things I could never do without
essay6- I spend a lot of time thinking about
essay7- On a typical Friday night I am
essay8- The most private thing I am willing to admit
essay9- You should message me if...

Since some users decided to leave some responses blank, I decided it would be best to aggregate them into one corpus for vectorization and dimension reduction.

In this project, I visually graphed users and clustered them using different techniques such as DBSCAN, KMeans, and t-SNE. Furthermore, I checked whether these clusters were good by heuristically looking at users' essays that were clustered by the algorithms. You can be the judge whether you think the users might go on a date based on their essays! 
