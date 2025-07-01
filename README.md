# 📊 Netflix Movie Data Analysis

Netflix has grown from a DVD rental service in 1997 to a global streaming giant available in over 190 countries by 2016. This project explores trends and insights in its movie catalog using data analysis and visualizations.

## 🔍 Objectives

This notebook answers key questions based on Netflix’s movie data:
- What are the most frequently released genres?
- Which genres receive the highest vote counts?
- What movie is the most popular and what is its genre?
- What movie has the lowest popularity and what is its genre?
- Which year saw the highest number of movie releases?

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🧹 Data Preprocessing

- Dropped irrelevant columns like `Overview`, `Original_Language`, and `Poster_Url`
- Converted `Release_Date` to year
- Handled missing values and removed duplicates
- Split and exploded multi-genre entries
- Casted genre and vote categories into meaningful labels (e.g., _Popular_, _Average_)

## 📈 Key Insights

| Question | Insight |
|---------|---------|
| 📽️ Most Frequent Genre | **Drama** dominates as the most frequently released genre. |
| 🗳️ Highest Votes by Genre | Most movies fall under the **Average** vote category. |
| 🌟 Most Popular Movie | **Spider-Man** stands out as the most popular movie by popularity score. |
| 💔 Least Popular Movies | _The United States vs. Billie Holiday_ and _Threads_ recorded the lowest popularity scores. |
| 📅 Most Active Year | **2020** witnessed the highest number of movie releases. |

## 📊 Visual Highlights

- Bar plots for genre and voting distribution
- Histogram for yearly release trends

## 💡 Conclusion

This analysis gives a data-driven perspective on Netflix’s content strategy, emphasizing its focus on drama and evolving audience engagement. There's room to explore temporal popularity trends, voting behaviors per genre, or even build a movie recommendation engine as a future extension.

