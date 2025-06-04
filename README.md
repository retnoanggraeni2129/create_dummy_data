# create_dummy_data
Analisis Data Dummy untuk Digital User Profiling

# Purpose
Demonstrate the creation of dummy data, variable development, and descriptive statistical analysis with confidence interval.

# Dummy Data Creation
1. Dummy data generation is done using pandas, faker and random.
2. Data dimension is 100 rows 9 columns
3. Basic Variable:
  - Nama Lokasi (Location)
  - Jam Login (Login Time)
  - Nama (Name)
  - Email
  - Nomor Telepon (Phone Number)
  - Tahun Lahir (Year of Birth)
  - Merk HP (Phone Brand)
  - Minat Digital (Digital Interest)
  - Tipe Lokasi (Location Type)

# Development of New Variables
- Age (2025 - Year of Birth)
- Mobile Segment
  - High-end: iPhone
  - Mid-end: Samsung, Oppo, Xiaomi, Vivo, Realme Login
- Period
  - Morning: 05.00-11.59
  - Afternoon: 12.00-15.59
  - Evening: 16.00-20.00
- Interest 
  - Low: 0–59
  - Medium: 60–79
  - High: 80–100
 
# Descriptive statistics
- The results of the descriptive statistics show that this data has a range of values from 1 to 100, with an average of about 51-52. This data is quite varied, with a standard deviation of about 6.3.
- Digital Interest: The average is around 51.4, with a minimum value of 1 and a maximum of 100, indicating a large variation in digital interest among respondents.
- Age: The average is about 28.87 years, with a range from 18 to 40 years, indicating most respondents are young adults.
- Login Hours: Averaged around 1900-01-01 12:28:12, with time variations from 00:05:50 to 23:50:00. This data shows that logins are made throughout the day, with a fairly even distribution.

# confidence Interval
- A confidence interval is a range or line that we draw from sample data, to guess the true value of a large group.
- With a 95% confidence level, it means that we are 95 out of 100 times sure that the range will fit the true value.
- So, it's a way of estimating something approximately, but still believing and being confident.
- The results of the confidence interval calculation are 27.60 and 30.12. This means there is a 95% chance that the true value is between 27.60 and 30.12.

# Insight
- Distribution of Customers by Age Range: Most users are between 20-25 years old, peaking at 24 years old with 8 users. 
  - The number of users decreases gradually after the age of 25, with a peak at 20-25 years old and a steep decline thereafter. 
  - Those above 40 years of age have a very small number of users at 1 person. 
- Percentage of HP Brands by HP Segment:
  - High-end segment dominated by iPhone with 20%,
  - Mid-range segment dominated by Samsung (16%).
- Where Users Access the Internet:
  - Cafes and Libraries are the most used locations to access the internet, with 19 and 18 users respectively.
  - Other locations such as Malls, Stations, Offices, and Campuses have relatively fewer users.
- Users per Mobile Phone Brand:
  - The most used brand is Phone (20 users), followed by Oppo (16 users).
- Number of Users per Interest Category:
  - The Low category dominates with 60 users, while High and Medium have 25 and 15 users respectively.
- Number of Internet Users in Each City:
  - Surabaya has the most internet users (24), followed by Bandung (18), and other cities that have fewer users.
- Number of Users per Log In Period:
  - Peak usage occurs in the afternoon (53 users).
  - Usage is quite high in the morning (34 users), and less in the afternoon (13 users).
 
# Recommendations
1. Main Purpose of the Application: Understand user characteristics in real-time. Customize services and promotions based on user segmentation. Increase user engagement and retention through data-driven decisions.
2. Main Features of the Application:
  - User Demographics & Segmentations: Display demographic data such as age, location, and interests. Personalize content and promotions based on segmentation (e.g., promotions for young age, specific city users).
  - Real-Time Analytics Dashboard: Shows peak visit times (e.g., afternoon) and top locations. Send automatic notifications when user uptime is high (afternoon)
  - Location-Based Promotion: Send special promotions at certain popular locations (e.g. cafes or libraries). Enable geofencing to increase engagement in targeted areas.
  - Device & Brand Targeting: Develop promotions and content for users based on HP brands and high-end or mid-range segments. Optimize the experience of users using specific brands.
  - Interest & Category Personalization: Understand users' key interest categories and offer content accordingly (e.g., special offers for Low interest categories).
  - User Engagement Timing Optimization: Send notifications, promos, or communications during peak hours (evening) to increase traffic and conversions.
3. Technology and Implementation:
   - Backend: Using data analytics and machine learning for automated segmentation.
   - Frontend: Web/mobile based interactive dashboard using React, Flutter, or similar platforms.
   - Data Storage: Cloud-based database (like, Firebase, AWS).
   - Push Notifications: For promotions and user uptime reminders.
4. Development Steps:
   - Data Collection Integration of data from various sources and real-time updates.
   - Data Processing and Analysis Use BI (Business Intelligence) tools to generate automated insights.
   - UI/UX Design Create an attractive and easy-to-use dashboard.
   - Build MVP Start from basic features such as analytics and notifications.
   - Test and Iterate Internal and external user feedback, make continuous improvements.
     
# Summary:
- The majority of users are young, around 20-25 years old, with market segmentation dominant in the high-end segment and low-interest category. 
- Users mostly access the internet in public places such as cafes and libraries. 
- Surabaya and Bandung are the cities with the most internet users. 
- Peak user activity occurs in the afternoon, signaling the main time of use of the service. 
- The suggested application will utilize user data to provide a personalized and relevant experience through location, uptime, and interest analysis, thereby increasing engagement, targeted promotions, and real-time data-driven decision-making.


# Contact Me:
LinkedIn: https://www.linkedin.com/in/retnoanggraeni/
Email: retnoagraeni@gmail.com
Dashboard Interactive: https://public.tableau.com/app/profile/retno.anggraeni/viz/datadummy_17489618237160/Dashboard1
