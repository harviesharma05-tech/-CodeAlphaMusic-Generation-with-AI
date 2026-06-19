# Bach-Style Music Generator

An LSTM trained on Bach's chorales to generate new melodic lines in a similar style.

## Features
- Trains on all 433 Bach chorales bundled with `music21` — no dataset download needed
- Preprocesses notes into pitch + duration tokens
- 2-layer LSTM, trained with early stopping
- Generates new sequences via temperature sampling
- Exports a playable MIDI file, with an optional in-notebook audio preview

## Run it
This is a standard Jupyter notebook — open it with any Jupyter setup you have (Jupyter Notebook, JupyterLab, VS Code's Jupyter extension, Google Colab, etc.) and run all cells top to bottom. Needs Python with TensorFlow, music21, and matplotlib; the first cell installs anything missing.

## Stack
Python, TensorFlow/Keras, music21, FluidSynth (for the audio preview)

---
CodeAlpha AI Internship — Task 3: Music Generation with AI
