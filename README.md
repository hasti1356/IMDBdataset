# IMDB Sentiment Classification

Early practice notebook for binary sentiment classification on the [IMDB reviews](https://ai.stanford.edu/~amaas/data/sentiment/) dataset using Keras.

The notebook loads the top 10,000 words, pads sequences, and trains a baseline model. Accuracy is still modest — this repo documents the first iteration before tuning embeddings and architecture.

## Files

- `IMDBDataset.ipynb` — data loading, preprocessing, and model training

## Setup

```bash
pip install -r requirements.txt
jupyter notebook IMDBDataset.ipynb
```

## Notes

- Vocabulary capped at 10,000 words (`num_words=10000`)
- Intended as a learning exercise, not production-ready
- See `requirements.txt` for pinned dependency versions
- Keras IMDB data is downloaded automatically on first notebook run
