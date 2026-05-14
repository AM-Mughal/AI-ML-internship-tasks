# AI-ML-internship-tasks

This repository showcases multiple AI/ML projects focused on real-world applications such as conversational AI, mental health support, and stock price prediction.

Task 1: General Health Query Chatbot (Prompt Engineering)
Objective

Develop a chatbot that answers general health-related questions using an LLM while ensuring safe and user-friendly responses.

Dataset Used
No custom dataset
Based on pretrained knowledge from the Gemini API
Models & Techniques
Gemini (Google Generative AI API)
Prompt Engineering
Key Results & Findings
Generated clear and concise health responses
Applied safety filtering to avoid harmful medical advice
Gained practical experience in prompt design and response control
Task 2: Stock Price Prediction (Short-Term)
Objective

Predict the next day’s stock closing price using historical market data.

Dataset Used

Data collected using yfinance

Features:

Open
High
Low
Volume

Target:

Next day closing price
Models Applied
Linear Regression
Random Forest Regressor
Key Results & Findings
Random Forest performed better due to its ability to capture non-linear patterns
Time-series handling without shuffling was essential for realistic predictions
Predictions followed overall market trends but were limited by market volatility
Task 4: Mental Health Support Chatbot (Fine-Tuned LLM)
Objective

Create an empathetic chatbot capable of responding to emotional and mental health-related conversations.

Dataset Used
EmpatheticDialogues (Facebook AI)
Multi-turn conversational dataset converted into user-response pairs
Models & Techniques
DistilGPT2
LoRA (Low-Rank Adaptation)
Hugging Face Transformers Trainer API
Key Results & Findings
Successfully fine-tuned a lightweight LLM for empathetic responses
Learned conversational dataset transformation and preprocessing
Observed limitations of smaller models, including:
Repetitive responses
Context loss
Improved outputs using:
Prompt engineering
Decoding strategies (temperature, top-p, repetition penalty)
Key Learnings
Importance of data quality
Impact of model size
Proper tokenization and label masking techniques
Skills Demonstrated
Prompt Engineering
Gemini API Integration
LLM Fine-Tuning (LoRA, Hugging Face)
Dataset Preprocessing & Transformation
Time Series Analysis
Regression Modeling
Model Evaluation & Visualization
Conversational AI Development
AI Safety Handling
Future Improvements
Upgrade to larger models (e.g., Mistral-7B with QLoRA)
Build a Streamlit-based deployment UI
Add sentiment detection for improved emotional understanding
Enhance stock prediction using LSTM and deep learning models
Conclusion

This repository demonstrates practical AI applications in:

Conversational AI
Mental health support systems
Financial forecasting

It highlights both the strengths and limitations of machine learning models in real-world scenarios.
