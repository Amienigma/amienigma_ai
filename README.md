# amienigma_ai
# Amienigma AI

A recursive information system exploring art, neglect,
memory, symbolism, and hidden pathways across media.
from transformers import pipeline

ai = pipeline("text-generation", model="gpt2")

prompt = input("Enter prompt: ")

response = ai(prompt, max_length=100)

print(response[0]["generated_text"])

