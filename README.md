# IMDb Analysis

Why do people like the movies they do?

In light of the recent release of the 2022 Sight and Sound poll—which polls critics on their top 100 films—we thought we'd turn our attention to the ordinary movie-goer instead, and explore the question of which films are popular, why, with whom, and over which periods of time.

We shall be using the BigQuery IMDb dataset to answer our questions. The dataset tracks (among other things) the reviews left by online users on particular films, along with a rating on a 10-point scale. To answer our main question, we shall be amalgamating reviews and ratings to answer three interrelated subquestions:

- How are ratings and reviews broadly distributed across IMDb titles?
- How have these ratings and reviews changed over time?
- How do the ratings of the IMDb audience compare to the critics' Sight and Sound poll, and has the 2022 update brought it closer to public opinion?

Finally, we shall use an ML algorithm to try to predict the average user rating of a film based on the features we identify.

Code written in colaboration with Ayush Majumdar
