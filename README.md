## About This Project

**Predicting Spotify: A Data Story about Quantifying Taste in Music**  


We set out to understand what makes a song successful on Spotify by marrying rich audio-feature data with artist metrics and temporal context. Our workflow is split into two phases:

1. **Exploratory Data Analysis**  
   - Cleaned and merged a 32,833-track Spotify dataset with artist popularity and follower data.  
   - Explored how audio features (e.g., danceability, loudness, tempo) correlate with Spotify’s “track popularity” score.  
   - Uncovered dynamic genre trends over decades, including a surprising decline in rock and a “retro-sentiment” boost for pre-1980s classics.

2. **Predictive Modeling**  
   - Built an XGBoost regressor (tuned via 5-fold CV) to predict track popularity (0–100).  
   - Achieved an RMSE of ~20 and R² ≈ 0.28 on the test set, demonstrating moderate predictive power.  
   - Used SHAP to interpret model drivers, confirming artist fame and key audio features as top influencers.

**Key Findings & Recommendations**  
- High popularity aligns with moderate-to-fast tempos (≈105 bpm or >150 bpm), danceability, loudness, and shorter durations (150–210 s).  
- Nostalgia (“retro sentiment”) and recency bias both elevate track performance.  
- For content creators: focus on audio features that align with popular trends and leverage artist branding.  
- For Spotify: consider dynamic curation strategies that balance emerging hits with classic favorites.

🔗 Dive into the notebooks and visualizations to see the full data story and model insights!
