# Netflix Data Analysis Project

## Project Overview
This project performs an in-depth analysis of Netflix's content library to uncover key trends and insights. The primary focus areas include:

1. *Movies vs TV Shows Trend Over Time*  
   - Analysis of how the number of movies and TV shows has evolved over the years.  
   - Provides insights into Netflix's content strategy and production focus.

2. *Genre Analysis*  
   - Identifying the most common genres in Netflix's library.  
   - Tracking the popularity of genres over time.  
   - Helps understand audience preferences and content diversification.

3. *Country-wise Content Contribution*  
   - Determining which countries contribute the most content to Netflix.  
   - Comparison of content types (Movies vs TV Shows) by country.  
   - Provides insights into Netflix’s global reach and market focus.

---

## Dataset
The dataset contains detailed information about Netflix titles, including:  

- *Title* – Name of the movie or TV show
- *Director* - Name of the Director
- *Category* – Movie or TV Show
- *Casts* - Actor & Actress 
- *Type* – Genres of movies or TV Shows  
- *Release Date* – Date of release  
- *Country* – Country of production  
- *Additional Metadata* – Other columns such as duration, rating, description, etc.

### Data Cleaning & Preprocessing
The dataset was cleaned and preprocessed using *Pandas*:  

- Null values were handled carefully.  
- Multi-valued columns (like Type and Country) were split and exploded into separate rows.  
- Leading/trailing spaces were removed, and text normalized.  
- Ensured data consistency for accurate analysis.
- Duplicated columns were removed.

---

## Tools & Technologies
- *Python 3.12.0*  
- *Pandas* – for data cleaning and manipulation  
- *Matplotlib / Seaborn* – for data visualization  
- *Jupyter Lab* – for interactive analysis and exploration  

---

## Key Analysis & Visualizations

### 1. Movies vs TV Shows Trend
- Line or bar charts showing the yearly growth of movies and TV shows.  
- Helps visualize Netflix's content strategy over time.

### 2. Genre Analysis
- *Top Genres Overall:* Horizontal bar chart showing the most common genres.  
- *Genre Distribution:* Pie chart showing proportional representation of genres.  
- *Genre Trend Over Years:* Line or stacked bar charts showing how genre popularity changes over time.  

### 3. Country-wise Contribution
- *Top Countries by Content:* Horizontal bar chart of the countries contributing the most titles.  
- *Movies vs TV Shows by Country:* Stacked bar chart showing the breakdown of content type per country.  

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/bersercz/VOIS-Netflix_Major_Project


# Author 
## Devansh Singh Tomar
