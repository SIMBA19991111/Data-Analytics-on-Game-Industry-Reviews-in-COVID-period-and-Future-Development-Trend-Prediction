# Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction
This project uses Metacritic as a data source to analyze game review scores and user ratings from 2017 to April 2023. It examines the impact of COVID on game quality and player acceptance across platforms and categories. AI-based predictive modeling techniques provide insights into future gaming trends to assist stakeholders in decision-making.
Analysis Tool Development
We have developed a series of tools to more easily support our research to collect and better visualize our data.
1. Web scraping and database building.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/7c37450e-68e1-4d71-aa28-3d01482728c0)


We used the beautifulsoup library to gain the records of all released games from January 1,2017 to April 5,2023, and established a database.
2.Description of dataset
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/b9f75f34-f264-4085-a070-1956004ea2cc)

Our dataset contains the data recorded on the Metacritic website from January 4, 2017 to April 4, 2023. The dataset covers eight including Game_Title,Game_Publisher Game_Platform, Game_Genre, Game_Release_Date, Critic _ Score, User_Score, Year, and the size is 6303 recorded titles.
2.Functions Building.
Our analysis tool includes 4 functions:
(1)Game quality / quantity status for specifically requested game publishers/developers.
(etc. Electronic Arts)
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/f3a8abf7-4117-4800-a9f2-ad5cf01381f2)


1-Top 10 media and user ratings, and their other rating dimension (all time)
2-The company has seen a total trend in the number and number of games released on and on different platforms (by years)
3-Average media ratings and user rating trends (by years)
4-The company's average media rating trends across its platforms (by years, Compared with the average score)
5-The company's average user rating trends on the platform (by years, Compared with the average score)
6-The company's average media rating trends in genre (by years, Compared with the average score)
7-The company's average user rating trends in genre (by years, Compared with the average score)

We have also developed a simple set of fuzzy query tools for better usability.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/5b829915-2f70-4163-8579-fc9d98bd032d)

Based on this function, users can always find their own development / distribution company for a more personal data processing experience.
(2)Overall summary of the all-time period
including:
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/1854daae-7f4b-4dd7-938b-6718bd76cad7)


1-Top 10 for media ratings, and their respective other rating dimension
2-Average media ratings by year
3-Total number of games released on major platforms (from high to low)
4-Trend in the number of games released across platforms (by year)
5-Changes in average media scoring trends across major platforms (compared with overall average by year)
6-Changes in average user rating trends across major platforms (compared with the overall average split by year)
7-Trend change in the number of games released by genre (by year)
8-Total number of games released in each genre (from high to low)
9-Changes in average media score trends across major types (compared with overall average split by year)
10-Changes in average user score trends across major types (by year, versus overall average)
(3)An overall summary accurate to the requested time period (input start and end time node) 
A function was developed to automatically identify the time points and form format the input to more accurately present data in certain special intervals (such as three years of COVID).

 ![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/67a3a7da-9853-4af7-b0da-60797c1ae031)
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/f78d4e83-64c3-480c-ad96-c4a7549bd246)


(4)Prediction
AutoTS is a time series package for Python designed to quickly deploy large-scale, high-precision predictions. It has dozens of prediction models available in sklearn style and can generate accurate predictions quickly. In 2023, AutoTS won the M6 Prediction Competition and provided the highest performing investment decisions in 12 months of stock market forecasting.
Our brief prediction was made using the AutoTS automated time series prediction library to observe the changing trend expressed by the game quality presented by the mean media score.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/ff28d9fb-1267-44b4-a9eb-ab314e9dc494)
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/58c7eff9-c3ee-4086-91ef-673146230bb0)
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/f1a583b1-2dad-4d9d-b7ce-b434a313f351)



1、To predict the whole time period of the database and observe the overall development of the game field.
2、Predicted the data before the COVID outbreak (01 January 2017-31 December 2019), and observe the overall quality of the game before the outbreak.
3、Forecast the data of COVID in the database (1, January 2020- 31, December 2022), and observe the overall quality of the game in the epidemic.
4、Forecast the data from the COVID outbreak in the database (January 1,2023 to April 5,2023), and observe how the overall quality of the game predicts after the outbreak.
After that, the four predicted trends were compared to observe whether the COVID has a significant impact on the fluctuations of the development trend of game quality.
(5)The integration of all functions and the selection interface.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/6b03af31-1515-4a74-ad2d-e533f9c1a5ad)

