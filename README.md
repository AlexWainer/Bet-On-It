# Bet-On-It
Excel soccer/football predicitng model

Overview
This repository contains an Excel-based sports predicting model designed for the 2022 World Cup. The model uses various team performance metrics to predict match outcomes and calculate betting odds.

Features
Team Performance Metrics: The model uses goals scored, goals conceded, matches completed, form and injuries to evaluate team performance.
Matrix Calculation: Based on the input metrics, the model creates matrices for each variable.
Average Goals Calculation: These matrices are used to calculate the average goals scored by each team.
Poisson Distribution: The model applies a Poisson distribution to determine the probabilities of the home team winning, losing, or drawing against the away team.
Odds Calculation: Finally, the model computes the betting odds for each possible outcome.

How to Use
Input Data: Ensure that the data for goals scored, goals conceded, matches completed form, and injuries for each team are up-to-date in the Excel file.
Run the Model: Choose which teams to put up againts each other. 
Interpret Results: Review the calculated probabilities and odds to make informed predictions and betting decisions.

Model Details
Input Variables
Goals Scored: Number of goals a team has scored in previous matches.
Goals Conceded: Number of goals a team has conceded in previous matches.
Matches Completed: Number of matches you have data for for a team.
Form: Recent performance of the team (Last 5 matches).
Injuries: Current injury status of key players.

Calculation Process
Attacking Matrix: The model generates attacking matrices for goals scored, goals conceded, form, and injuries based on the averages of all these variables.
Average Goals: These matrices are used to calculate the average goals scored by each team, home advanatges shoudl be left out for tournaments.
Poisson Distribution: The average goals are input into a Poisson distribution to calculate the probability of different match outcomes (home win, draw, away win).
Odds Calculation: Based on the probabilities, the model computes the betting odds for each outcome.

Inspiration
This model was inspired and built on the fundamentals of a model I encountered previously. Unfortunately, I cannot recall the source or the original creator. If you recognize any similarities or know the origin, please feel free to reach out so I can give proper credit.
