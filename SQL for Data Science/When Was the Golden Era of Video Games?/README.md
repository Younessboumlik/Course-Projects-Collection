According to Mordor Intelligence, video games are big business: the global gaming market is projected to be worth more than $300 billion by 2027. With so much money at stake, the major game publishers are hugely incentivized to create the next big hit. But are games getting better, or has the golden age of video games already passed?

In this project, you'll analyze video game critic and user scores, in addition to sales data for the top 400 video games released since 1977. You'll search for a golden age of video games by identifying release years that users and critics liked best, and you'll explore the business side of gaming by looking at game sales data.
<ul>
<li>
Find the ten best-selling games. The output should contain all the columns in the game_sales table and be sorted by the games_sold column in descending order. Save the output as best_selling_games.
<li>
</li>
Find the ten years with the highest average critic score, where at least four games were released (to ensure a good sample size). Return an output with the columns year, num_games released, and avg_critic_score. The avg_critic_score should be rounded to 2 decimal places. The table should be ordered by avg_critic_score in descending order. Save the output as critics_top_ten_years. Do not use the critics_avg_year_rating table provided; this has been provided for your third query.
<li>
</li>
Find the years where critics and users broadly agreed that the games released were highly rated. Specifically, return the years where the average critic score was over 9 OR the average user score was over 9. The pre-computed average critic and user scores per year are stored in users_avg_year_rating and critics_avg_year_rating tables respectively. The query should return the following columns: year, num_games, avg_critic_score, avg_user_score, and diff. The diff column should be the difference between the avg_critic_score and avg_user_score. The table should be ordered by the year in ascending order, save this as a DataFrame named golden_years.
</li>
</ul>
Note: Please also ensure that you do not change the names of the DataFrames that the three query results will be saved as - creating new cells in the workbook will rename the DataFrame. Make sure that your final solutions use the names provided: best_selling_games, critics_top_ten_years, and golden_years.