Overall Data Analysis
1.Number of games released
Step1 
View the overall trend in the number of releases.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/3b0b7213-071d-45ba-a230-e8e7c0128e8e)

1.1 Number of games released (all time)
We will focus on the change of three-year covid circulation. Figure 1.1 shows that the number of game launches has decreased significantly between 2020-20-2022 (incomplete data in 2023 is not included in the discussion)。

Step2 
Deeper study using time-segment functions.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/aacc9c41-d88c-4a8a-9d4b-696690dccd78)

1.2 Trend of number of games released  (2019-12 to 2022-12, by month)
There is a significant peak season for game releases every year, usually in September and October, but the number of games released in 2022 has declined significantly, and many months of the year are significantly lower than the previous year. In Figure 1.2, since the interval between game development and official release is generally one to two years, the development time of the game released in 2022 is exactly during the outbreak of COVID, and it is speculated that the impact of COVID on game development appears at this time.

Step3
View changes after covid period.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/cc603149-908c-4eb7-8019-18945ccaa642)

1.3 Trend of number of games released  (2022-01-01 to 2023-04-05, by month)
As shown in Figure 1.3, the game circulation in January and February 2023 increased significantly compared with the same period last year, but March showed a downward trend. This proves that so far, game production is gradually recovering from the impact of COVID, but the recovery process is still tortuous.
2.Game quality / player acceptance (reflected by media average / player rating)
Step1
Filtering Top 10 games that media reviews and players consider the best during this period.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/d928e224-5d07-47be-88f9-29ee2aaa6f31)


2.1 Top 10 best game by critic review
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/99217e3f-5a90-4a4a-b882-3adb31b0b3ca)


2.2 The best game top10 by users
In Figure 2.1, when the user rating situation was added, we found that some game users and media reviews were quite different, such as Elden Ring and Red Dead Redemption 2. Therefore, we selected the best ten games that users considered to compare with media reviews, as shown in Figure 2.2. At this time, the gap between media ratings and user ratings was significantly narrowed.
In Figure 2.1, when the user rating situation was added, we found that some game users and media reviews were quite different, such as Elden Ring and Red Dead Redemption 2. Therefore, we selected the best ten games that users considered to compare with media reviews, as shown in Figure 2.2. At this time, the gap between media ratings and user ratings was significantly narrowed. 
Step2
Check out the overall trend of average distribution.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/f9a85993-9d39-4117-b241-808c90b571f3)

2.3 Overall trends in media and user ratings
As can be seen in Figure 2.3, from the media evaluation, the development of products, but reversed the significant decline trend of COVID. However, despite the perspective of the actual acceptance trend of players, the performance of 2020 and 2021 also reversed the downward trend in 2022, which proves that the actual impact of COVID on the acceptance performance of players is significant. In addition, the trend between media reviews and player acceptance seems to suggest a dangerous tendency of a separation between good ideas and actual player acceptance, and the separation is getting bigger. We think this is a more alarming trend: the industry seems to be losing understanding what players really want.

3. Trend of Platforms’ Change
Step1
Check the number of games logged in on each platform.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/c77f9e17-17cf-4887-b8dd-a114986b9536)


3.1 Top 10 platforms with the largest number of games
In Figure 3.1, in the past six years, the development of game platforms is as follows: In terms of the number of games, pc still has the number of logins reaching 2036, the only game platform to break the 2000 mark, followed by switch, reaching 1757.

Step2
Check out the number of games released on each platform.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/a853ce5d-11bb-4b0f-bbf0-e2cac4d14780)

3.2 Platform Trend of game quantity change (all time)
After we added the overall statistics of the number of login games on each platform to the time dimension, Figure 3.2. Since 2017, with the rise of switch worldwide, when the number of games on all other platforms was declining, switch has launched 355 games in one year.
When time came to 2020, the global outbreak into the white-hot, each big game platform are affected, in addition to the pc platform online game quantity appeared the cliff type fell, 3ds even after 2019 to stop the login new products, and pc during this period showed strong toughness, is during 2019 to 2021 game circulation only still in the growing platform, even more than before the outbreak of covid.
It is worth mentioning that COVID did not affect the new platform online, one of the most impressive is ps5 and Xbox Series X, in 2020 to 2022 online game number rising, 169 and 110, at the same time their former PS4 and Xbox One continue to fall, this reflects the transition of the old and new platform, also prompted developers need to attention to shift to the emerging platform.
The outbreak of the global epidemic is undoubtedly a challenge for the established game platforms, but it is a rare opportunity for the emerging game platforms.

