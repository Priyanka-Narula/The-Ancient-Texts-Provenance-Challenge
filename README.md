# The-Ancient-Texts-Provenance-Challenge:Provenance Prediction
📜Determine the origin of historical inscriptions using only their text.
🏛️ This competition challenges you to step into the world of computational history and determine the geographical origin of ancient inscriptions based solely on their textual content.
The task is to build and fine-tune a deep learning model that can classify these historical artifacts into one of several anonymized geographical regions. This isn't just about text classification—it's about finding subtle patterns, dialects, and stylistic differences hidden within the language of the past.

# The Goal:
Predict the correct origin label for each inscription in the test set.The Data: You will work with a large collection of cleaned, anonymized inscription texts.
# 🚀📊 Evaluation: 
The model’s performance will be evaluated based on the Macro F1-Score.
# Metric: Macro F1-ScoreRange: 0.0 to 1.0 (Higher is better)
Equal Weight: The score assigns equal importance to the performance on all origin classes, ensuring the model performs well across the board.
Class Imbalance: The Macro F1 metric accounts for and mitigates issues related to potential class imbalance in the dataset.
Final Score = Macro F1-Score
Macro F1 = (1/6) × Σ(F1_score_per_emotion_class)

