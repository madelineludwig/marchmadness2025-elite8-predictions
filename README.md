## March Madness 2025: Elite 8 Predictions

This notebook uses Python to simulate and visualize potential outcomes for the 2025 NCAA March Madness Elite 8 matchups. It includes model-driven predictions, visual breakdowns by matchup, and insights based on simulated percentages.

### 📝 Summary Analysis

This project uses a logistic regression model to predict which NCAA basketball teams would advance from the Sweet 16 to the Elite 8 in the 2025 March Madness tournament. The model was built on regular-season stats and simulated each matchup 10,000 times to estimate win probabilities.

**Key features used:** Win-Loss %, SRS, SOS, FG%, 3P%, FT%, TRB, AST, STL, BLK, and TOV.

The model achieved **75% accuracy**, correctly predicting 6 out of 8 Elite 8 teams. Successful predictions were often supported by strong offensive metrics like assists and rebounds. Narrow-margin matchups (51–53%) were still accurately forecasted, showing the model’s ability to capture subtle statistical differences.

Two incorrect predictions—Arizona vs. Duke and Purdue vs. Houston—had nearly even win probabilities and reflect the inherent unpredictability of tournament games, especially when based solely on regular-season data.

**Next steps:** Future iterations could incorporate tournament-specific metrics, historical performance, and qualitative data (e.g., coaching adaptability) to enhance accuracy in high-pressure, close-probability matchups.

🏀 **Accuracy:** 75%  
🧠 **Model:** Logistic Regression  
🔁 **Simulations:** 10,000+
