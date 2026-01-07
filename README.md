# Coding a ChatGPT like transformer from scratch

This project is a basic AI text generator trained on Shakespeare's writing. It uses PyTorch to predict the next character in a sequence, creating new text that mimics the style of the original dataset.

## What it does
1.  **Downloads Data:** Automatically fetches the Tiny Shakespeare dataset.
2.  **Trains:** Uses a simple Bigram Neural Network (trained for 5000 steps).
3.  **Generates:** Outputs new, random text based on what it learned.

## Requirements
* Python 3
* PyTorch (`pip install torch`)

## How to Run
Simply open and run the notebook `23B0278_Assignment_Week3.ipynb`. The script will handle data downloading, training, and text generation automatically.

## Sample Output
The model generates text like this:
> "CHNCKIViver HelozR'd jemiok..."

(Since it is a simple Bigram model, the text structure is basic, but it learns valid characters and some pairings).
