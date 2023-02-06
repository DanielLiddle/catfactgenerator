!pip install openai
import openai

# Use your OpenAI API key here
openai.api_key = "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"

def generate_cat_fact():
  response = openai.Completion.create(
    engine="text-davinci-002",
    prompt="Tell me a cat fact",
    max_tokens=100,
    n=1,
    stop=None,
    temperature=0.5,
  )

  message = response["choices"][0]["text"].strip()
  return message
