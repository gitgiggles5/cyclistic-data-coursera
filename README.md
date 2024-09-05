
# Introduction

In the Coursera Data Analytics case study, I engaged in a comprehensive
range of hands-on activities typically entrusted to a Junior Data
Analyst. This case study simulates my role as a Junior Data Analyst at
Cyclistic, a fictitious bike-share company in Chicago. My
responsibilities included analyzing the distinct usage trends of casual
riders versus annual members, with the objective of developing a
marketing strategy to enhance the conversion of casual riders into
loyal, annual members.

The strategy's success hinges on executive approval, which requires
solid data insights and professional visualizations to support my
recommendations for converting casual riders into annual members. I
addressed the business inquiries by adhering to the data analysis
process stages learned during the course: Ask, Prepare, Process,
Analyze, Share, and Act.

# Background

Cyclistic is a bike-share program featuring more than 5,800 bicycles and
600 docking stations. The program distinguishes itself by offering
reclining bikes, hand tricycles, and cargo bikes, making it inclusive
for people with disabilities and those who can't use a standard
two-wheeled bike. While the majority of riders opt for traditional
bikes, about 8% of riders use the assistive options. Cyclistic users are
more likely to ride for leisure, with approximately 30% commuting to
work daily.

# Key Personnel:

-   Lily Moreno: Director of Marketing, responsible for campaigns and
    initiatives to promote the bike-share program through various
    channels.

-   Cyclistic Marketing Analytics Team: A team of Data Analysts
    collecting, analyzing, and reporting data to guide marketing
    strategy. I joined this team six months ago.

-   Cyclistic Executive Team: A detail-oriented group that will decide
    whether to approve the recommended marketing program.

# ASK

Business Task The goal of this analysis is to understand the patterns
and trends in the usage of Divvy bikes over the year 2023. Specifically,
we aim to identify peak usage times, the popularity of different bike
types, and the behavior of various rider types (members vs. casual
riders). Insights from this analysis will help inform strategies to
optimize bike availability, improve customer satisfaction, and guide
marketing efforts.

## Key Stakeholders: 
* Divvy Bike Operations Team 
* Marketing Department
* Customer Experience Team
* Urban Planners

# PREPARE:

In the preparation phase, we meticulously gathered and cleaned Divvy
bike trip data spanning the entirety of 2023. By ensuring data integrity
and completeness, we laid the groundwork for robust analysis aimed at
uncovering actionable insights into rider trends, bike usage patterns,
and membership behaviors.

The data used for this analysis consists of Divvy bike trip data for the
year 2023, sourced from the last 12 months of monthly CSV files named in
the pattern "2023MM-divvy-tripdata.csv". These files contain detailed
records of individual bike trips, including start and end times, start
and end stations, ride-able type (bike type), and rider type (member or
casual). The data was downloaded from the Divvy Trip Data portal and has
been made available by Motivate International Inc. under a license
agreement which outlines the terms of use.

# PROCESS: Throughout the data processing phase, meticulous cleaning and
aggregation of Divvy bike trip data from 2023 were conducted to ensure
accuracy and reliability. By preparing a unified data set and applying
rigorous analysis techniques, we laid the foundation for deriving
meaningful insights into rider behavior and usage patterns.

# Data Cleaning 
Filtering: Removed entries with empty
start_station_name and trips with non-positive duration.

-   NA Removal: Dropped rows with missing values.

-   Empty Columns and Rows: Removed empty columns and rows using

-   Date/Time Conversion: Converted started_at and ended_at to datetime
    format and extracted date (Ymd), start hour (start_hour), and end
    hour (end_hour).

-   Duration Calculation: Calculated trip durations in both hours and
    minutes.

# ANALYZE:

Analyzing the data trends revealed crucial insights into rider behavior
and preferences, guiding targeted strategies to convert casual riders
into annual members effectively. By leveraging these insights, Cyclistic
aims to optimize bike availability, enhance customer satisfaction, and
drive sustainable growth in membership conversions


# SHARE:

Sharing these data-driven insights with key stakeholders, including the
Divvy Bike Operations Team, Marketing Department, Customer Experience
Team, and Urban Planners, will facilitate informed decision-making and
collaborative efforts. By aligning on actionable strategies, Cyclistic
aims to enhance operational efficiency, improve marketing initiatives,
and ultimately foster a more seamless and rewarding experience for
riders across Chicago.

# ACT

Based on the comprehensive information provided in the Cyclistic
Bike-Share Program Analysis project, here are three recommendations to
increase the number of annual members or convert casual riders into
annual members more effectively:

1.  Targeted Marketing Campaigns Based on Usage Patterns:

-   Data Insight: Utilize the insights gained from the analysis of bike
    usage patterns, such as peak usage times and popular bike types
    among casual riders.

-   Recommendation: Launch targeted marketing campaigns that highlight
    the benefits of annual membership during peak usage times or for
    specific bike types that casual riders prefer. For example,
    promotions offering discounted annual memberships or exclusive
    benefits during high-demand periods could incentivize casual riders
    to switch to annual memberships.

2.  Enhanced Customer Engagement through Personalization:

-   Data Insight: Leverage customer behavior data to personalize
    marketing efforts and engagement strategies.

-   Recommendation: Implement personalized marketing messages based on
    individual riding habits, preferences, and demographics. Use data
    analytics to tailor communications that emphasize how annual
    membership can enhance their specific riding experience or cater to
    their needs better than casual membership. For instance, sending
    personalized emails with membership benefits that align with their
    usage patterns (e.g., frequent commuters, leisure riders) can
    increase conversion rates.

3.  Improvement of User Experience and Convenience:

-   Data Insight: Focus on improving the overall user experience and
    convenience factors that influence membership decisions.

-   Recommendation: Streamline the membership registration process and
    ensure it is user-friendly and accessible across different devices.
    Provide clear and compelling information on the benefits of annual
    membership, such as cost savings, bike availability guarantees, and
    additional services (e.g., priority access during peak times,
    special events). Enhance the Cyclistic mobile app or website to
    prominently feature these benefits and simplify the upgrade process
    from casual to annual membership.

# Implementation Strategy:

-   Measurement and Evaluation: Set measurable goals for each
    recommendation, such as an increase in annual membership sign-ups or
    conversion rates from casual to annual members.

-   Continuous Optimization: Monitor the effectiveness of implemented
    strategies using data analytics. Adjust marketing tactics based on
    real-time insights and feedback from members.

-   Collaboration with Stakeholders: Engage with the Cyclistic Marketing
    Analytics Team and Executive Team to align strategies with broader
    business goals and ensure support for implementation.

By implementing these recommendations, Cyclistic can strategically
enhance its efforts to convert casual riders into loyal annual members,
thereby optimizing bike availability, improving customer satisfaction,
and fostering long-term growth for the bike-share program.