Step4
View average rating by media and users.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/7526f43a-0161-4199-bdad-2ce3a5642d32)

3.3 Change trend of media average score of each platform (by years)
As shown in figure 3.3 we screened six years media for the average score of each platform, we found that most of the platform score basic consistent with the overall average score, floating range around 10 points, basically stable, visible media for the platform evaluation is relatively stable, but it is interesting that switch platform between 2018 to 2020 score gap between surprising, we continue to check the user score trend.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/ea61f8f9-3c1c-43c9-93eb-eed941469e2c)

3.4 Trend of average ratings of each platform (years)
When we select the user for points platform average score, as shown in figure 3.4, we found that the user's average score is generally lower than the media average score, on the other hand, unlike the media, the user of each platform score change is very big, the average annual ups and downs around 30%, visible compared with the media, the user's attitude to the platform is more likely to influence.
Combined with both Figure 3.3 and Figure 3.4, Let's focus on the switch platform, Despite the impressive success of the switch platform in 2017, But in 2018, switch platforms faced huge challenges, See Figure 3.3 and 3.4, Users and media scored the lowest ratings for switch games during the year, The vast majority of players have reversed their attitude towards this nascent platform, But the covid outbreak brought a turnaround for switch, Since 2019, switch has been at a slump in media and user reviews, Achieved a significant increase, Even surpassing the best performance in 2017.
Furthermore, we can compare Figure 3.3 and Figure 3.4 to see very clearly the "Game industry's winter during the pandemic," and to what extent the pandemic has changed user demand for games. Media perspective often quantifies and evaluates games from an objective and fair perspective (such as graphics quality, game difficulty, and other academic indicators), so it can be concluded that XBOX games have remained stable and excellent in quality before and after the pandemic.
User perspective is more based on playability and user-generated ratings. After the pandemic, we found that users' high ratings shifted from the PC end to the Switch end, which to some extent also confirms a news fact: the pandemic has stimulated users' game entertainment demand, and we can also know that hardcore users are gradually shifting from PC to Switch during the pandemic. Combining with Figure 3.2, we can see that while the number of Switch games is decreasing, they are receiving higher ratings, indicating that games on this platform are increasingly being accepted and showing a trend of becoming "high-quality."
Based on this, we can also pose a more interesting question for scholars to study: based on the fact that Switch is a more family-like game and combined with the fact that Switch games are more popular, we can further explore whether the pandemic has changed users' entertainment habits to some extent. Or, have users become more willing to spend money on games for entertainment after the pandemic?
Trend of Genres’ Change
Step 1: 
Check the number of games in each genre.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/7c11dc44-0616-412f-aa21-9ea3b3ebc8d4)

4.1 Top ten genres with the highest published number
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/797a8736-a247-47ad-86ae-f3b577c2d72c)

4.2 Top ten genres with the highest published number during COVID（2019-12-31 to 2023-01-01）
As shown in Figure 4.1, Action, General, Action Adventure, Role-Playing and Adventure are still the top five game genres in terms of quantity over the past six years. For comparison purposes, we also compared the genres with the highest number of releases during COVID period as shown in Figure 4.2 which remained consistent with overall trends.
This proves that the outbreak of COVID did not have a significant impact on game market type creation; these five types have always been favored by game developers.

Step 2: 
Check changes in quantity trend for each genre.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/0c61434d-15bc-4e34-a220-7bebf696b770)

4.3 Quantity trend for each genre (all time)
From a temporal perspective as seen from Figure 4.3 ,the number of games across all major gaming categories has generally decreased over the past six years. Even between 2019 and 2021 when there was an enormous demand for video games due to covid pandemic only few types such as card game, minigame, snowboard showed growth trends. However, since 2022,the numbers have significantly reduced reaching an all-time low point.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/73da9c59-9109-483c-ab3c-c33f8458c5de)


4.5 Quantity trend for each genre (December 31st ,2019 - January 1st ,2023)
When we focus on Covid outbreak period as seen from figure(figure no) we can clearly see that action adventure and action were among those having maximum releases during this three-year period. Action peaked between Jan-Sep'20 while action-adventure peaked between Nov'20-Aug'21.After going through common decline phase both entered stable growth phase after entering year '22.
It should be noted that generally speaking, games often possess multiple attributes. For instance, a game can be both an action game and an action-adventure game, or a role-playing game. This is very common in the gaming market. However, we can see that the decline trend of many types of games not only far exceeds the top five genres but also far exceeds the overall trend of releases.
We believe this reflects a tendency towards increasing homogenization in gaming genres: the number of top genre games is increasing while other types are decreasing.

