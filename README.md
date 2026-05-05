# Task 5: Mental Health Support Chatbot

**Objective:** Build a chatbot that provides supportive 
and empathetic responses for stress, anxiety and emotional wellness.

**Dataset:** EmpatheticDialogues 
(bdotloh/empathetic-dialogues-contexts) — 19,209 examples

**Model:** DistilGPT2 fine-tuned using HuggingFace Trainer API

**Key Features:**
- Fine-tuned on real emotional situations dataset
- Acknowledges feelings with empathy
- Gives 3-4 practical solutions per situation
- Suggests professional help when needed
- Friendly and warm tone throughout

**Tools Used:** Python, HuggingFace Transformers, 
DistilGPT2, OpenRouter API, Google Colab (T4 GPU)

## How to Run
1. Open notebook in Google Colab
2. Enable T4 GPU runtime
3. Add your OpenRouter API key in Cell 9
4. Run all cells
