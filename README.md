# Bill Bachao

AI-powered electricity bill reader and personalized energy-saving assistant.
Built for the 1M1B AI for Sustainability Virtual Internship (SDG 7: Affordable and Clean Energy).

## What it does
- Reads an uploaded electricity bill image, or accepts manual entry
- Requires a mandatory appliance checklist so the AI never assumes appliances the household doesn't own
- Generates an appliance-wise consumption breakdown
- Detects anomalies/unusual bill spikes with likely causes
- Gives 3 personalized, rupee-quantified saving tips
- Includes a follow-up chat to ask questions about your bill

## Tech
HTML/CSS/JavaScript frontend, powered by Claude (Anthropic) for multimodal bill reading and reasoning.

## How to run
This file calls the Anthropic API directly and is designed to run inside Claude.ai's artifact preview, where the API key is handled securely. To run it standalone, you'd need your own Anthropic API key and a small backend proxy (not included in this version).
