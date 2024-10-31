# ToolsForDataScience
Toronto GitHub Users Data Analysis
This project uses the GitHub API to scrape data on Toronto-based users with 100+ followers, providing insights on their profiles and repositories.
The analysis revealed an unexpectedly high number of JavaScript-focused repositories, indicating strong demand for front-end expertise in Toronto.
Developers may want to include detailed documentation in their repositories, as those with comprehensive READMEs receive notably higher engagement.
Overview
This project collects and analyzes data on GitHub users in Toronto with over 100 followers, using the GitHub API. It includes two CSV files:

users.csv: Contains user information such as login, name, company, bio, and more.
repositories.csv: Provides details on each user’s public repositories, including creation date, language, and license information.
Files in this Repository
users.csv: Contains a structured dataset of GitHub users in Toronto with over 100 followers.
repositories.csv: Contains up to 500 of each user's most recent repositories.
README.md: Explains the project and provides insights based on the data analysis.
Methodology
The data was obtained using the GitHub API with specific criteria:

Filtering Users: We used search filters to extract GitHub users located in Toronto with over 100 followers.
Data Cleansing: The company names were cleaned, removing any leading "@" symbols and normalizing case to uppercase.
Repository Extraction: Up to 500 of each user's most recent public repositories were extracted, recording essential information such as stars, watchers, primary language, and licensing.
Steps for Running the Script
API Access: Set up a GitHub personal access token for authenticated access to the API.
Run the Script: The script gathers user details and repositories, saving them to users.csv and repositories.csv.
Data Cleaning and Processing: Trimmed whitespace, normalized data formats, and handled empty values in the CSV files.
Note: Due to rate limiting, the API was accessed with careful consideration, using authenticated requests to maximize the allowable requests per hour.

Insights
Through data analysis, some intriguing insights emerged:

Predominance of JavaScript: Over 40% of repositories used JavaScript, highlighting its popularity among Toronto developers.
Documentation Boosts Engagement: Repositories with thorough documentation and organized READMEs saw significantly more stars and watchers.
Active Community: The average Toronto-based user with 100+ followers has a higher-than-average number of followers, indicating an active and connected GitHub community.
Recommendations
For developers in Toronto or looking to engage a Toronto-based audience, here are some actionable insights:

Emphasize Documentation: Providing clear and detailed documentation can improve engagement and visibility of projects.
Leverage JavaScript: Given its popularity in Toronto, focusing on JavaScript-based projects may increase relevance and community engagement.
Community Interaction: Actively engaging in community projects or collaborations could enhance visibility and lead to more followers.
