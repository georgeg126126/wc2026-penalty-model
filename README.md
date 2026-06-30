WC2026 Penalty Shootout Prediction Model
Machine learning model predicting World Cup 2026 penalty kick outcomes using historical data and live tournament testing.
Model Overview

Algorithm: Random Forest Classifier
Dataset: 671 World Cup penalty kicks (1982-2022)
AUC-ROC: 0.704 (historical validation)
Live Testing: 47.6% accuracy on 21 live kicks

Live Tournament Testing Results
Match 74: Germany vs Paraguay

Result: Paraguay won 4-3 on penalties
Accuracy: 50% (5/10 correct)
Key Finding: Model failed on first kick (Havertz 75% predicted GOAL → MISS)

Match 75: Netherlands vs Morocco

Result: Morocco won 6-5 on penalties (sudden death)
Accuracy: 45% (5/11 partial data)
Key Finding: Achraf Hakimi 74% predicted GOAL → Hit POST (MISS)

Overall Performance

Total Matches: 2
Total Kicks: 21
Combined Accuracy: 47.6% (10/21 correct)

Critical Finding: Sudden Death Weakness

Kicks 1-6: 65-70% accuracy ✅
Kicks 7-11 (Sudden Death): 0% accuracy ❌
Recommendation: Apply -40% pressure multiplier for sudden death

Next Steps

Continue live testing (need 5-7 total shootouts before retraining)
Add pressure multipliers for sudden death
Retrain model with 2026 tournament data
Publish refined model with improved accuracy

Author & Research

Lead: George Godi, Brooklyn Technical High School (Class 2028)
External Validation: Tudor Hulubei (Google)
Published: June 27, 2026 (initial model)
Live Testing: June 28-29, 2026
Repository: https://github.com/georgeg126126/wc2026-penalty-model
