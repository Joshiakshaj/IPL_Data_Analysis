IPL Data Analysis
2008-2018

Key Points: EDA, Data Viz, Pivot Tables, Slicer, VLOOKUP Function, Dashboard Making

Existing Dataset Provides Data about:
city	Sesion	date	Session	venue	team1	team2	toss_winner	toss_decision	result	winner	win_by_runs	win_by_wickets	umpire1	umpire2
![image](https://github.com/Joshiakshaj/IPL_Data_Analysis/assets/129145776/644d0c3a-1d3a-4f7e-9950-74daa0834736)

Dataset Preview:

![image](https://github.com/Joshiakshaj/IPL_Data_Analysis/assets/129145776/5d5ea2fe-c037-4337-989a-d350f4a8d0c3)

Some questions we can find the solutions to in this dataset:
1. Most Wins by Team Seasonwise
2. Match of the Match by Season
3. Player of the Series for each season(each year)
4. Number of Match Wins by Teams with bat first and field first?
5. Toss Decision based winning percentage
6. Total number of matches won by any Team
7. Venuewise distribution of Toss Choices etc.

Pivot Tables Created:
1. Top 7 Winning Teams:
   ![image](https://github.com/Joshiakshaj/IPL_Data_Analysis/assets/129145776/b11290bd-8b2e-4008-985d-ccfb04dd74de)

2. Team Win Vs. Toss Decision:
   ![image](https://github.com/Joshiakshaj/IPL_Data_Analysis/assets/129145776/0acb8341-caa3-4a9d-9021-7aa62626c820)

3. Winner Vs. No. of Times Won
   ![image](https://github.com/Joshiakshaj/IPL_Data_Analysis/assets/129145776/776cd456-d25a-44b0-9d29-5edcafbcfb4d)

4. Toss Decision Vs. Result
   ![image](https://github.com/Joshiakshaj/IPL_Data_Analysis/assets/129145776/f78c2895-4e7b-44c2-bbf0-f8236ac71483)

5. Venuewise Bat Vs. Field
   ![image](https://github.com/Joshiakshaj/IPL_Data_Analysis/assets/129145776/fcf70623-f24f-43a5-a923-dd7d79d6e7bb)

6. LookUp Table
   Using the 'team winner worksheet'
   Season	Winner	Runner Up	Player of the Match	Player of the Series	
IPL-2018	Chennai Super Kings	Sunrisers Hyderabad	Shane Watson	Sunil Narine	
IPL-2017	Mumbai Indians	Rising Pune Supergiants	Krunal Pandya	Ben Stokes	
IPL-2016	Sunrisers Hyderabad	Royal Challengers Bangalore	Ben Cutting	Virat Kohli	
IPL-2015	Mumbai Indians	Chennai Super Kings	Rohit Sharma	Andre Russell	
IPL-2014	Kolkata Knight Riders	Kings XI Punjab	Manish Pandey	Glenn Maxwell	
IPL-2013	Mumbai Indians	Chennai Super Kings	Kieron Pollard	Shane Watson	
IPL-2012	Kolkata Knight Riders	Chennai Super Kings	Manvinder Bisla	Sunil Narine	
IPL-2011	Chennai Super Kings	Royal Challengers Bangalore	Murali Vijay	Chris Gayle	
IPL-2010	Chennai Super Kings	Mumbai Indians	Suresh Raina	Sachin Tendulkar	
IPL-2009	Deccan Chargers	Royal Challengers Bangalore	Anil Kumble	Adam Gilchrist	
IPL-2008	Rajasthan Royals	Chennai Super Kings	Yusuf Pathan	Shane Watson	
![image](https://github.com/Joshiakshaj/IPL_Data_Analysis/assets/129145776/7d8ae663-efcc-4430-b96b-c99ad081a764)

LookUp Table: (Using Vlookup function, referencing copy of the above data in same worksheet)

![image](https://github.com/Joshiakshaj/IPL_Data_Analysis/assets/129145776/d30a6d95-5472-41ed-a019-7c55d9b561a9)
Values Shift by using Slicer

Slicer: ![image](https://github.com/Joshiakshaj/IPL_Data_Analysis/assets/129145776/b7a623f5-5899-4968-9d49-48aae3f528dd)

=====================================================================================================================================

DashBoard:

Copy all Pivot Tables on the worksheet labelled "Dashboard"

Insert Shapes as such: ![image](https://github.com/Joshiakshaj/IPL_Data_Analysis/assets/129145776/2d925e6f-0adf-4efc-844a-3084dc3c754d)
![Screenshot 2024-02-23 145303](https://github.com/Joshiakshaj/IPL_Data_Analysis/assets/129145776/e4e3dc52-af40-4e76-b816-00d30e8a8ba0)
(Gridlines/Cell Lines can be removed)

Parallely insert Slicer with desirable height, width and color schemes as such:
![Screenshot 2024-02-23 145537](https://github.com/Joshiakshaj/IPL_Data_Analysis/assets/129145776/b4f28fc3-5fa5-458c-bdca-a3318e130296)

Now, Click on the Slicer and Slicer column is enabled to the right of 'Help'
Report Connections to all Pivot Tables on Dashboard and now the Slicer can be used
to Look up year wise Stats on all Pivot Tables simultaneously

Final Look for Dashbaord:
![Screenshot 2024-02-23 145952](https://github.com/Joshiakshaj/IPL_Data_Analysis/assets/129145776/d8afe116-4018-4582-87eb-00d9e131251d)

Key Insights Drawn (2008-2018):
1. 59% of times teams that chose to field have WON
2. Most Wins- Mumbai Indians: 98
   Chennai Super Kings: 90
   Kolkata Knight Riders: 86
3. Teams have chosen to field the most at MCA Stadium (19 out of 21 times; 90.47% times)   
4. Teams have chosen to bat the most at Chidambaram Stadium (34 out of 49 times; 69.38% times)
5. Kochi Tuskers had only won when they chose to field (6 times)
6. More Chances to win when chosen to field as Toss Decision: MI, KXIP, RCB, KKR, DD, RR, DC, RSP, GL
7. More Chances to win when chosen to bat as Toss Decision: CSK, PWI (Correleted to MSD Captaincy)





    
   
   

   

   
   




