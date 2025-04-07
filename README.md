# Google Play Store App Analysis 📱

## Overview
This project analyzes over 10,000 Android apps to gain insights into the app market, covering pricing, ratings, downloads, and user sentiment to help inform product growth and monetization strategies.

## Dataset
- Kaggle: [Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

## Folder Structure
```
GooglePlayStore/
├── data/               # Raw datasets (CSV)
├── notebooks/          # Jupyter analysis
├── README.md           # Project overview
├── requirements.txt    # Python packages
```

## Setup
1. Clone this repo:
   ```bash
   git clone https://github.com/DisariB/GooglePlayStore.git
   cd GooglePlayStore
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch notebook:
   ```bash
   cd notebooks
   jupyter notebook 01_analysis.ipynb
   ```

## Key Insights
- Free apps dominate the store, but paid apps tend to have higher ratings.
- Education and Health apps have higher average ratings.
- App size and price both influence user experience and downloads.
- Sentiment analysis shows free apps receive more polarizing feedback.

## License
MIT