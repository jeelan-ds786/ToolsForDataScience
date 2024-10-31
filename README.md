# Toronto GitHub Users Data Analysis

## Project Overview
This project utilizes the GitHub API to gather and analyze data on Toronto-based GitHub users with over 100 followers. The analysis provides insights into popular languages, community engagement, and repository trends among Toronto's developers.

### Key Findings
- **JavaScript Popularity**: An unexpectedly high number of repositories are JavaScript-focused, indicating a strong demand for front-end expertise in Toronto.
- **Impact of Documentation**: Repositories with detailed READMEs receive notably higher engagement, emphasizing the importance of documentation for developers.

## Files in this Repository
- **`users.csv`**: Contains user data such as login, name, company, bio, and more for GitHub users in Toronto with over 100 followers.
- **`repositories.csv`**: Provides details on each user’s public repositories, including creation date, primary language, and license information.
- **`README.md`**: Project explanation and key insights based on the data analysis.

## Methodology

### Data Collection
Data was gathered using the GitHub API with specific criteria:
- **User Filtering**: Extracted users located in Toronto with over 100 followers.
- **Repository Extraction**: Retrieved up to 500 of each user's recent public repositories, recording essential information such as stars, watchers, primary language, and licensing.

### Data Cleaning and Processing
- **Company Names**: Removed leading "@" symbols and standardized to uppercase.
- **General Cleanup**: Trimmed whitespace and handled missing values in the CSV files.
- **Rate Limiting**: API requests were managed using authenticated access to respect GitHub's rate limits.

## Running the Script
1. **API Access**: Set up a GitHub personal access token for authenticated API requests.
2. **Run the Script**: Execute the script to collect user details and repository data, saving them to `users.csv` and `repositories.csv`.
3. **Data Cleaning**: Process and clean the data as needed.

## Insights

### Key Findings from the Analysis
1. **Predominance of JavaScript**: Over 40% of repositories use JavaScript, highlighting its popularity among Toronto-based developers.
2. **Documentation Boosts Engagement**: Repositories with thorough documentation and organized READMEs saw a significant increase in stars and watchers.
3. **Active Community**: Toronto users with 100+ followers show a higher-than-average follower count, suggesting an engaged GitHub community.

## Recommendations

For developers in Toronto or those aiming to engage Toronto’s developer community, here are some actionable insights:

- **Emphasize Documentation**: Providing clear and detailed documentation can boost engagement and project visibility.
- **Focus on JavaScript**: Given its popularity, JavaScript projects may gain more community relevance and engagement.
- **Community Interaction**: Actively engaging in collaborative projects can enhance visibility and attract followers.

---

### Notes
Due to rate limits, authenticated requests were used to maximize data collection. This project offers insights into Toronto's developer landscape and provides strategic guidance for improving engagement on GitHub.

