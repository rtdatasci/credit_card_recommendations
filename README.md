# Credit Card Recommendation Based on Travel and Demographics

This project predicts the next credit card a user is likely to apply for, based on their demographic information, spending habits, and travel preferences. The goal is to recommend a card that aligns with their lifestyle, particularly focusing on travel rewards and cashback benefits.

## Project Structure
- **data**: Contains raw and processed datasets. Raw data from Kaggle ("sakshigoyal7/credit-card-customers")
- **notebooks**: Jupyter notebooks for data exploration and experimentation.
- **src**: Core scripts for data processing, model training, and evaluation.
- **models**: Saved models.
- **results**: Evaluation metrics and visualizations.
- **tests**: Unit tests to ensure code reliability.

## Features
The model uses features such as:
- **Demographics**: Age, income level, etc.
- **Travel Preferences**: Preferred airline, travel frequency.
- **Spending Habits**: Monthly spend on travel, dining, and entertainment.
- **Current Credit Card Type**: Indicates reward preferences (e.g., cashback, travel rewards).

## Getting Started

1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
