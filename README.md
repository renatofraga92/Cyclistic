# Cyclistic
My Capstone Project for the Google Data Analytics Course

Scenario:

I am a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director
of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore,
my team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights,
my team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives
must approve my recommendations, so they must be backed up with compelling data insights and professional data
visualizations.

Three questions will guide the future marketing program:
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

# Solution

The Cyclistic company is looking for answers... The finance team have come to the conclusion that the annual membership clients are more
profitable than the casual ones. So the main question is: How to convert these casual riders into membership clients?

First things first. Let's look at some data and recognize how they behave, look for differences and similarities on how they use the service.

Link for access the data:
https://divvy-tripdata.s3.amazonaws.com/index.html


To have a first contact with the data set, let's simply open it with Microsoft Excel


Let's start comparing casual vs annual members::

![image](https://user-images.githubusercontent.com/96549926/179627449-6954243d-0062-428e-9e79-9026ff9522a7.png)

We've got 52,02 % of annual members and we're aiming to increase this number.

Let's look for some patterns between those.

There are 2 main variables we can analyze to get our answers:
- Type of bycicle (There are 3)
- Duration of the ride

First, we gonna clean the data. We have the initial and end date/time of the trip, but not the total duration. Lets include this important information.

Type of bycicle

There are 3:

We can see what are the preferences of members and casuals

![image](https://user-images.githubusercontent.com/96549926/179864027-be8bf4e0-946c-427a-91ce-98673007d656.png)

The docked bikes are used only by casuals, which seems pretty obvious.
The members has a preference for the classic bike.


Duration

We can find it by subtracting final and initial time. Creating a new column, with this new information.

Making a column graph we can have this following visual:

![image](https://user-images.githubusercontent.com/96549926/180618337-40005d00-2d00-4c24-bf2f-d3bf941214bc.png)


It shows us that, not only the casual have more number of trips, but they also have bigger duration of the rides.


Now, lets remind some questions we've been asked.

How do casual and members use our bikes differently?
R- Casuals has the docked bike as exclusive. Not only that, they are in bigger number of rides and the duration of the rides.

How would Casuals would buy the annual membership?
R- The company must focus on bring the benefits to the casuals who uses Cyclistcs more often. The numbers shows us that there are a lot of potential clients,
through the study of the duration the trips. For sure the number of different people who uses the bike is very very higher than the casuals. The data doesn't shows
it to us, but it is comprehensive, if there aren't a cadastration for casuals riders. Another insight we can get through the data is that the revenue for the casuals
are bigger than the membership. The company will increase this revenue bringing those people who uses Cyclistic more often.

How the company can use digital media to influence casual riders to become a member?
R- It can use to bring the benefits of becoming a member rider


Link to the files which were used in the analysis https://1drv.ms/u/s!Am_rbw_sYFru634m8PDSTmkb-_d0?e=3ZuTMn








