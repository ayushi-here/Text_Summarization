📰 Text Summarization using BART
This project implements abstractive text summarization using a pre-trained BART (facebook/bart-large-cnn) model from HuggingFace.

We used the CNN/DailyMail dataset (via KaggleHub) and built a working interface using Gradio to allow users to paste long articles and get concise summaries.

🔧 What’s Inside:
Loaded and cleaned the dataset (article + highlights).

Used HuggingFace's summarization pipeline (based on BART).

Displayed sample results from real data.

Built a simple user interface using Gradio for live input/output.

🔍 Key Concepts:
Pre-trained transformer model (BART = encoder + decoder).

Fine-tuning not done manually — we used a ready fine-tuned model.

The model is abstractive, meaning it generates new text rather than copying.
