# Bach-Style Music Generator

An LSTM trained on Bach's chorales to generate new melodic lines in a similar style.

## Features
- Trains on all 433 Bach chorales bundled with `music21` — no dataset download needed
- Preprocesses notes into pitch + duration tokens
- 2-layer LSTM, trained with early stopping
- Generates new sequences via temperature sampling
- Exports a playable MIDI file, with an optional in-notebook audio preview

## Run it
Open `CodeAlpha_MusicGenerationWithAI.ipynb` in Google Colab, set **Runtime → Change runtime type → GPU**, then Run All.

## Stack
Python, TensorFlow/Keras, music21, FluidSynth (for the audio preview)

---
CodeAlpha AI Internship — Task 3: Music Generation with AI
