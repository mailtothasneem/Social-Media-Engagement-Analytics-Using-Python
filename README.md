# Social-Media-Engagement-Analytics-Using-Python
Social media platforms generate enormous volumes of engagement data every day — including likes, comments, shares, impressions, watch time, and follower counts. This data provides valuable insights into how users interact with content, what trends emerge across different demographics, and how engagement varies by post type or category.

## Overview

Social media engagement data can help reveal which types of content attract interactions and how audience behavior varies. This project uses Pandas and NumPy to clean and analyze post data, then uses visualizations to explore patterns.

The project includes:

- Data cleaning and preparation
- Handling missing values and standardizing categories
- Feature creation, including hashtag counts and engagement metrics
- Statistical summaries and group-by analysis
- Exploratory data analysis and visualizations
- A notebook summarizing findings

## Project Files

```text
.
├── README.md
├── Social Media Engagement Analytics Using Python.ipynb
├── Insights of social media.ipynb
└── social_media_engagement_5000.csv
```

The CSV is listed because the analysis notebook refers to it. Include it in your repository if you have permission to share it. If it is not included, update the notebook’s data-loading path or add instructions for obtaining the dataset.

## Dataset Description

The dataset is described in the analysis notebook as containing 5,000 social media post records, with fields including:

| Field group | Example columns |
|---|---|
| User demographics | `user_id`, `age`, `gender`, `country` |
| Account information | `follower_count`, `is_verified` |
| Post information | `post_id`, `post_type`, `post_category`, `hashtags` |
| Engagement metrics | `likes`, `comments`, `shares`, `impression_count`, `watch_time_sec` |
| Other attributes | Posting date/time, `device_type`, `sentiment` |

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Installation and Usage

### 1. Clone the repository

```bash
git clone https://github.com/mailtothasneem>/<https://github.com/mailtothasneem/Social-Media-Engagement-Analytics-Using-Python>.git

```

Replace `<https://github.com/mailtothasneem>` and `<https://github.com/mailtothasneem/Social-Media-Engagement-Analytics-Using-Python>` with your GitHub details.

### 2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Place the dataset

Place `social_media_engagement_5000.csv` in the repository folder, or change the CSV path in the notebook to match where you saved it.

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Social Media Engagement Analytics Using Python.ipynb` and run its cells. Then open `Insights of social media.ipynb` to review the written findings.

## Analysis Questions

The notebooks explore questions such as:

1. Which post types have the highest engagement?
2. Which content category performs best?
3. Which countries have the highest average engagement?
4. How does age relate to engagement?
5. Do verified accounts perform differently from non-verified accounts?
6. Which post types have the highest watch time?
7. How does device type relate to watch time?
8. Which sentiment category has the highest average engagement?

## Key Findings

The findings below are reported in `Insights of social media.ipynb`:

- **Post type:** Image posts had the highest reported average engagement metric, at **12,315.23**.
- **Content category:** Tech was identified as the best-performing category by average likes, at approximately **9,958.82**.
- **Country:** France had the highest reported average engagement metric among the countries shown, at approximately **12,567.70**.
- **Age:** Engagement varied by age, with no consistent increasing or decreasing pattern.
- **Verification status:** Non-verified accounts had a higher reported average engagement metric (**12,256.35**) than verified accounts (**12,019.99**).
- **Watch time by post type:** Reels had the highest average watch time, at approximately **4,135.73 seconds**.
- **Watch time by device:** Mobile users had the highest average watch time, at approximately **4,087.83 seconds**.
- **Sentiment:** Negative sentiment had the highest reported average engagement metric (**12,352.98**), followed by positive (**12,246.21**) and neutral (**12,090.27**).

The notebook reports the engagement values above. Confirm the metric’s formula and units in the analysis notebook before interpreting these values as percentages or standard engagement rates.

## Notes

- The dataset and file path must be available for the analysis notebook to run.
- Results describe the dataset used in this project and may not generalize to other platforms or audiences.
- The insights notebook’s description of the “best time of day” question reports watch time by post type. Check the analysis if you intend to make a claim about posting time.

## Future Improvements

- Clarify and document the engagement metric formula and units.
- Add exported charts or screenshots of key visualizations.
- Analyze posting time if the dataset includes a usable time-of-day field.
- Compare results across more audience groups and datasets.


Author
L.Thasneem
AI Driven Data Analytics
- GitHub:https://github.com/mailtothasneem
