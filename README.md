# IMDB-trends-and-ratings-dashboard
# Project Objective
To Visualize decades of IMDB data in Power BI to reveal audience trends and content insights.

# Dashboard components (KPIs)
Trend of IMDB voting: Sum of IMDB votes/scores over time to capture engagement momentum and peaks by year.
Trend of release: Count of titles released per year to visualize industry output and saturation periods.
Top movies & TV shows: Ranked list by popularity or average IMDB score (e.g., Inception, Forrest Gump, Breaking Bad).
Trend of runtime: Average runtime by year to observe format shifts and pacing trends.
Age certification vs ratings: Average IMDB score by certification (TV‑14, TV‑MA, etc.) to infer audience maturity preferences.
Year‑wise IMDB scores: Average IMDB score per year across decades to reveal rating cycles and standout eras.

# Process workflow
Data ingestion
Data cleaning
Modeling:
Calendar table: Create a Year dimension linked to ReleaseYear.
Relationships: Titles (fact) → Year (dim).
Measures: DAX for averages, sums, top‑N rankings.
Visualization
Dasboard
IMDB_PBI
# Key insights
Engagement momentum rose around the 2000s: Both votes and release counts show a notable upswing, suggesting increased audience activity and content output.
Top titles cluster in modern eras: High‑ranking titles (e.g., Inception, Forrest Gump, Breaking Bad) reflect strong performance in late 90s–2010s periods.
Runtime trends shift post‑2000: Average runtime fluctuates with a general decline after 2000, hinting at format optimization and pacing for streaming audiences.
Mature certifications rate higher: TV‑14 and TV‑MA show stronger average scores, indicating a tilt toward complex, mature storytelling preferences.
# Final conclusion
This dashboard translates a complex entertainment dataset into clear, actionable narratives: engagement and content output surged in the 2000s, mature certifications consistently earn higher ratings, and runtimes have been refined to fit modern consumption. For content strategy, prioritize TV‑14/TV‑MA programming with strong narrative depth, calibrate runtimes to audience tolerance, and leverage high‑performing modern titles for recommendation engines. The framework is modular, reproducible, and ready to scale with broader IMDB data—making it a solid portfolio piece and a practical analytics asset.
