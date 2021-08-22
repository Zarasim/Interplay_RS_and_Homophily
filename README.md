# Interplay-RS-and-Homophily-

Project addressing the interplay between Recommender Systems and Homophily in Network of Users. 
The processed data has been retrieved from the Movielens Dataset (https://movielens.org/).

## Introuduction and Motivation of the project

Over the last decades, research on Recommender Systems (RS) has focused on models
and algorithms that provide personalized suggestions to customers with increasing
accuracy. This project proposes an investigation on the interplay between homophily
and recommendation processes in the prediction of movie ratings. In simpler terms, we 
aim to answer the question

To which extent does a RS influence the choices of movies by target users in a streaming platform ?

The network analysis offers interest insights that can explain the causes of user' behiavour,
such as how much they believe in in the recommendations from the online service without conducting
expensive and biased surveys. 

Our approach is based on harnessing the temporal evolution of an affiliation
network, which links users to the respective rated movies. The projection into the
former group will reveal how their inter-connections evolve over time on the basis
of their rating patterns.

Similarly, synthetic networks are generated by a simple model that rewires the
links in the affiliation network and preserves its degree distribution. One
parameter controls the fraction of movies that each user will see according to a collaborative
filtering algorithm, whereas the remaining titles are picked at random.
The tuning of this parameter will also reflect on the topology of the user network
and enables to model matematically the initial question.


The results suggest that the best model is achieved if users decide, on average,
to watch 40% of movies assigned by the RS. This conclusion is not significant as the processed dataset
contains too few entries, but it can to be validated on bigger
datasets and with more advanced models, which might account for demographic and other 
personal information to provide the best recommendations.
