# NCAA March Mania 2026 🏀

A machine learning pipeline to predict NCAA March Madness tournament outcomes for the [Kaggle March Machine Learning Mania 2026](https://www.kaggle.com/competitions/march-machine-learning-mania-2026) competition.

## Approach

Predicts win probabilities for all possible men's and women's NCAA tournament matchups using a Gradient Boosting model trained on historical tournament data.

### Features engineered per team per season
- Win rate & average point differential
- Elo rating (with annual mean reversion)
- Tournament seed number
- Recent form (last 10 games)
- Historical tournament appearances

### Model
- Gradient Boosting Classifier (sklearn)
- Trained on combined men's + women's tournament history
- Evaluated using log loss (5-fold cross-validation)

## Results
- **132,133** matchup predictions generated
- Submitted to Kaggle Stage 2 — scores update as tournament games are played


