# IBM Applied Data Science Capstone: SpaceX Falcon 9 Landing Prediction

## Project Overview

This repository contains my final IBM Applied Data Science Capstone project. The objective is to predict whether the SpaceX Falcon 9 first stage will land successfully using historical launch data.

Successful first-stage landing allows SpaceX to reuse boosters and reduce launch costs. A competitor can use a landing-success prediction model to estimate launch cost and support bidding decisions.

## Business Problem

The project is based on a fictional business scenario in which a competing space company wants to estimate the likelihood of a successful Falcon 9 first-stage landing. Since booster recovery can significantly affect launch cost, predicting landing success can support cost estimation and competitive bidding decisions.

## Data Sources

- SpaceX REST API
- Wikipedia Falcon 9 / Falcon Heavy launch records
- Cleaned datasets generated during the IBM capstone labs
- Dashboard and geospatial datasets provided in the IBM lab environment

## Project Workflow

1. Data collection using the SpaceX API
2. Web scraping from Wikipedia
3. Data wrangling and creation of the `Class` target variable
4. Exploratory data analysis with SQL
5. Exploratory data analysis with visualization
6. Interactive launch-site mapping with Folium
7. Interactive dashboard with Plotly Dash
8. Machine learning classification for landing prediction
9. Final presentation of results

## Repository Structure

```text
notebooks/      Solved Jupyter notebooks for each capstone lab
dashboard/      Plotly Dash dashboard notebook and Python app
images/         Dashboard screenshots and visual assets
presentation/   Final PowerPoint and PDF presentation
data/           Generated CSV files used during the capstone labs
