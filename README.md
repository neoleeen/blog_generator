# Blog Generator

A Python program that uses the OpenAI API to write a paragraph on any topic you give it. You can keep going to build a blog one paragraph at a time.

Built following the Codedex.io tutorial "Generate a Blog with OpenAI".

## How to run it

1. Install the packages: `pip install openai python-dotenv`
2. Create a file called `.env` in the project folder containing: `API_KEY=your-openai-key`
3. Run: `python blog_generator.py`

## What I learned

- Calling an API from Python
- Using a while loop to repeat tasks
- Keeping API keys secret with a `.env` file and `.gitignore`

## Changes from the tutorial

The tutorial's model (`gpt-3.5-turbo-instruct`) has been retired by OpenAI, so I updated the code to use the chat API and a current model.
