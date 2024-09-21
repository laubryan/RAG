# RAG Experiment

A personal experiment to build a RAG system that can answer questions from information sourced from a PDF document, in this case a PDF manual for my Garmin watch.

Uses:

- The llama 3.1 LLM model
- Sentence embeddings

## Improvements

As an initial PoC it worked well enough, but it definitely needs some improvements:

- Grouping the text from the PDF into chapters would probably greatly improve the effectiveness of the responses.
- Save/load the vectorized embeddings so that they don't have to be generated each time.
- Build a user interface.
