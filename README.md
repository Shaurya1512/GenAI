# 🤖 AI Prompt Playground

A simple web app that lets you experiment with different AI prompt styles using the Claude API.

## What it does

You type any text or topic, pick a mode, and the app sends it to Claude with a different system prompt depending on the mode you chose.

## Modes

- **Explain Like I'm 5** – breaks down any topic into simple, easy-to-understand language
- **Professional Rewrite** – rewrites your text to sound more formal and polished
- **Quiz Generator** – generates 5 multiple choice questions on any topic
- **Study Plan** – creates a 4-week study plan for anything you want to learn

## How to run it

1. Clone this repo
2. Open `index.html` in your browser
3. Replace `YOUR_API_KEY_HERE` in the script with your actual Anthropic API key
4. That's it!

## Tech used

- HTML, CSS, JavaScript (no frameworks)
- Claude API (claude-sonnet-4-6)

## Note

This is a frontend-only project built for learning purposes. The API key is in the client code which is not safe for production — don't share your key publicly.
