# SpaceX Falcon 9 first stage Landing Predictio

In this capstone project-[IBM-Applied Data Science Capstone](https://www.coursera.org/learn/applied-data-science-capstone), the successful landing of the Falcon 9 first stage is predicted. Data on Falcon 9 first-stage landings is collected using a RESTful API and web scraping. 
The collected data is converted into a dataframe and then subjected to data wrangling.

An interactive dashboard is built using Plotly Dash to analyze the launch records. Additionally, an interactive map is created with Folium to examine the proximity of the launch sites. 
Google Colab was used for all notebooks except for interactive visual analytics and the dashboard, which were done in the local environment. The required Python packages for the environment are listed in the req.txt file.

Machine learning is used to determine if the first stage of Falcon 9 will land successfully. The data is split into training and test sets to find the optimal hyperparameters for SVM, classification trees, and logistic regression. The best-performing method is then identified using the test data.
