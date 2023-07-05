# startup-analysis
Data visualization dashboards for start-ups are becoming increasingly popular due to their ability to furnish stakeholders with real-time insights into key business metrics. As start-ups expand, they generate an abundance of data, rendering it arduous for stakeholders to apprehend the company’s performance without expending an excessive amount of time sifting through spreadsheets and reports.

Data visualization dashboards enable start-ups to collate and exhibit their data in an easy-to-understand format, facilitating the swift identification of trends, patterns, and areas for improvement. This not only conserves time but also engenders more knowledgeable decisions based on data-driven insights.

Moreover, data visualization dashboards can also facilitate start-ups in communicating their performance to investors, partners, and other stakeholders more effectively. By presenting data in an engaging and interactive way, start-ups can convey a clear and compelling narrative about their business, which can be of paramount importance during fundraising rounds or partnership negotiations.

# Brief Explanation
The provided dashboard serves as a valuable tool for angel investors seeking to maximize their profits through informed investment decisions. Moreover, this dashboard proves to be a beneficial resource for entrepreneurs, as it provides them with a clear understanding of their startup’s timeline and the necessary milestones required to secure funding successfully. The dashboard aggregates data from over 12,000 companies across various industries such as software, biometrics, and e-commerce. Additionally, it presents a visual representation of global startups, highlighting trends and features by country. This feature enables government policymakers to comprehend the underlying dynamics and formulate effective policies to strengthen their respective countries’ startup ecosystems.

# The Dataset
This dataset consists of a total of 44 columns, which gave us the overall idea of start-ups that are present there in market. We use a total of 12 columns to visualize the important information out of the dataset. Below are the attributes that are used in the dashboard:

<script src="https://gist.github.com/mrunalmania/1d6d0c4527ed8a81f7feea7a1f96f0b6#file-mrunal-dv-gist-csv"></script>

# Preprocessing
In the dashboard, we visualize the average time required for companies to achieve their first milestone, and to find this information, we used a calculated field to calculate the time difference for companies between the first funding round and the first milestone achieved.

In the dashboard we also try to answer the question “In every sector what is the average time between first and last funding round?”, and to answer this question, we calculate the field which gives us the time difference between companies’ first funding and last funding rounds.

For this calculated field we will use tableau as a preprocessing tool.

Except those simple functions like average are used directly in Tableau software.

# The Dashboard Users
The dashboard proves to be a valuable resource for angel investors, as it provides insights into essential aspects of a startup’s performance, such as the distribution of ROI based on categories, the variance in companies’ first investment rounds, and the time taken to achieve their initial milestone. These critical insights enable angel investors to make well-informed investment decisions based on calculated risk assessments.

Entrepreneurs can benefit greatly from this dashboard as it provides a realistic timeline for securing funding from investors. By leveraging the insights provided by the dashboard, entrepreneurs can gain a deeper understanding of the prevailing trends in the startup ecosystem and identify the critical features required to achieve success. For instance, the dashboard answers questions on the time to success, which is the time difference between achieving the first funding round and the initial milestone. This valuable information empowers entrepreneurs to make informed decisions based on a comprehensive analysis of the existing startup landscape.

Government policymakers can leverage this dashboard to gain insights into the prevailing startup trends and the average ROI by country. The dashboard provides valuable information on the overall startup ecosystem of each country, enabling policymakers to assess which countries have the most active startups. With this knowledge, policymakers can study the policies of the countries with the most active startups (a question answered by this dashboard) and adopt similar policies to strengthen their own country’s startup ecosystem. Thus, this dashboard proves to be a valuable resource for policymakers seeking to develop effective policies that promote startup growth and innovation.
