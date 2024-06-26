[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/9bMXU1P_)
# Final Project Proposal

## Match Point Metrics: Exploring Tennis Statistics

### Authors

Abigail Williams (aaw01@uw.edu) <br />
Madi Trimmer (mrtrimme@uw.edu) <br />
Stefan Cutovic (scuto26@uw.edu) <br />
### May 5, 2024

Spring 2024
## Abstract

We will consider the affects of various playing surfaces in tennis tournaments hosted by the Association of Tennis Professionals (ATP). Ivestigating this topic is important becuase we can potentially uncover hidden patterns and new avenues for optimizing player
performance. Accordingly, we plan to identify trends, predict match
outcomes, and deliver a comprehesnive summary of the factors influencing player success.

## Keywords

Association of Tennis Professionals (ATP), win rates, player rankings, court surfaces

## Proposal

1. Introduction  

> This project investigates the influence different playing surfaces has on player performance in the context of the Association of Tennis Professionals. 
Through our analysis we ask ourselves - is possible to predict the trajectory of a particular tennis player’s ranking based on historical data? This data will support statistics in match viewing popularity, player marketability, and tournament pools, all of which are integral to the tennis industry. Carefully applying these metrics to future events is likely to provide quality entertainment for the audience and increased revenue for the organization and or the individual player. Furthering the questions surrounding potential player success, we also wonder, how do the win rates of two tennis players, measured over a series of matches within a specific tournament, differ, and is there a significant variance in their performance? With this, we are able to evaluate relative strengths and abilities through win rates. Thus, allowing for direct comparisons between players, aiding in the assessment of their skill levels and competitiveness within the sport. Finally, and most importantly we want to know, Is there a statistically significant relationship between a tennis player’s performance and the type of surface they play on? Knowing this can contribute to answering our initial question surrounding player performance. If a player does particularly well on a specific surface we can use this as a parameter in considering a single match outcome between two opponents or an entire season for a single player. 


2a. Related Work  

> The rise of analytics and data-driven decision making has made significant progress into the world of professional tennis. While the sport has traditionally defied standard statistical analysis due to its unique scoring system, varied playing styles, and different court surfaces, the arrival of advanced analytics has opened up new modes of understanding player performance and developing match strategies. Major technology firms such as SAP and IBM have partnered with tours, tournaments, and players to provide detailed data analysis. Top players like Novak Djokovic and Roger Federer have both found their way into incorporating these techniques into their preparations. However, reactions from players remain mixed, with some cautiously assessing the value of analytics (Tandon). 

> This shift towards data-driven approaches isn't limited to professionals; organizations like the USTA (United States Tennis Association) have partnered with companies like Playisight to analyze youth players, identify talent, and optimize training programs using data on metrics like distance covered, intensity, and workload (Global Sport Matters). This allows coaches to mitigate injuries while simultaneously striving to enhance performance. 

> Understanding the dynamics of ATP tennis tournaments can provide valuable insights into player performance and tournament organization. Analyzing historical tournament data allows us to identify trends, predict match outcomes, and gain a deeper understanding of the factors influencing player success (Wastcoat). While not a global problem per se, it would be interesting to see if data programming and analysis can provide answers to longstanding questions within the tennis community, such as the impact of surface preferences on performance or the significance of high win rates when predicting match outcomes. By using this data, we can potentially uncover hidden patterns and new avenues for optimizing player performance.


2b. Works Cited --> (MLA, 8th ed.)

> Farrell, Sarah. “Tennis players embracing technology and analytics in training.” Global Sport Matters, 16 October 2019, 
    https://globalsportmatters.com/science/2019/10/16/tennis-players-embracing-technology-analytics/. Accessed 30 April 2024.

> Tandon, Kamakshi. “The role of analytics in tennis is on a long, slow rise.” Tennis Channel, 17 January 2020, 
    https://www.tennis.com/news/articles/the-role-of-analytics-in-tennis-is-on-a-long-slow-rise. Accessed 30 April 2024.

> Wastcoat, Eliza. “5 Exciting Ways AI Can Be Used In Tennis.” IoT For All, 20 June 2023,
    https://www.iotforall.com/5-exciting-ways-ai-can-be-used-in-tennis. Accessed 30 April 2024.


2c. Links to Featured Sites:

> https://www.tennis.com/news/articles/the-role-of-analytics-in-tennis-is-on-a-long-slow-rise

