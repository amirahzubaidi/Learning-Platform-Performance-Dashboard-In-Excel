## Learning Platform Performance Dashboard In Excel

### Introduction: 
In the digital age, online learning platforms have become a preferred choice for millions to develop their skills and gain knowledge anytime, anywhere. But with so many options, how can we choose the best? This performance dashboard sheds light on key metrics such as ratings, completion rates, pricing, and user engagement for four top platforms: Udemy, LinkedIn Learning, Coursera, and edX.

💥 Key Metrics: 
<br>Average Rating: 3,99/5
<br>Engagement Rate: 2,14
<br>Total Users: 25.3 Million 
<br>Total Course: 10.000
<br>Completion Rate: 75,1%

📊 Visualizations:
<br>☑️ Top Platforms by Completion Rate:
The platform with the highest completion rate is Udemy (75.10%), followed by LinkedIn Learning (75.08%).
<br>☑️ Average Prices per Platform:
The platform with the highest average price is Coursera ($108.04), while the lowest price is edX ($104.64).
<br>☑️ Enrolled Students by Percentage:
The distribution of enrolled students is even among the four platforms with 25% each.
<br>☑️ Average Course Duration per Platform:
LinkedIn Learning has the longest course duration (55 hours), while Coursera has the shortest (53.3 hours).
<br>☑️ Top Platforms by Rating:
The highest ratings belong to edX, Coursera, and Udemy (4.00), while LinkedIn Learning is slightly lower (3.97).
<br>☑️ Total Categories per Platform:
Udemy has the most number of categories (2,554), while Coursera has the least (2,466).
<br>☑️ Total Students per State Map:
Shows the distribution of students in different states, each state's numbers range from 4.135 million to 4.346 million, Kentucky being the highest.
<br>☑️ Average Courses Rating per Platform:
Each platform has different average ratings depending on the category, with categories like Technology tending to get higher ratings.
<br>☑️ States with the Highest Courses Expenses:
This graph shows the states with the highest course expenses for various categories such as AI, Data Science, and others.

Summary : 
<br>Overall, these platforms have their own advantages depending on user needs, such as category variety, course duration, <br>price, or completion rate. Udemy and edX seem to be the superior choices for accessibility, while LinkedIn Learning and <br>Coursera shine in terms of course duration and depth.

Tools Used: Microsoft Excel

### The following is the method to complete this dashboard, from raw data to visualization.

![alt text](https://github.com/amirahzubaidi/Learning-Platform-Performance-Dashboard-In-Excel/blob/main/Picture/Screenshot%202025-01-20%20073635.png?raw=true)

#### Step 1: Extract Course_Id, Course_Name, Category and Duration(Hours) data in the guide column
We use the vlookup formula to find data, look at the image below
<br>
![alt text](https://github.com/amirahzubaidi/Learning-Platform-Performance-Dashboard-In-Excel/blob/main/Picture/Screenshot%202025-01-20%20075035.png?raw=true)
<br>
![alt text](https://github.com/amirahzubaidi/Learning-Platform-Performance-Dashboard-In-Excel/blob/main/Picture/Screenshot%202025-01-20%20075145.png?raw=true)
<br>
![alt text](https://github.com/amirahzubaidi/Learning-Platform-Performance-Dashboard-In-Excel/blob/main/Picture/Screenshot%202025-01-20%20075155.png?raw=true)

#### Step 2: Fill in the data in the Course ID column with the format =EDU-(Course Name)-(Course Category)-(Duration)-(Enrolled Students)-(Platform Code1)
We create formula to fill the colomn Course ID
<br>
![alt text](https://github.com/amirahzubaidi/Learning-Platform-Performance-Dashboard-In-Excel/blob/main/Picture/Screenshot%202025-01-20%20074853.png?raw=true)

#### Step 3: Do the formatting data, cleaning data, Handling null values
![alt text](https://github.com/amirahzubaidi/Learning-Platform-Performance-Dashboard-In-Excel/blob/main/Picture/Screenshot%202025-01-20%20075215.png?raw=true)

#### Step 3: Analyze by creating a pivot table, pivot chart and the slicer in the Helper Sheet
![alt text](https://github.com/amirahzubaidi/Learning-Platform-Performance-Dashboard-In-Excel/blob/main/Picture/Screenshot%202025-01-20%20082313.png?raw=true)

#### Step 4: Here are the performance of the dashboard
![alt text](https://github.com/amirahzubaidi/Learning-Platform-Performance-Dashboard-In-Excel/blob/main/Screenshot%20Dashboard.png?raw=true)
