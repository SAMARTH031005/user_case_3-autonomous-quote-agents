# Autonomous Quote Agent System

This project builds an AI-powered multi-agent system that automates insurance quote evaluation.

## Agents in the System

1. **Risk Profiler Agent**
   - Predicts the risk score of the quote.

2. **Conversion Predictor Agent**
   - Predicts the probability that a quote will bind.

3. **Premium Advisor Agent**
   - Suggests whether the premium should be adjusted.

4. **Decision Router Agent**
   - Produces the final decision:
     - Auto Approve
     - Agent Follow-Up
     - Escalate to Underwriter

## Tech Stack

- Python
- scikit-learn
- XGBoost
- Streamlit

## Files

- `train_pipeline.py` – model training pipeline
- `app.py` – Streamlit deployment app
- `risk_agent.pkl` – trained risk model
- `conversion_agent.pkl` – trained conversion model
- `encoders.pkl` – label encoders

## Deployment

The system is deployed using Streamlit.
