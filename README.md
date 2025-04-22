# 9.Customer-Support-Case-Type-Classification_202401100300039-
This project aims to enhance customer support efficiency by automatically classifying support tickets into billing, technical, or general queries. Automating this process reduces response time, improves accuracy, and streamlines case routing, especially for email-based support in e-commerce.
📈 Model Performance
The model was tested on a sample of 20 support tickets.

🔢 Metrics
Accuracy: 0.35
Precision: 0.50
Recall: 0.35
F1-Score (macro avg): 0.35

📊 Classification Report
Category	Precision	Recall	F1-Score	Support
Billing	0.67	0.18	0.29	11
General	0.27	0.60	0.38	5
Technical	0.33	0.50	0.40	4

📌 Result Interpretation
The model shows high precision for billing queries but misses many of them (low recall), suggesting it only labels something as billing when very confident.
It performs reasonably on general and technical queries but would benefit from a larger and more balanced dataset.
Overall, the current accuracy of 35% indicates room for improvement, particularly in terms of recall and class balance.

🛠 Improvements & Future Work
🔄 Collect more labeled data for better model training
⚖️ Balance class distribution to improve fairness across categories
🧪 Experiment with advanced models (e.g., Logistic Regression, Random Forest, BERT)
🧹 Enhance text cleaning (lemmatization, bigrams, etc.)
🌐 Extend support to live chat and social media messages

