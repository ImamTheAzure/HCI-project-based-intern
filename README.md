Problem & Objective
Business goal: Reduce losses by predicting loan default (binary classification).
KPIs: ROC-AUC, Precision@K, Recall (capture rate of defaulters), Expected loss reduction.
Scope: Proof-of-concept model using application data; provide actionable business recommendations.

Dataset Overview
Files used: application_train (307,511 rows), application_test (48,744 rows).
Main table: application_train with TARGET (0 = repay, 1 = default).
Additional tables available: bureau, installments_payments, credit_card_balance, previous_application.

Model Performance (Key Results)
OOF ROC-AUC: 0.737
Top 1% -> Precision: 0.399, Recall: 0.049
Top 5% -> Precision: 0.294, Recall: 0.182
Top 10% -> Precision: 0.247, Recall: 0.306
Best threshold (F1): 0.13 -> Precision: 0.210, Recall: 0.442
