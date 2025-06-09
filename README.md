# Spotify Dashboard 🎵📊

## Project Overview
This project analyzes Spotify user listening patterns, providing insights into albums, artists, and tracks over time. Built with a focus on interactivity and data-driven insights, this dashboard visualizes trends, engagement patterns, and year-over-year (YoY) comparisons using Spotify's music streaming data. 🎧

## Features ✨
- **Interactive Grid View**: Displays Album Name, Artist Name, Track Name, and other key metrics with drill-down, drill-up, and hierarchy support. 📋
- **Drill-Through Functionality**: Explore detailed data and export to CSV. 📥
- **Trend Analysis**: Visualize albums, artists, and tracks played over time. 📈
- **Yearly Comparisons**: Compare Latest Year (LY) vs Previous Year (PY) with YoY growth analysis. 📅
- **Listening Patterns**: Heat maps for peak listening hours and scatter plots for track frequency vs. listening time. 🕒
- **Top 5 Rankings**: Identify the most played albums, artists, and tracks. 🏆
- **Weekday vs Weekend Patterns**: Analyze listening behavior differences. 💥

## Business Requirements 📋
The dashboard fulfills the following requirements:

### Albums 🎵
- Total albums played over time (monthly/yearly trends).
- Number of albums listened to by year (min/max identification).
- Weekday vs weekend listening patterns.
- Top 5 albums by listening frequency.
- LY vs PY trends and YoY growth analysis.

### Artists 🎤
- Total artists played over time (monthly/yearly trends).
- Number of artists listened to by year (min/max identification).
- Weekday vs weekend listening patterns.
- Top 5 artists by listening frequency.
- LY vs PY trends and YoY growth analysis.

### Tracks 🎧
- Total tracks played over time (monthly/yearly trends).
- Number of tracks listened to by year (min/max identification).
- Weekday vs weekend listening patterns.
- Top 5 tracks by listening frequency.
- LY vs PY trends and YoY growth analysis.

![Screenshot 2025-06-09 100108](https://github.com/user-attachments/assets/078a7efa-5e87-4138-a742-6c027c086b4e)

### Listening Patterns 🕒
- **Heat Map**: Visualizes peak listening times by hour and day with color intensity.
- **Scatter Plot with Quadrant Analysis**:
  - High Frequency & High Listening Time: Most engaging tracks. 🎯
  - Low Frequency & High Listening Time: Niche but impactful tracks.
  - High Frequency & Low Listening Time: Short, frequently played tracks.
  - Low Frequency & Low Listening Time: Less popular tracks.
 
  
![Screenshot 2025-06-09 100207](https://github.com/user-attachments/assets/45a9c746-d99d-4904-8c38-36410d7dd960)

### Details Grid 📊
- Interactive grid with Album Name, Artist Name, Track Name, and other attributes.
- Supports drill-through for detailed insights and CSV export.
- Hierarchical navigation (drill down/up).

![Screenshot 2025-06-09 100236](https://github.com/user-attachments/assets/c0f1ac38-385d-4c8b-ae35-4bf36f11f8b3)


## Dashboard Structure 🖼️
The dashboard, as seen in `SPOTIFY_DASHBOARD.pdf`, includes:
- **Filters**: Select Platform, Year, Shuffled, Skipped. 🎚️
- **Tabs**: Overview, Listening Patterns, Albums, Artists, Tracks.
- **Visuals**:
  - Tracks Played Over Time (13,665 tracks displayed). 📈
  - LY vs PY comparison (e.g., 1,071 tracks in both years). 📅
  - Album details (e.g., "Awaken, My Love!", "Heroes", "Let's Rock"). 🎵
  - Metrics: Number of Albums, Tracks, Milliseconds Played, Avg Listening Time.

## Installation 🛠️
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/spotify-dashboard.git
   ```
2. Install dependencies (e.g., for Python-based processing):
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Set up your data processing environment (e.g., Power BI, Tableau, or Python-based tools).
4. Load the Spotify dataset (see [Data Sources](#data-sources)).

## Usage 🚀
1. Import the Spotify dataset into your data processing tool.
2. Connect to the data source and clean the data as per [Project Steps](#project-steps).
3. Use the dashboard to:
   - Filter by platform, year, or listening behavior (shuffled/skipped).
   - Explore trends via charts and heat maps.
   - Drill into specific albums, artists, or tracks for detailed insights.
   - Export detailed data to CSV for further analysis.

## Data Sources 📂
- **Spotify Albums Data**: Contains listening history with fields like Album Name, Artist Name, Track Name, Milliseconds Played, and Avg Listening Time.
- **Sample Data**: Includes 13,665 tracks, with metrics for albums, artists, and tracks over time.

## Technologies Used 🛠️
- **Data Processing**: Pandas, NumPy (Python).
- **Visualization**: Power BI/Tableau (assumed based on dashboard structure).
- **Charting Libraries**: Matplotlib, Seaborn (for Python-based visuals).
- **DAX Calculations**: For metrics like YoY growth and listening time averages.
- **Export Functionality**: CSV export for detailed grid data.

## Project Steps 🛤️
1. **Requirement Gathering**: Defined business needs for albums, artists, tracks, and listening patterns. 📝
2. **Data Walkthrough**: Reviewed Spotify dataset for structure and quality. 🔍
3. **Data Connection**: Linked dataset to the analysis tool. 🔗
4. **Data Cleaning/Quality Check**: Ensured data accuracy and consistency. 🧹
5. **Data Modeling**: Structured data for efficient querying and visualization. 🗄️
6. **Data Processing**: Aggregated data for metrics like total tracks and listening time. ⚙️
7. **DAX Calculations**: Computed YoY growth, averages, and rankings. 🧮
8. **Dashboard Layouting**: Designed intuitive layout with filters and tabs. 🎨
9. **Charts Development**: Created heat maps, scatter plots, and trend charts. 📊
10. **Dashboard/Report Development**: Built interactive dashboard with drill-through. 🖥️
11. **Insights Generation**: Derived actionable insights from trends and patterns. 💡

## Insights Generated 🔍
- **Listening Trends**: 13,665 tracks played, with consistent engagement (1,071 tracks in LY and PY). 📈
- **Top Albums**: Includes "Awaken, My Love!", "Heroes", "Let's Rock". 🏆
- **Listening Patterns**: Peak listening times identified via heat maps; quadrant analysis highlights track engagement categories. 🕒
- **YoY Analysis**: Stable listening volume between LY and PY, with potential growth in specific albums/artists. 📅
- **Weekday vs Weekend**: Patterns reveal differences in listening behavior, aiding targeted recommendations. 💥

## Contributing 🤝
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/new-feature`).
3. Commit changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a pull request.

## Made with ❤ by [Karan Saxena](https://www.linkedin.com/in/karan1saxena/)
