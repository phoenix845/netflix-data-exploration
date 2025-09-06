🎬 Netflix Movie Data Analysis

📖 Overview
This project explores and analyzes a Netflix movie dataset to uncover trends, patterns, and insights into content distribution.  
The goal is to answer questions like:  
- What are the most common movie genres on Netflix?  
- How has Netflix's content library evolved over time?  
- What is the distribution of movie popularity and ratings?  
- Which movies stand out as highly rated or popular?  

By performing **exploratory data analysis (EDA)**, we visualize and interpret patterns that can drive business and product decisions.


📂 Dataset
- **Source:** `movie_dataset.csv`  
- **Size:** ~25,000+ records, ~10 columns (insert actual numbers from `df.shape`)  
- **Key Features:**  
  - `title`: Movie title  
  - `genre`: Primary genre(s)  
  - `release_date`: Release year  
  - `vote_average`: Average rating  
  - `vote_count`: Number of votes  
  - `popularity`: Popularity score  


⚙️ Workflow & Methodology
1. **Data Cleaning**  
   - Removed duplicates, null values, and irrelevant columns  
   - Converted release dates to year format  
   - Standardized genre and rating values  

2. **Feature Engineering**  
   - Created rating bins: `popular`, `average`, `below_avg`, `not_popular`  
   - Extracted temporal trends from release dates  

3. **Exploratory Data Analysis (EDA)**  
   - Visualized genre distribution  
   - Analyzed rating trends and popularity  
   - Tracked release volume over time  

4. **Visualization Tools**  
   - `Matplotlib` and `Seaborn` for interactive charts  
   - Clear labels and storytelling visuals  


📊 Key Insights

🎭 Genre Distribution
- **Drama, Comedy, and Action** dominate the platform, with Drama titles exceeding **3,500+ entries**.  
- Genres like *Documentary* and *Western* are rare, representing niche audiences.  

![Genre Distribution](figures/genre_distribution.png)



📅 Release Year Trends
- Netflix’s catalog has **expanded rapidly post-2000**, peaking in **2015-2020**.  
- Movies from before the 1980s form a **tiny fraction** of the library.  

![Release Date Distribution](figures/release_date_distribution.png)


⭐ Popularity & Rating Patterns
- Ratings are **evenly distributed** among `popular`, `average`, and `below_avg` bins.  
- Few movies are categorized as `not_popular`, showing that most content receives engagement.  

![Votes Distribution](figures/votes_distribution.png)


🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  
- **Version Control:** Git & GitHub  


🚀 How to Run Locally
Clone the repo:
```bash
git clone https://github.com/phoenix845/netflix-data-exploration.git
cd netflix-data-exploration
