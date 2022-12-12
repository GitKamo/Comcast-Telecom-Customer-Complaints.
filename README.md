# Real-industry-projects - [Comcast Telecommunications].

Problem Statement.
Comcast is an American global telecommunication company. The firm has been providing terrible customer service. They continue to fall short despite repeated promises to improve. Only last month (October 2016) the authority fined them a $2.3 million, after receiving over 1000 consumer complaints.
The existing database will serve as a repository of public customer complaints filed against Comcast.
It will help to pin down what is wrong with Comcast's customer service.

Data Dictionary

Ticket #: Ticket number assigned to each complaint
Customer Complaint: Description of complaint
Date: Date of complaint
Time: Time of complaint
Received Via: Mode of communication of the complaint
City: Customer city
State: Customer state
Zipcode: Customer zip
Status: Status of complaint
Filing on behalf of someone
Analysis Task

In this project, I had to perform the tasks below, I used different Python libraries such as NumPy, SciPy, Pandas, scikit-learn, matplotlib, and BeautifulSoup.

- I imported data into the Python environment.
- I provided the trend chart for the number of complaints at monthly and daily granularity levels.
- I provided a table with the frequency of complaint types.

I was required to identify which complaint types are maximum i.e., around internet, network issues, or across any other domains.
- I created a new categorical variable with value as Open and Closed. I categorized Open & Pending categorized as [Open] and Closed & Solved as [Closed].
- I provided state wise status of complaints in a stacked bar chart and used the categorized variable from Q3 - third quarter. The insights I provided were on:

States which had the maximum complaints
States which had the highest percentage of unresolved complaints
- I had to provide the percentage of complaints resolved till date, which were received through the Internet and customer care calls.