> https://globalsportmatters.com/science/2019/10/16/tennis-players-embracing-technology-analytics/

> https://www.iotforall.com/5-exciting-ways-ai-can-be-used-in-tennis


3. The Dataset

>The dataset we’re investigating will be the “ATP Tennis Matches 2013-2023” CSV file available on Kaggle. This data collection contains information about every ATP tennis match (ATP 250, 500, Masters 1000, Grand Slam) that occurred between the years of 2013 and 2023. This includes various attributes such as tournament name, surface type, match date, player names, their rankings, match scores, etc. The data was collected simply by a fan (user DISSFYA on Kaggle) who was invested in collecting popular tennis match/player statistics, and who published such findings with a Creative Commons license so that it could be accessed in the public domain.There are 17 features/columns in this data, some of which were aforementioned above. There are 25,163 rows, which represent a single match at a tournament and the respective characteristics and aspects of the match. As a result of the way in which this data was obtained, one possible limitation to consider is that the individual who found and collected this data might have looked over certain matches/data points (which is unlikely given the thoroughness of the data). Additionally, they also would have had the power to insert personal biases towards a player, tournament, etc through including more relevant data pertaining to these items rather than objectively adding data pertaining to any potential data point to consider. This, however, A challenge we faced with this data is that, if a match never played out, ended due to injury, involved a retired player, etc, the row which was relevant to this match was simply wiped clean. Therefore, we had to scan through the data and remove any blank rows manually, which was quite laborious and difficult.

[Link to ATP Tennis 2013 - 2023](https://www.kaggle.com/datasets/dissfya/atp-tennis-2013-2023)


4. Implications

> The analysis of ATP data carries significant implications that could shape the future of the sport and influence the various stakeholders involved in its ecosystem. 

> For technologists, this study showcases the potential of data programming and analysis in uncovering valuable insights and patterns within the professional tour. With such findings, they can develop advanced analytics tools, predictive models, and data-driven decision support systems. These innovations could aid players, coaches, and tournament organizers in optimizing performance, strategy, and event planning (respectively), ultimately elevating the sport to new heights. 

> Designers, too, benefit from this analysis, as it highlights the need for user-friendly and visually appealing data representations. By leveraging the insights gained, they can create intuitive visualizations and interfaces that effectively communicate complex statistical information to diverse audiences, including fans, players, coaches, and analysts. 

> This could refine the overall experience and understanding of the sport for all stakeholders, while also potentially informing policymakers within the tennis industry. The findings related to players’ performance on different court surfaces could influence decisions regarding tournament scheduling, surface selections, or even rule modifications to improve fairness and competitiveness. This analysis could prompt broader discussions around data-driven decision-making in sports, athlete welfare, and the responsible use of analytics to maintain the integrity of the game.


5. Limitations & Challenges

> While the project idea would showcase the potential of analytics within the sport of tennis, several challenges and limitations must be addressed to ensure its broader application and impact. For one, the plan heavily relies on the availability and quality of historical tournament data. Ensuring consistent, accurate, and comprehensive data collection across various tournaments, surfaces, and player demographics could be a significant challenge. Incomplete or inaccurate data could severely limit the scope and reliability of results derived, undermining the entire point of analysis. 

> Furthermore, it's important to consider the interpretability of statistical models and predictions made in the analysis. While these models can provide valuable insights, it’s crucial to ensure that the underlying assumptions, methodologies, and decision-making processes are transparent and easily interpretable. Failing to do so could result in widespread skepticism and distrust from stakeholders. Without clear explanations of how the analytics are derived and applied, there may be reluctance to adopt the insights and recommendations generated by the project. 

> Lastly, while we’re projecting to perform various types of statistical models and analyses based on historical ATP data, our current knowledge may not be sufficient to bring those results to fruition effectively. Our goals within this project are tentative and subject to change based on our understanding of data programming and the complexity of the tasks involved. As we progress, we may discover that our initial objectives exceed our current skill level or require more advanced techniques than anticipated. In such cases, we will adapt our goals to better align with our capabilities. Addressing these challenges proactively is crucial for ensuring the responsible and effective application of data analytics in the tennis industry.


Acknowledgements
>  Our team would like to dedicate special thanks to our teaching assistant Kiyomi Komatsu. Without Kiyomi's support and guidance, this project would not be possible.
