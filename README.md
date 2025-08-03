
🎧 Spotify Listening History Analysis
This project performs a comprehensive Exploratory Data Analysis (EDA) on personal Spotify listening history using Python. It uses advanced visualization techniques to derive insights from streaming behavior over time.

📊 Project Overview
## Key Features & Analysis

-   **Top Artists and Tracks:** Identifies the most-listened-to artists and tracks by total play count and total listening time.
-   **Temporal Patterns:** Visualizes listening activity based on the hour of the day, day of the week, and monthly/yearly trends.
-   **Platform Usage:** Analyzes which devices and platforms (e.g., iPhone, web player) are most frequently used for listening.
-   **Skipping Behavior:** Examines the rate and reasons for skipping songs, including the impact of shuffle mode.
-   **Playback Reasons:** Investigates the reasons behind songs starting, such as manual clicks versus automatic playback.

🛠️ Technologies Used
## Technologies Used

-   **Python:** The core programming language.
-   **Pandas:** For data manipulation and analysis.
-   **Matplotlib:** For data visualization.
-   **Seaborn:** For creating aesthetically pleasing statistical graphics.
-   **SQLite3:** Used to load and query the cleaned data.

📁 Notebook Contents

The notebook includes:

📅 Date & Time Analysis
🎶 Top Artists and Songs
⏱️ Streaming Duration Distributions
🕓 Hourly and Weekly Trends
🌿 Custom Seaborn Green Palette Visuals

📂 Dataset
The dataset used is the Spotify Streaming History, downloaded from Spotify's data request portal. The data is assumed to include columns such as:

endTime
artistName
trackName
msPlayed