Step 3: 
Check changes in media and user ratings for each genre.
Due to our earlier finding that fewer types were becoming more prevalent, we analyzed only the top ten genres with data research value.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/d646326b-2fa4-4508-ae0b-80b8ebf27a1f)

4.6 Average rating change trends for each genre (Top 10) by media
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/6c62856b-34a2-4b6d-b5ea-e3defdd2b22d)

4.7 Average rating change trends for each genre (Top 10) by users
We found that media ratings tend to converge relatively similarly across different types of games which proves that quality is less affected by type; player ratings fluctuate more evenly but since 2022 there has been significant differences between user ratings among different types. Arcade, Shooter, and 3D type's average user rating have dropped rapidly. This shows that different game categories have a greater impact on player acceptance.
In addition, COVID did not significantly affect these fluctuations during at least our sampled top ten game genres.
5. Predictions
As previously stated, we utilize the AutoTS library to forecast the mean media score 45 days after the dataset using four distinct periods: overall, pre-epidemic, during epidemic, and post-epidemic.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/f486dbda-0cbe-4d96-8cb7-755494c38fcb)

5.1Critic score trend of all time
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/26e37679-a094-46d0-8a2e-f70c0fdc6598)

5.2Critic score trend before COVID
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/582ac80d-cb72-4541-a63d-f479cf604e72)

5.3Critic score trend during COVID
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/1c5bc626-b620-4f26-a1c4-a88946effe2d)

5.4Critic score trend after COVID (Prediction)

Our main objectives are:
1. To predict the general trend of future game product quality, whether it will increase or decrease and if there will be more fluctuations, based on existing data using a simple average performance format.
2. During our exploration process, we found that the predicted values differ greatly depending on the time period due to their dependence on the performance of data in the dataset. Therefore, we believe that the predicted results - including numerical values and fluctuations - can also reflect overall data performance during this period. Specifically, if numerical values show an upward trend or fluctuations are relatively stable, it indicates good performance of training data sets for models; otherwise not.
Therefore, we believe that predictive data produced at different times can also serve as a reference point. For example, if there is significant fluctuation in predicted scores during an epidemic compared to before it occurred, then we can conclude that epidemics have a significant impact on game quality.
We first observe the prediction results for the entire time period. From this observation, we see that within 45 days from now (the prediction date), industry-wide game ratings will hover between 73 and 82 points. Compared with previous years' averages which were mostly around 75 points per year; this score range shows better performance indicating an upward trend in industry products.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/def96ea4-adeb-45ee-8e4d-042191305e3a)

Next, let's compare the four predicted trends as a whole:
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/02011f7b-90b3-44b5-8c4b-ee970985baae)

We can extract many useful information from it.
For example:
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/3a8c3f62-321b-419d-83c7-c293f0948f68)

Comparison between during and before the outbreak of COVID
It can be seen that during the three-year period of the COVID outbreak, there was a significant fluctuation range, which proves that the epidemic has had a significant impact on the industry. However, compared to before the outbreak, the output quality during this period may have reached higher scores, proving that there is actually an upward trend in quality.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/a64dc5ef-fa92-4dc1-adfa-ade24792fe70)

Comparison between after and during COVID
It can be concluded that the amplitude of fluctuations has weakened and score ranges have significantly increased. This proves that the industry is gradually getting rid of COVID's influence.
![image](https://github.com/SIMBA19991111/Data-Analytics-on-Game-Industry-Reviews-in-COVID-period-and-Future-Development-Trend-Prediction/assets/113533985/2314633c-5d16-42a1-99fa-307aab0f63e8)

Comparison between after and before COVID
Compared to before COVID outbreak, it can be seen that score ranges have significantly increased after its outbreak. This proves that current output quality in this industry may even exceed pre-COVID levels.
Conclusion:
① The overall prediction shows that game quality is becoming higher and should continue to remain stable;
② During pandemic periods there were large fluctuations which prove gaming industry was greatly affected by COVID. But currently with pandemic ending soon we see an obvious upward trend overall. Therefore, we are optimistic about future development prospects for gaming industry.
