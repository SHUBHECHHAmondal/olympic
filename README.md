# Olympics Analysis Project

This project is an interactive data analysis application for the Olympics, built using Streamlit, Pandas, Plotly, and Seaborn. It allows users to explore the Olympics dataset and analyze various aspects such as overall performance, medal tally, country-wise analysis, and athlete-wise analysis.

## Features

- **Medal Tally**: View the medal tally of countries for different years.
- **Overall Analysis**: View top statistics like number of editions, host cities, sports, events, athletes, and participating nations over time.
- **Country-wise Analysis**: Analyze the performance of a specific country, including year-wise medal tally and top athletes.
- **Athlete-wise Analysis**: View the distribution of athletes' ages, height vs weight comparison, and participation trends of male and female athletes over the years.

## Dataset

The project uses two datasets:
- **athlete_events.csv**: Contains information about the athletes, their participation, and achievements in the Olympics.
- **noc_regions.csv**: Contains information about the National Olympic Committees (NOCs) and their corresponding regions.

### Clone the repository:

git clone https://github.com/your-repo/olympics-analysis.git    
cd olympics-analysis 

## INSTALLATION

pip install streamlit    
pip install pandas    
pip install plotly    
pip install seaborn    
pip install matplotlib   

## RUNNING THE APP

streamlit run app.py

## APPLICATION OVERVIEW

### 1. Medal Tally
Users can filter the medal tally by year and country.  
Displays the total medals won in the selected year and country.  

### 2.Overall Analysis  
View top statistics: number of editions, host cities, sports, events, athletes, and participating nations.  
Visualize the number of participating nations, events, and athletes over time.  
Heatmap of the number of events for each sport over time.  
List of the most successful athletes in the selected sport.  
### 3.Country-wise Analysis  
Visualize the medal tally of a specific country over time.  
Heatmap showing the sports in which the selected country excels.  
List of the top 10 athletes from the selected country.  
### 4.Athlete-wise Analysis
Distribution of athletes' ages across all medalists (Gold, Silver, and Bronze).  
Age distribution of gold medalists in different sports.  
Scatter plot showing the relationship between height and weight of athletes, categorized by medal type and gender.  
Participation trends of male and female athletes over the years.


## Helper Functions  
The helper.py script contains all the necessary functions to preprocess the data and extract insights for visualization.    

### preprocess(): Prepares the dataset by merging athlete_events.csv and noc_regions.csv.  
### fetch_medal_tally(): Retrieves the medal tally for a given year and country.  
### data_over_time(): Plots the trends of nations, events, and athletes over time.  
### most_successful(): Returns a list of the most successful athletes.  
### yearwise_medal_tally(): Returns the medal tally for a specific country over time.  
### country_event_heatmap(): Creates a heatmap of the sports in which a country excels.  
### most_successful_countrywise(): Returns a list of the top athletes of a specific country.  
### weight_v_height(): Returns a dataset for visualizing the height vs weight scatter plot.  
### men_vs_women(): Plots the participation trends of male and female athletes over time.  



