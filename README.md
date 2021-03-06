![netflix](https://images.unsplash.com/photo-1522869635100-9f4c5e86aa37?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80)  

# Shiny app: Suggest a netflix show :tv:

## Description
Project to build a Shiny app that randomly suggests ONE viewing suggestion, based on genre preference and critics meta-score. The app is motivated by being faced with an abundance of suggestions, so it will simplify the choice by suggesting only one excellent film or TV show (the dice can be rolled again, until the user is satisfied with the suggestion).  

## To-do :tv:

1. Find a website that contains a catalogue of shows currently on Netflix UK that lets me interact with the API  
It seems like there are not many great options to solve this. On [kaggle](https://www.kaggle.com/shivamb/netflix-shows), there is the Netflix dataset, that contains movies and shows until 2020, which is updated every two months (via Flixable: https://flixable.com/).  
2. Find out if IMDB or metacritic has an API  
They don't, but they did recently share their titles and ratings data. Also via [kaggle](https://www.kaggle.com/ashirwadsangwan/imdb-dataset).  
3. Build Shiny app that asks about prefered genre  
4. Show one randomly picked movie plus the imdb rating

## PS: You can scrape your own Netflix viewing history :tv:

Netflix lets you download your viewing history [here](https://www.netflix.com/ViewingActivity). The script ("./Netflix-viewing-hisotory.Rmd") to visualize the top most viewed TV-shows can also be found in this repo.  

![gif](https://github.com/annahensch/suggest-a-netflix-show/blob/master/annas-fave-shows.gif)  

Header image via @freestocks on [Unsplash](https://unsplash.com/photos/11SgH7U6TmI).
