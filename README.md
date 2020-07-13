# Exploration of World Happiness Report Data
## Note: Please open the .ipynb file in Google colab to interact with the world map. Click the 'Open in Colab' icon once you're in the Ipython notebook. 

The data for this project was taken from kaggle and is initially collected by Gallup in collaboration with Center for Sustainable Development, Earth Institute - Columbia University for annual World Happiness Reports. This project aims to understand the measurement of the happiness - Cantril Score- given to countries. The project shows how these scores are distributed using Plotly library's interactive choropleths, and other seaborn and matplotlib visualizations. The World Happiness Report Data also has various other metrics present that do not determine the happiness score but play a role in gauging the overall 'well-being' of the people in the country. Therefore, this project  tries to predict the happiness scores based on these non-causal metrics through Linear Regression.

Furthermore, the report also groups the countries into three distinct classes (Thriving, Struggling, Suffering) based on their happiness score. The project, using K-Means clustering and PCA tries to cluster the countries into a similar category from the other metrics of the report. 

![Cantril Scores World Map](https://raw.githubusercontent.com/sbsaptarshi/Exploration_of_World_Happiness_Report/master/map.PNG)

Thank you for reading and any feedback is appreciated. 

Relevant links: 

1. Data Source: https://www.kaggle.com/mathurinache/world-happiness-report?select=2015.csv

2. World Happiness Report 2020: https://worldhappiness.report/ed/2020/#read

3. World Happiness Report FAQ: https://worldhappiness.report/faq/

4. Gallup's use Cantril Scale: https://news.gallup.com/poll/122453/understanding-gallup-uses-cantril-scale.aspx

