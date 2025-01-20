## Learning Platform Performance Dashboard In Excel

### Introduction: 
In the digital age, online learning platforms have become a preferred choice for millions to develop their skills and gain knowledge anytime, anywhere. But with so many options, how can we choose the best? This performance dashboard sheds light on key metrics such as ratings, completion rates, pricing, and user engagement for four top platforms: Udemy, LinkedIn Learning, Coursera, and edX.

![alt text](https://github.com/amirahzubaidi/Learning-Platform-Performance-Dashboard-In-Excel/blob/main/Screenshot%20Dashboard.png?raw=true)

### Below is a guide for creating the dashboard:

![alt text](https://github.com/amirahzubaidi/Learning-Platform-Performance-Dashboard-In-Excel/blob/main/Picture/Screenshot%202025-01-20%20073635.png?raw=true)

### The Main data to create the Dashboard
![alt text](?raw=true)

#### Step 1: Extract Course_Id, Course_Name, Category and Duration(Hours) data in the guide column
We use the vlookup formula to find data, look at the image below

![alt text](https://github.com/amirahzubaidi/Learning-Platform-Performance-Dashboard-In-Excel/blob/main/Picture/Screenshot%202025-01-20%20075035.png?raw=true)

![alt text](https://github.com/amirahzubaidi/Learning-Platform-Performance-Dashboard-In-Excel/blob/main/Picture/Screenshot%202025-01-20%20075145.png?raw=true)

![alt text](https://github.com/amirahzubaidi/Learning-Platform-Performance-Dashboard-In-Excel/blob/main/Picture/Screenshot%202025-01-20%20075155.png?raw=true)

#### Step 2: Fill in the data in the Course ID column with the format =EDU-(Course Name)-(Course Category)-(Duration)-(Enrolled Students)-(Platform Code1)
We create formula to fill the colomn Course ID
![alt text](https://github.com/amirahzubaidi/Learning-Platform-Performance-Dashboard-In-Excel/blob/main/Picture/Screenshot%202025-01-20%20074853.png?raw=true)

#### Step 3: Do the formatting data, cleaning data, Handling null values
![alt text](https://github.com/amirahzubaidi/Learning-Platform-Performance-Dashboard-In-Excel/blob/main/Picture/Screenshot%202025-01-20%20075215.png?raw=true)

#### Step 3: Analyze by creating a pivot table
