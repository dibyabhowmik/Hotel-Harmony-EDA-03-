Project Overview:
This project analyzes hotel booking data to understand booking behaviour, cancellations, guest preferences, hotel performance, and revenue patterns. The goal is to provide data-driven insights that can help improve hotel operations, customer experience, and revenue management.

Objectives:
Analyze hotel booking and cancellation patterns.
Understand customer booking behaviour and stay duration.
Identify important booking channels and market segments.
Analyze ADR and revenue patterns.
Study factors related to booking cancellations.
Understand guest preferences through special requests and other booking details.
Tools Used
Python
Pandas & NumPy
Matplotlib & Seaborn
Statsmodels
Kaggle Code
Kaggle Hotel Booking Dataset
Process

The dataset was first checked for missing values, duplicate records, incorrect data types, and unusual values. Duplicate bookings were removed, missing categorical values were handled, and date fields were converted into proper datetime format.

New features such as total nights, total guests, and lodging revenue were created to support the analysis. The data was then analyzed using descriptive statistics, grouping, correlation analysis, visualizations, and regression techniques.

Cancellation patterns were studied across hotel types, lead time, market segments, and arrival months. Revenue analysis was based on ADR and stay duration, with cancelled bookings excluded when looking at realized lodging revenue.

Key Insights:
City Hotels receive more bookings than Resort Hotels.
The average booking lead time is around 80 days.
August is one of the busiest arrival months.
Guests stay for around 3–4 nights on average.
TA/TO is the most common distribution channel.
Portugal has the highest number of bookings by country in the dataset.
Longer booking lead times are associated with higher cancellation levels.
ADR varies across hotel types and market segments.
Guest special requests are relatively low, averaging around 0.70 per booking.
The analysis shows that understanding booking behaviour and cancellations can help hotels improve room planning, marketing, pricing, and resource allocation.
