# *Module-4-Python-Project*

# **ABC Basketball Company Comprehensive Employee Analysis**
## *The csv file contains the details of the different Basketball team members. we have to analyse the data, based on the csv file extracted*.
![image](https://github.com/user-attachments/assets/05c6cdbd-bed6-4495-acb9-c348a3019b97)
## **In the project document it has informed that the column which contains details of the 'Height' need to be replaced with a new value. Hence we have deleted the column with the heading 'Height'. The data which has popluated in the 'Height'column was the date. The new column 'Height' needs to be created with random number from 150 to 180**
![image](https://github.com/user-attachments/assets/06990d30-0b97-4c5f-b601-ef6908299599)
![image](https://github.com/user-attachments/assets/4ba7ba25-c5e9-4f7b-9a31-b9ec296d6289)
**Keeping a backup copy of our CSV file before making any changes is a great practice. This ensures that we can always revert to the original data
if something goes wrong during data processing or if we need to compare changes later.**
![image](https://github.com/user-attachments/assets/b714e096-499c-463e-a2b5-02f0810be593)
**When handling missing data, it is essential to identify the numeric and categorical fields. This is because the approach to managing missing data varies depending on the type of data.**  

**Below is the procedure to identify them:**  
 
**Identify the Numerical columns and display the count of numerical columns with null values**  

**Identify the Categorical columns and display the count of Categorical columns with null values**  

**Display the Df file to show the column which has missing values**

![image](https://github.com/user-attachments/assets/85ce2384-d51e-4fc2-9cec-fe180afbd1dc)
![image](https://github.com/user-attachments/assets/83fa682e-9ee5-426a-93c3-57e165f1264f)

**Procedure to update the numerical column with the mean value**

**Procedure to update the Categorical columns with the Mode** 

**Display the number of records updated in numeric column**

**Display the number of records updated in categorical column**

**Display only the columns which has udated with the updated Values**

**Display the Data frame with the updted values** 

**Save  the updated CSV file**
![image](https://github.com/user-attachments/assets/d641f5ff-ccdb-491f-9936-9882b10615eb)
![image](https://github.com/user-attachments/assets/ac64b405-1720-4e34-9a79-7b7555e8bdd0)
**Remove the duplicates  from the dataframe as part of the data cleaning process*

**The [suebset] parameter specifies which columns to consider when identifying duplicate rows.
Essentially, it tells pandas to look only at these specified columns to determine if a row is a duplicate. That means the pandas will consider 
one row as duplicate only if the columns mentioned in the  subset parameter values are  same.**
![image](https://github.com/user-attachments/assets/483601a9-4121-4fef-8679-67b1377d7203)

![image](https://github.com/user-attachments/assets/3b466a81-b97c-48b7-be30-bb0f12132b3f)

![image](https://github.com/user-attachments/assets/be4b4804-e11f-4702-a86e-12b4646d874d)

![image](https://github.com/user-attachments/assets/898275a1-973e-4c4e-9e0f-3bc7f9b8afee)

![image](https://github.com/user-attachments/assets/318ac86e-e1cb-44b8-818b-ba3740a40265)

![image](https://github.com/user-attachments/assets/352b89f5-413c-446f-a86c-e4292f54f5de)

## *1.	Determine the distribution of employees across each team and calculate the percentage split relative to the total number of employees.* 
![image](https://github.com/user-attachments/assets/5b11b8a0-5e7a-408a-b81b-2cc71df729bf)

![image](https://github.com/user-attachments/assets/479ebde7-ffb4-41ca-b789-3a9035f65a0f)

**Plotting the percentage split**


![image](https://github.com/user-attachments/assets/c410c4f0-a40f-4ff1-8279-e185cea1a4e7)

**Here's the table with each team's percentage split and their difference against the New Orleans Pelicans (the team with the highest percentage):**

![image](https://github.com/user-attachments/assets/4bd1a062-e90b-4f7f-a080-028a039752c6)

![image](https://github.com/user-attachments/assets/7660bc7c-3bdd-4e40-a2d2-a56b5855c0d2)


## **Here are a few insights based on the percentage splits and differences for the teams:**


 **1.	Uniformity Among Most Teams: The majority of the teams have an employee percentage split of 3.28%, which shows a fairly even distribution across  the team.**
  
 **2.	New Orleans Pelicans and Memphis Grizzlies: The Pelicans stand out with the highest percentage of 4.15%, followed closely by the Grizzlies at 3.93%. This indicates that these two teams have a slightly larger workforce compared to other teams.**
  
 **3.	Small Differences: The difference between most teams and the New Orleans Pelicans is only around 0.87%. This suggests that while the Pelicans have the highest number, the overall distribution is still relatively close among all teams.**
  
 **4.	Outliers: The teams with the smallest workforce percentage—such as the Minnesota Timberwolves and Orlando Magic with 3.06%—indicate slightly fewer employees compared to the rest of the league, differing by about 1.09% from the Pelicans.**
  
 **5.	Balanced Representation: Overall, the data shows a balanced representation of workforce distribution, ensuring that no single team has a disproportionately large or small share of the total employees.**
  
 **This balanced distribution Shows a structured approach in employee allocation across the teams, potentially aiming for uniformity in operations and management within the league.**

# *2.  	Segregate employees based on their positions within the company*

 **Following  are  some of the different methods to display the  details of the employess based on their postion within the company**

 **The Team mebers are segragate into C, PF,PG, SF & SG**

 **•	Centers (C): 79 players**  

 **•	Power Forwards (PF): 100 players**  

 **•	Point Guards (PG): 92 players**  

 **•	Small Forwards (SF): 85 players**  

 **•	Shooting Guards (SG): 102 players**  

![image](https://github.com/user-attachments/assets/ccef6513-d91d-436e-8b9d-9c155cc1d723)


![image](https://github.com/user-attachments/assets/70c8fd61-1df2-456c-9961-272642703b79)


![image](https://github.com/user-attachments/assets/d2f82665-a09e-4f45-829f-4ae3ffb854d4)


![image](https://github.com/user-attachments/assets/13890c26-5b58-47c4-8d65-8ad19fd6a738)


![image](https://github.com/user-attachments/assets/41c624ab-15f5-46ac-b232-2d1f6959e073)

![image](https://github.com/user-attachments/assets/2c7b0048-4213-4efc-b6b5-5de109d76113)

# *Bar Chart representation of the segragated team members within the Company*

![image](https://github.com/user-attachments/assets/e1a6dc37-d809-4b62-8404-5e090d751612)

![image](https://github.com/user-attachments/assets/f7e9f580-69a2-4b9e-948a-f5e083fd50bc)

# *Position wise number of team members within the Company with the Count in each position*

![image](https://github.com/user-attachments/assets/e2149fa6-00cd-4d54-9605-6b4cef156a45)

![image](https://github.com/user-attachments/assets/1a2c0c5e-8880-4349-9641-f4d8538edf66)

# *Representation of Position wise number of team members within the Company , using the Pie Chart*


![image](https://github.com/user-attachments/assets/3f8249b0-30fd-4ac9-af1a-4338be9505fb)

![image](https://github.com/user-attachments/assets/1f859cc6-df61-4338-b8cf-d5fdc4434076)

# *Segregated list of Employees based on Position in each Team*

![image](https://github.com/user-attachments/assets/439148d5-1239-461d-bfa4-46a5910709a4)
![image](https://github.com/user-attachments/assets/4c61627b-2acb-4135-ba96-90ac054fcce0)
# *2.       Segregation of Employees Based on Position in Each Team , graphical representation*

![image](https://github.com/user-attachments/assets/6266aff1-7481-4d4d-8db2-8d6ef04f7ddf)
![image](https://github.com/user-attachments/assets/e33e0bcd-1534-49f6-865a-93f9a6f0c2a3)

## *Key findings and Insights based on the segragated count of employees with their position in the team*

### *Position Distribution:*

 **•	Shooting Guards (SG): 102 players**
 
 **•	Power Forwards (PF): 100 players**

 **•	Point Guards (PG): 92 playerse** 

 **•	Small Forwards (SF): 85 players**

 **•	Centers (C): 79 players**

### *Shooting Guards (SG):*
    
 **•	Highest number of players, indicating a wide focus on scoring and defense.**

 **•	Teams like the Brooklyn Nets stand out with a higher number of shooting guards (6), suggesting an emphasis on backcourt rotation.**


### *Power Forwards (PF):*
    
 **•	The second most common position, showing the ability of adaptability of the  forward players who can contribute on both offense and defense.**

 **•	Memphis Grizzlies lead with 6 power forwards, suggesting a strong focus on this position Point Guards (PG)**

 **•	Essential for playmaking and ball handling, with a significant number of players across teams.**

 **•	Memphis Grizzlies again lead with 5 point guards, highlighting their strategy around strong guard play.**

### *Small Forwards (SF):*
     
 **•	Fewer in number, but crucial for versatility and flexibility in both offensive and defensive plays.**

 **•	Golden State Warriors have the highest number of small forwards (5), emphasizing versatility.**

### *Centers (C):*

 **•	Least represented position, indicating a potential shift towards small ball lineups and positionless basketball.**

 **•	Teams like San Antonio Spurs and Utah Jazz have the highest number of centers (4), potentially focusing on traditional big men roles.**

### *Player Distribution Insights:*

 **Teams with 15 Players:**  

 **•	The majority of teams have 15 players, which is the standard roster size. This includes teams like the Atlanta Hawks, Boston Celtics, Brooklyn
    Nets, and others.**
    
 **Teams with More Than 15 Players:**
    
 **•	Memphis Grizzlies: 18 players**

 **•	New Orleans Pelicans: 19 players**

**•	Milwaukee Bucks: 16 players**

 **•	New York Knicks: 16 players**

 **•	Utah Jazz: 16 players**

 **These teams have larger rosters, potentially indicating a strategy that involves greater flexibility. The New Orleans Pelicans have the largest roster with 19 players, suggesting a strong emphasis on having a variety of options and possibly dealing with injuries or strategic rotations.**
    
**Teams with Fewer Than 15 Players:**

 **•	Minnesota Timberwolves: 14 players**

 **•	Orlando Magic: 14 players**

**These teams have smaller rosters, which might indicate a focus on a more tight-knit, core group of players, or it could be due to attrition, injuries, or other roster changes.**

**Following are some of the different methods to display the details of the employess based on their postion and age group**
# *3.	Identify the predominant age group among employees*

![image](https://github.com/user-attachments/assets/d1299843-449c-4862-ab9a-10dcfbc55705)
![image](https://github.com/user-attachments/assets/03b05191-d85b-41f4-98d4-d5c12be5f7b6)
*Bar chart to show the count of employess in each age group*
![image](https://github.com/user-attachments/assets/95b88611-e9c1-43aa-b7ee-866dc46f5dcf)
![image](https://github.com/user-attachments/assets/273ee34a-744f-4350-a0f7-3fb7e0bf03fe)
*The predominat age group based on the position*
![image](https://github.com/user-attachments/assets/17f7c16a-e295-4d74-ab05-8ed3ac7580ed)
![image](https://github.com/user-attachments/assets/5b8a60f9-1b66-46d5-b8ad-e841923b4fb0)
*Bar chart to represent the predominant age group by Position*
![image](https://github.com/user-attachments/assets/8657daa5-7e24-4a4b-a876-af84c198888b)
![image](https://github.com/user-attachments/assets/7096c0e5-397a-42b5-925e-1ce74cf0b38d)
**Display the details of each team with Position, Age group, Count of employees falls under each age group**

![image](https://github.com/user-attachments/assets/eae490bd-079b-4770-a96b-70296400e881)
![image](https://github.com/user-attachments/assets/f2b85939-872d-47ab-9353-bd66abb72239)
*Graphical representation of the team which fall under different age group and Position*
![image](https://github.com/user-attachments/assets/5f6486de-3af0-472f-8c8c-db19eebca6e9)
![image](https://github.com/user-attachments/assets/2d2bc566-32ed-4817-b3d2-1255088ad564)
### *Insights:*
**1.	Centers (C):**  
**o	The predominant age group for Centers is 25-34 with 54 individuals. This suggests that this position tends to attract more experienced players in their prime years.**  
**2.	Power Forwards (PF):** 
**o	The predominant age group for Power Forwards is 25-34 with 62 individuals. This is consistent with the trend seen for Centers, indicating that this position also benefits from players in their peak physical condition and experience.**  
**3.	Point Guards (PG):**
**o	The predominant age group for Point Guards is 25-34 with 58 individuals. Point Guards are typically the playmakers on the team, and having more experienced players in this role can be crucial for game strategy.**  
**4.	Small Forwards (SF):**
**o	The predominant age group for Small Forwards is 25-34 with 50 individuals. This position often requires versatility, and players in this age group are likely to have the necessary skills and physical fitness.**    
**5.	Shooting Guards (SG):**
**o	The predominant age group for Shooting Guards is 25-34 with 48 individuals. Shooting Guards are key scorers on the team, and having players in their prime years can enhance the team's offensive capabilities.**
### *Overall Insights:*  
**•	The 25-34 age group is dominant across all positions, indicating that this age range is critical for the team's performance and success.**  
**•	Experience and Physical Prime: Players in the 25-34 age group are generally in their physical prime and have significant experience, making them valuable assets to the team.**  
**•	Consistency Across Positions: The consistency of the 25-34 age group being predominant across all positions suggests that this is a key age range for achieving peak performance in basketball.** 

### *Actionable Strategies:*  

**•	Retention and Development: Focus on retaining players in the 25-34 age group by providing career development opportunities, advanced training, and competitive compensation.**    
**•	Injury Prevention: Implement comprehensive injury prevention and management programs to ensure that players in this age group remain in peak condition.** 
**•	Succession Planning: Prepare younger players (18-24 age group) to eventually take over key roles by providing mentorship and development programs.** 
## *4.	Discover which team and position have the highest salary expenditure.*
![image](https://github.com/user-attachments/assets/40c7e195-8b8a-40d5-b376-79d8f5d5f212)
![image](https://github.com/user-attachments/assets/75c0e6a1-da81-49d3-a787-8242f93cbe04)
![image](https://github.com/user-attachments/assets/e9ca37d6-57b3-42b1-9983-67e8627de98a)
**Display the details of the salary expenditure by Team and  position**
![image](https://github.com/user-attachments/assets/5d0ec6d2-134a-4c87-be66-87fb8f8e1f93)
![image](https://github.com/user-attachments/assets/cccb0e74-48b8-4cc2-bbd9-6f770be82e8c)
**Plotting the total salary expenditure for each team and position using a stacked bar plot**
![image](https://github.com/user-attachments/assets/2d46014f-067f-44d9-808a-590a10be5db6)
![image](https://github.com/user-attachments/assets/ef230f80-6014-4660-b505-7386e62ae3ce)
**Graphical representation of the salary expenditure of the team by position**
![image](https://github.com/user-attachments/assets/cc5fa48d-6f57-4dc5-a737-c334ec1385a5)
![image](https://github.com/user-attachments/assets/5a27ae05-1efe-4bc5-890d-34a2e3363add)
**Scatter Plot diagram of the salary distribution on each age group**

![image](https://github.com/user-attachments/assets/8212b2b5-813e-4ebf-ba34-e8af0180b894)
![image](https://github.com/user-attachments/assets/28065c48-9771-4578-9344-f6216d32b347)
**Salary of the entire employees sort by Salary,Team in the descending order**
![image](https://github.com/user-attachments/assets/0491fa26-b56d-4ef6-b856-22be8253bd98)
![image](https://github.com/user-attachments/assets/840f7ac9-a76c-45a6-887a-34431263b4f6)
**Team Wise Salary Expenditure**
![image](https://github.com/user-attachments/assets/543b4f8c-de4f-4c5a-93a8-df2f66d984e3)
![image](https://github.com/user-attachments/assets/6a7d6eb8-530a-40de-bcf4-8aa3811d2da2)
**Plotting the total salary expenditure for each team using a horizontal bar plot**
![image](https://github.com/user-attachments/assets/24176200-2e84-4dbc-8fef-873b86e8e26a)
![image](https://github.com/user-attachments/assets/58bba505-7450-4756-b7ac-a77a37182a83)
**Dispaly the entire team salary in the ascending order**
![image](https://github.com/user-attachments/assets/c6c1bbce-e7f9-4a93-8658-487d36eef2e2)
![image](https://github.com/user-attachments/assets/c05dbb93-3b05-4f84-8a8d-fa6bbc0d65a0)
**Plotting the salary distribution by Team in ascending order**
![image](https://github.com/user-attachments/assets/ccf95216-bcbf-4434-9272-abfbebcb53f4)
![image](https://github.com/user-attachments/assets/15e10528-c23f-451e-a889-db3140c876b4)
**Plotting the total salary expenditure for each team and position using barplot**
![image](https://github.com/user-attachments/assets/1f5ce30a-3616-4e05-b209-49bbfe3eeb19)
![image](https://github.com/user-attachments/assets/b1973ee1-bf62-440c-bc35-6a9f3c67e35f)
### *Based on the salary expenditure data for the various teams and positions, here are some key insights:*  
**Insights:**  
**1.	Team with the Highest Salary Expenditure:*   

**o	Team: Los Angeles Lakers** 
**o	Position: Small Forward (SF)**  
**o	Total Salary Expenditure: \$31,866,445.0**  
**o	The Los Angeles Lakers invest heavily in the Small Forward position, suggesting that this position is crucial to their strategy and performance.** 

**2.	Top 5 Teams with the Highest Salary Expenditure:**

**o	Los Angeles Lakers (SF): \$31,866,445.0**  
**o	Miami Heat (PF): \$31,538,671.0**
**o	Houston Rockets (SG): \$28,122,883.0**
**o	Phoenix Suns (PG): \$28,002,998.0**  
**o	Denver Nuggets (SF): \$27,982,771.0**  
**o	These teams prioritize certain positions significantly more than others, likely due to the strategic importance of these roles.**  

**3.	Position Trends:**
**o	Small Forwards (SF) and Power Forwards (PF) appear frequently among the top salary expenditures.**  
**o	Positions like Shooting Guard (SG) and Point Guard (PG) also show significant salary investments.**  
**o	This suggests that forwards and guards are highly valued across multiple teams, possibly due to their versatile roles in both offense and defense.**

**4.	Salary Distribution Patterns:**

**o	Los Angeles Lakers and Miami Heat lead the list, indicating their financial strength and willingness to invest in top talent.**  
**o	Teams like the Washington Wizards and Boston Celtics also show substantial investments in positions like Point Guard and Shooting Guard.**  
**o	Teams with lower salary expenditures for certain positions may either focus on developing younger talent or prioritize other roles.** 

**5.	Mid-Tier and Lower Salary Expenditures:** 
**o	Teams like the Minnesota Timberwolves and Denver Nuggets have a more balanced salary distribution across positions.**   
**o	Teams with the lowest salary expenditures (e.g., Orlando Magic (SF): \$845,059.0) might be focusing on rebuilding or
    have a different strategic approach.** 

       
**Detailed Insights:**  

**Highest Investment Positions:**

**The Small Forward (SF) and Power Forward (PF) positions are highly prioritized across top teams. This reflects the strategic importance of these positions, likely due to their versatility in both offense and defense. Teams investing heavily in these positions aim to enhance their scoring, rebounding, and defensive capabilities.**

**Team Strategies:**

**Los Angeles Lakers: Their significant investment in the Small Forward position suggests that they rely heavily on the performance of their SFs to drive team success. This could mean a focus on scoring, playmaking, and versatility.**

**Miami Heat: With the highest expenditure on Power Forwards, Miami Heat may focus on strong interior play, rebounding, and defending the paint, indicating a strategy centered around dominating the key areas of the court.**

**Houston Rockets: Their top investment in the Shooting Guard position suggests a strategy focused on perimeter scoring and three-point shooting.**

**Phoenix Suns: The heavy investment in Point Guards highlights their reliance on playmaking, court vision, and offensive orchestration by their PGs.**

**Denver Nuggets: Similar to the Lakers, their investment in Small Forwards indicates a strategic emphasis on versatile wing players who can contribute on both ends of the court**

**Salary Distribution Across Teams:**

**Teams with balanced salary distributions (like the Minnesota Timberwolves and Denver Nuggets) may focus on a more holistic team approach, ensuring depth and balance across all positions. This strategy can be beneficial in maintaining team performance even with injuries or player rotations.**

**Lower salary expenditures for certain positions (e.g., Orlando Magic's low investment in SF) could indicate a rebuilding phase, development of younger talent, or a strategic focus on other positions.**

**Financial Strength and Willingness to Invest:**

**The financial might of teams like the Los Angeles Lakers and Miami Heat is evident from their top salary expenditures. Their willingness to invest in top talent showcases their ambition to compete at the highest levels and attract superstar players.**

**Teams with lower expenditures may be adopting a more cautious financial strategy, possibly aiming for sustainable growth, developing homegrown talent, or focusing on long-term financial stability.**

**Emerging Patterns and Trends:**

**A trend towards investing heavily in versatile and high-impact positions like Small Forwards (SF) and Power Forwards (PF) can be observed. This indicates that modern basketball strategies value players who can contribute in multiple aspects of the game.**

**Guards (SG and PG) also receive substantial investments, highlighting the importance of backcourt players in dictating the tempo, facilitating offense, and scoring from the perimeter.**

**These insights provide a deeper understanding of the strategies and priorities of various teams based on their salary expenditures.** 

![image](https://github.com/user-attachments/assets/65bda7c7-a748-4b94-ae47-1054d5c78554)
![image](https://github.com/user-attachments/assets/22b4dfec-d94f-43ea-bc62-40bb21e37d6e)
![image](https://github.com/user-attachments/assets/4ddca8dd-4978-4072-857e-5294e5105be9)
![image](https://github.com/user-attachments/assets/c4ad4f21-9b20-4404-8677-5b929bd03ca8)
![image](https://github.com/user-attachments/assets/8a054cf4-d687-4f2b-b516-211b58d2ad6c)
## *Correlation Coefficient: 0.214*

**Interpretation: The value of 0.214 indicates a weak positive correlation between Age and Salary. This means there is a slight tendency for Salary to increase as Age increases, but the relationship* is not very strong.**

**Implications:**

**Weak Relationship: The weak correlation suggests that while there might be some relationship between Age and Salary, other factors likely have a stronger influence on Salary.** 

**Additional Variables: It's possible that other factors such as experience,  job position, or industry play a more significant role in determining Salary than Age alone.**
