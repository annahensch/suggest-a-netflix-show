# Suggest a netflix show Shiny app

## Description
Project to build a Shiny app that randomly suggests ONE viewing suggestion, based on genre preference and critics meta-score.  

The app is motivated by being faced with an abundance of suggestions, so it will simplify the choice by suggesting only one excellent film or TV show (the dice can be rolled again, until the user is satisfied with the suggestion).  

## To Do

1. Find a website that contains a catalogue of shows currently on Netflix UK that lets me interact with the API  
It seems like there are not many great options to solve this. On [kaggle](https://www.kaggle.com/shivamb/netflix-shows), there is the Netflix dataset, that contains movies and shows until 2020, which is updated every two months (via Flixable:https://flixable.com/).  
2. Find out if IMDB or metacritic has an API
3. Build app that asks about prefered genre (+ possibly another random question)
4. Show one randomly picked movie plus the metacritic score

## Scraping your own Netflix viewing history

Netflix lets you download your viewing history [here](https://www.netflix.com/ViewingActivity). The script ("./Netflix-viewing-hisotory.Rmd") to visualize the top most viewed TV-shows can also be found in this repo.  
