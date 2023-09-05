# Healthcare Industry Patent Visualization

This project was developed to visualize patent data in the healthcare industry using software tools and a patent mapping technique. The primary goal is to provide organizations and individuals with a comprehensive view of the most recent healthcare industry data, aiding in commercialization decisions. A user-friendly website has been created, featuring graphical representations that accurately depict the patent data.

## Project Overview

Two departments collaborated on this project: the Management Engineering team and the Software Engineering team.

- **Management Engineering Team**: Responsible for gathering information from the European Patent Office (EPO) database and interpreting the produced graphs.

- **Software Engineering Team**: Responsible for preparing the data, utilizing a patent mapping technique to create informative graphs, and developing a website to display the project's findings.

## User Stories

As users of the website, we aim to meet the following requirements:

- View various data graphically over a specific time interval.
- Sign in and sign up for an account.
- Access the visualization page after logging in.
- Access an explanatory interface and a help guide to better understand website features.
- Filter data based on specific criteria.
- Easily navigate to the visualization page from different sections of the website.
- Obtain brief explanations for each graph.
- Access the website via laptops, tablets, or phones.
- As a business owner, see the scope of a patent to avoid infringements.

## Technologies Used

The following libraries and technologies are utilized in this project:

- **NumPy:** A library for scientific computing with Python.
- **Pandas:** A library for data manipulation and analysis.
- **Matplotlib:** A library for data visualization.
- **Seaborn:** A library for data visualization.
- **Plotly:** A library for creating interactive visualizations.
- **HTML:** A standard markup language used for web documents.
- **CSS:** A style sheet language used to define the presentation of web pages.
- **JavaScript:** A programming language used for web development.

## Project Workflow

The project workflow involves several key steps:
## 1. Data Preparation
### 1.1. Importing a Working Dataset
A working dataset containing patent-related information was imported. 

### 1.2. Data Cleaning and Exploration
Basic data information was examined to identify and address issues such as duplicate values, mismatched data types, missing data, data outliers, unique values, and null values. 

### 1.3. Data Visualization
Data relationships between variables were explored through various plotting techniques, including box plots, count plots, histograms, and scatter plots.

## 2. Feature Engineering
Feature engineering involves creating new features based on existing data, which can be done using mathematical adjustments or combining existing attributes.

## 3. Data Pre-processing
Data pre-processing is a crucial phase in data mining, involving data manipulation or deletion to ensure or enhance performance. The following steps were taken:

### 3.1. Data Labeling
The IPC (International Patent Classification) column was labeled to provide context and make visuals more meaningful.
### 3.2. Data Cleaning
This phase involved handling missing data and noisy data. Techniques such as filling missing data manually or automatically were applied.

## 4. Patent Mapping
A patent mapping algorithm was used to analyze and illustrate the connections between patents. 

## 5. Data Analysis and Visualization
Quantitative and qualitative analyses were performed to gain insights into the patent data. This included various types of visualizations:

### 5.1. Quantitative Analysis Visualizations
- Ranking Map: Number of patents by country.
- Portion Rate Map: Distribution of top inventors and applicants.
- Share Map: Number of patents by IPC category and country.
- Time Series Visualizations: Various time-based analyses. such as Publication Count By Month, Rolling Mean Of The Publication Count By Month,
   Publication Count By Quarter, Time And Country Overall Publication and IPC Sections Over Time.
- Twin Peak Map: Number of patents and inventors by country.

### 5.2. Qualitative Analysis Visualizations
- Bar Charts:  Number Of Patents By IPC Main Class,  Number Of Patents By IPC Main Class And Country, Number Of Patents By IPC Main Class And Country (Excluding 
              A61B ) and  Top Countries For Patent Related To IPC_ A61B.
- Scatter Charts:  Number Of Patents By IPC Main Class and Number Of Patents By IPC Main Class (Excluding A61B).
- Heat Maps: Number of Patents by Country and Number of Patents by European Countries
- Word Cloud Maps: IPC Main Class Word Cloud from Patent Titles and Inventors, IPC Main Class and Word Cloud of Countries (excluding China)

## 6. Website Creation
The results of the patent data analysis and visualizations were used to create a website that presents the findings in an accessible and informative manner. The website includes various visualizations and interactive elements to explore the patent data landscape.


## Key Findings (2018-2023)
Here are some significant insights gained from the dataset analysis:

1. **Top Country for Patents**: China leads with 3017 patents, making it the country with the highest number of patents.

2. **Leading Patent Holder**: The United States-based company COVIDEN holds the most patents, with 108 patents to its name.

3. **Frequent IPC Code**: The most frequently occurring IPC code is A6B15/00, which corresponds to "Measuring for diagnostic purposes."

4. **Dominant IPC Category**: The most frequently occurring main IPC category relates to "diagnosis, surgery, and identification."

5. **Diverse Representation**: The dataset includes patent data from 35 different countries, showcasing the global reach of patent activities.

## Importent Diagrams

[Framework Diagram](https://github.com/umnaih/CapstoneProject_PatnetMapping/blob/main/Picture1-Freamwork%20diagram.png)

[Website Structure Diagram](https://github.com/umnaih/CapstoneProject_PatnetMapping/blob/main/Picture2-Website%20structure%20diagram.png)

[List Of The Countries That Were Visualized](https://github.com/umnaih/CapstoneProject_PatnetMapping/blob/main/Picture3-List%20of%20the%20Countries%20That%20Were%20Visualized.png)
