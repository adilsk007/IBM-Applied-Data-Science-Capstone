# IBM Applied Data Science Capstone: SpaceX Falcon 9 Landing Prediction

## Project Overview

This repository contains my final IBM Applied Data Science Capstone project. The objective is to predict whether the SpaceX Falcon 9 first stage will land successfully using historical launch data.

Successful first-stage landing allows SpaceX to reuse boosters and reduce launch costs. A competitor can use a landing-success prediction model to estimate launch cost and support bidding decisions.

## Data Sources

- SpaceX REST API
- Wikipedia Falcon 9 / Falcon Heavy launch records
- Cleaned datasets generated during the IBM capstone labs

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
data/           Add generated CSV files here before final submission
```

## Main Results

- KSC LC-39A had the largest number of successful launches in the dashboard analysis.
- KSC LC-39A also had the highest launch success rate.
- Payloads around 3,000-4,000 kg showed the highest success-rate band in the dashboard dataset.
- Booster category B5 showed the highest observed success rate.
- Classification models compared included Logistic Regression, SVM, Decision Tree and KNN.

## Tools and Libraries

Python, Pandas, NumPy, SQL, Matplotlib, Seaborn, Folium, Plotly Dash, Scikit-learn, Jupyter Notebook.

## Final Deliverables

- Final presentation PDF
- Solved Jupyter notebooks
- Dash dashboard screenshots
- Dash application file/notebook
- GitHub repository URL for Coursera submission

## Author

Muhammad Adil Salam
