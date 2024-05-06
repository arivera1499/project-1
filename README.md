# project-1
A shared repo for first project

### Google Slide Link
https://docs.google.com/presentation/d/1WF8fXsHKZk8qfGdtTBMJlc4rfrv4XwuZlIbYiCkNRcI/edit?usp=sharing

# Analysis
----
The goal of this project was to build an easy-to-understand formula to convince investors that the future product would have a great ROI.
To complete this task we wanted to look at the controllable variables that were returned from the JSON request from the OMDB API. With this in mind we found six main characteristics (Director, Actors, Writers, Genre, MPA Rating, and runtime) to investigate further. 

Directors:
When it came to directors we found the sum of the total amount made per movie as well as the average amount made per movie. Some notes of interest while analyzing the data was the tendency to be only one sole director per project. It was not completely unheard of to have multiple directors, such as with Joe and Anthony Russo, but most of the time there is usually one main director. This makes sense as if multiple directors work on a project together they could have disagreements with the direction of the movie and cause delays. 

Since directors tend to have more experience with certain types of movies we felt it was reasonable to suggest to potential clients to choose a director that appeared on the top 10 total amount made and average made per movie. 

Actors:
Similar to directors we found the total sum of money made by each actor as well as the average amount made per movie. From both graphs we noticed that a lot of actors tend to work on similar projects together within the top 200 grossing. One interesting thing to note was that the total amount of money made by the 3 Harry Potter stars (Daniel Radcliffe, Rupert Grint, Emma Watson) was high but were exactly the same. This suggests that while they have found success working together on the series they haven't found nearly as much when working on individual projects.

Many actors have also worked with certain directors regularly, especially when working on a continuing series. Since the cast of a film can contain many actors we also suggested choosing actors that appear on both lists while prioritizing the actors that return a higher average amount when descending on how to fill out the rest of a cast on a project. 

Writers:
For the writers portion we found the average amount of money returned per movie. Writers can have multiple people work on a project but it is not unheard of to have only one single writer on a film. We actually found that some directors will also write their own movies sometimes such as James Cameron

Picking a writer or two can be very simple and we suggest picking someone from the top 10 list provided during the presentation. Sometimes you can have the director picked earlier too making the process even simpler.

MPA rating:
There were only 4 ratings and one category without a rating found in the top 200 highest grossing. When researching why a movie may not be rated by MPA it was found that this tends to happen with re releases of certain films with a director's cut which would not have been submitted to MPA during the original screening of the film. As for the highest average amount made per rating we were interested to find that “PG-13” had the highest average made. This is contrary to what we would have believed as unlike with “G” and “PG”, “PG-13” has higher restrictions on who can actually watch the film. Our initial though was that one of the other, more family friendly, ratings would have higher returns since more people would have access to view the movie. 

For this section we would suggest making the rating “PG-13” in correlation with the highest average amount made.

Runtime:
We took the runtime for the top 200 highest grossing films and set them on a scatter plot during this section. Finding the linear regression line for all the film we found a slight positive correlation the longer the runtime of the film itself is. Many longer films tend to have a more flushed out story and character development which could be causing audiences to like and recommend the movie more, increasing the overall amount grossed for a film.

For the runtime we would suggest overall to make the film slightly longer to fit the trend line. There is an important note to be made though that it is possible to make a movie too long which would cause the audience to bore so it is important to be careful when deciding on the runtime. 

Extras:
During the exploration process of this project many other trends were found. These findings can also be found throughout this repo and the ones that we found most important were mentioned during the presentation in class. 


### Looking for the parts that will create the whole
----
- Directors like the Russo brothers and James Cameron. 
- Competent writers like Christopher Markus.
- Superstar actor Robert Downey Jr.
- A full feature-long runtime.

## The combination 
----
Observing them individually they make billions, together they could elevate each other making more money in the process. 
