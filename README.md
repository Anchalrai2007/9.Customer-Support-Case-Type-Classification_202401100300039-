# 9.Customer-Support-Case-Type-Classification_202401100300039-
This project aims to enhance customer support efficiency by automatically classifying support tickets into billing, technical, or general queries. Automating this process reduces response time, improves accuracy, and streamlines case routing, especially for email-based support in e-commerce.

# Model Performance
The model was evaluated using a test set of 20 support tickets. Below are the key performance statistics and detailed classification metrics:

# Overall Statistics
Metric	Value
Accuracy	0.35
Precision	0.50
Recall	0.35
F1-Score	0.35

Accuracy represents how many predictions were correct out of all predictions.
Precision measures how many predicted cases were relevant.
Recall tells us how many actual relevant cases were identified.
F1-Score is the harmonic mean of precision and recall.

### Classification Report (Per Class)

| Class        | Precision | Recall | F1-Score | Support |
|--------------|-----------|--------|----------|---------|
| Billing      | 0.67      | 0.18   | 0.29     | 11      |
| General      | 0.27      | 0.60   | 0.38     | 5       |
| Technical    | 0.33      | 0.50   | 0.40     | 4       |
| **Macro Avg**     | **0.42**      | **0.43**   | **0.35**     | **20**      |
| **Weighted Avg**  | **0.50**      | **0.35**   | **0.33**     | **20**      |


# Interpretation
Billing queries have high precision (0.67) but very low recall (0.18), meaning the model correctly identifies some billing tickets but misses many others.
General and Technical categories are identified with better balance between precision and recall, though overall scores remain moderate.
The model needs more data and possibly a different algorithm to improve overall accuracy and generalization.

# Improvements & Future Work
🔄 Collect more labeled data for better model training

⚖️ Balance class distribution to improve fairness across categories

🧪 Experiment with advanced models (e.g., Logistic Regression, Random Forest, BERT)

🧹 Enhance text cleaning (lemmatization, bigrams, etc.)

🌐 Extend support to live chat and social media messages
