
# 🧾 Contract Analyzer AI

This assistant uses OpenAI GPT-4 and LangChain to:
- Extract key sections from uploaded contracts (start date, termination, compensation, etc.)
- Identify legal red flags such as auto-renewal or one-sided liability
- Explain contracts in plain English for non-lawyers
- Answer custom legal questions like "Can I terminate early?"

### Example Use Cases:
- Upload an LLC Operating Agreement and get a breakdown
- Spot vague or risky terms automatically
- Ask targeted legal questions directly to the contract

### Files:
- contract_assistant.ipynb: Colab notebook with full logic
- requirements.txt: Python dependencies
- README.md: This file

### Run Instructions:
```bash
pip install -r requirements.txt
# Then open and run the notebook in Google Colab
