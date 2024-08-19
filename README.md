# linkedin-profile-scraper
This scraping script uses the Selenium library to extract LinkedIn profile data from:
1. **LinkedIn event** or **Search link**
2. **LinkedIn Post**
3. **Previously scraped LinkedIn profile data (csv file)**

The script extracts the following data points for each scraped profile:
- First Name
- Last Name
- Full Name
- Profile Link
- Degree of Connection
- Bio
- Location
- Reaction Type (if from a post)
- Country
- Job Title
- Employment Duration
- Employment Span
- Professionally active (active/inactive)
- Company Name
- Company Size
- Company Link
- Education Degree
- University Attended
- Phone Number
- Email Address
- Twitter Handle
- Birthday

## Data Utilization:
1. **Marketing and Networking Purposes:**
   - Targeted Advertising: By knowing specific attributes of individuals, such as their sector, interests, or location, marketing campaigns can be more accurately tailored, reducing ad costs.
   - Audience Analysis: Analyzing profiles helps in understanding the characteristics of people in specific sectors or with similar interests.
   - Network Expansion: By identifying individuals with similar interests or backgrounds, it's easier to extend your personal network, increasing the chance of having your connection requests accepted.

2. **Machine Learning/Deep Learning Projects:**
   - Predictive Analytics: Use attributes like job title, company, and education to predict career progression trends or industry shifts.
   - Recommendation Systems: Develop systems that recommend articles, connections, or jobs based on user profiles and behavior.
   - Network Analysis: Employ algorithms to analyze social networks and understand relationship dynamics within specific industries or regions.

## Example of extracted data:
![image](https://github.com/mrfidibus7/linkedin-profile-scraper/assets/110305821/2966da85-805c-48f4-b831-5607e55d4501)

## Video tutorial
To gain a comprehensive understanding of this script and its effective usage, I highly recommend viewing the accompanying video tutorial at this link: https://we.tl/t-ysKqDKlGDM

# Motivation
My motivation for creating the LinkedIn Profile Extractor stems from recognizing the immense value hidden within LinkedIn profiles. By deeply understanding individuals, we can connect more effectively and efficiently. This tool allows for precise filtering and connection with the right people, especially when enhanced with a language model to craft personalized connection requests based on mutual interests and goals. Furthermore, the tool facilitates large-scale analysis of specific groups, leveraging LinkedIn's search filters. It also targets active users, like those engaging with posts, ensuring that we reach people genuinely interested and active in relevant topics. This is especially powerful for job searches; in today's competitive market, direct messaging through LinkedIn can be a game-changer. This tool simplifies finding potential contacts open to discussions, giving a significant edge in exploring career opportunities.

# Project objective
This project has been created as an example of data preprocessing for training machine learning algorithms. However, it goes somewhat further than that. Looking at the data, there are features that will not be used for machine learning purposes like the email, phone number, twitter handle, etc. These have been added for marketing and networking purposes.
