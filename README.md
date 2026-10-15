# Feedback → Fix

A practice AI application that turns customer feedback into an
action plan for small businesses.

## Features

- Groups related customer complaints.
- Suggests priorities and practical actions.
- Includes supporting quotes from the original feedback.
- Validates the report structure and quoted evidence.

## Built with

- Python
- Streamlit
- Pydantic
- NVIDIA-hosted z-ai/glm-5.3
- OpenAI Python SDK configured for NVIDIA's API

## Run locally

Requires Python and an NVIDIA Build API key.

```bash
git clone https://github.com/gastonmartinezz/feedback-fix.git
cd feedback-fix

python3 -m venv .venv
source .venv/bin/activate

python -m pip install -r requirements.txt

export NVIDIA_API_KEY="your-nvidia-api-key"

python -m streamlit run app.py
```

Replace YOUR_USERNAME with the repository owner's GitHub username.

## Data and limitations

Submitted feedback is sent to NVIDIA for analysis.
Use fictional feedback when testing.

Reports are AI-generated. Review priorities and suggested actions
before using them.