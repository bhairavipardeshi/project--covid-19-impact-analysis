Project Explanation – Covid 19 Impact Analysis 

Introduction  
• The "Covid-19 Impact Analysis" project uses Python's Dash library web 
deployment to create an interactive dashboard. 
• This dashboard visually represents key Covid-19 metrics such as total 
cases, active cases, recovered cases, and total deaths according to different 
states of India.  
 
• It also analyzes the availability of essential items like masks, sanitizers, and 
oxygen. The goal is to make complex pandemic data easy to understand 
through interactive visuals. 
Data Collection 
• I gathered a curated dataset from a CSV file, encompassing comprehensive 
information on Covid-19 cases. 
Libraries Used  
• numpy and pandas for data manipulation and analysis. 
• plotly.graph_objs and plotly.express for creating interactive plots. 
• dash for web application development. 
• dash_core_components, dash_html_components for creating the layout 
components. 
• Input, Output from dash.dependencies for handling callbacks. 
Data Loading 
• The project starts by loading a dataset (state_wise_daily.csv) using Pandas, 
containing information on Covid-19 cases.  
3 
 
• The dataset is structured to include data on different statuses like 
Confirmed, Recovered, and Deceased. 
Dashboard Layout 
HTML 
• HTML (HyperText Markup Language) is the standard markup language for 
creating web pages. 
• In the context of this project, HTML is used to define the structure of the 
dashboard, dividing it into various sections. 
Dash Components 
• Dash provides a Python framework for building interactive web 
applications. Dash components are used to create the different elements of 
the dashboard. 
Divs and Classes: 
• Divs (Division): 
➢ Divs are HTML elements used to group and structure content on a web 
page. 
➢ In this project, divs are employed to create distinct sections of the 
dashboard, separating content logically. 
• Classes: 
➢ Classes in HTML are used to apply styles to multiple elements with the 
same design. 
• The top section displays overall Covid-19 statistics with dynamically 
updating total cases, active cases, recovered cases, and total deaths. 
• The second section presents line charts showing the trend of essential 
commodities (mask, sanitizer, oxygen) over different statuses (Confirmed, 
Recovered, Deceased). 
• The third section showcases a dropdown-enabled pie chart illustrating the 
distribution of Covid-19 cases in different zones (Red, Blue, Green, 
Orange). 
• The final section allows users to choose a status (Confirmed, Hospitalized, 
Recovered, Deceased) from a dropdown to view a bar chart depicting the 
total count for each state. 
Styling and External Dependencies 
4 
 
 
• Bootstrap is utilized for external styling to enhance the visual appeal of the 
dashboard. 
• External stylesheet links are added to the Dash app for improved styling. 
Running the Application 
• The application is launched using app.run_server(debug=True) 
• The application is launched using app.run_server(debug=True). The 
dashboard opens in the web browser. 
    Challenges Faced and Solutions 
• Challenge: Implementing dynamic updates for graphs based on user 
interactions required careful handling of callbacks and data dependencies. 
• Dash's callback functionality was used effectively. 
Conclusion  
This project not only enhances my skills in data analysis and web 
development but also serves as a practical application of data analytics and 
science in addressing real-world challenges. 

and this is my output:


![image](https://github.com/bhairavipardeshi/project--covid-19-impact-analysis/assets/175000774/828ddbce-5cb0-4ea0-b7f0-93c8fe973d24)

