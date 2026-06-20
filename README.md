# Bach-Style Music Generator

An LSTM trained to generate new melodic lines in a similar style — two versions, same idea.

## `index.html` — runs entirely in your browser, no install
Trains a small LSTM live in the browser tab on 22 hand-written diatonic phrases, using TensorFlow.js. Just open the file — no Python, no Colab, no Jupyter.

1. Click **Train model** — trains in a few seconds, loss chart updates live
2. Click **Generate melody** — see it as a piano-roll
3. **▶ Play** to hear it (Web Audio, no plugins), or **Download .mid** to save it

This is the lightweight, self-contained version — built from a small 22-phrase dataset, not a full corpus, so treat it as a working demo of the pipeline rather than a polished composer.

## `CodeAlpha_MusicGenerationWithAI.ipynb` — the full version
Trains on all 433 real Bach chorales bundled with `music21`, with a bigger model. Needs Python — open in Jupyter, VS Code, or Google Colab and run all cells. See the notebook itself for details.

## Features (both versions)
- Collects/preprocesses note data into pitch:duration tokens
- 2-layer LSTM trained from scratch
- Temperature-sampled generation
- Exports a playable, standard MIDI file

## Stack
`index.html`: HTML, CSS, vanilla JS, TensorFlow.js (CDN) — including a from-scratch MIDI file writer, no library needed.
Notebook: Python, TensorFlow/Keras, music21.

---
CodeAlpha AI Internship — Task 3: Music Generation with AI


---
CodeAlpha AI Internship — Task 3: Music Generation with AI
