# Image Caption Generation

Term project for Deep Learning (CS60010, Spring 2024) at IIT Kharagpur, done as a group of four (Group G-07): build encoder-decoder models that generate a caption for an image.

## Models

| Notebook | Encoder | Decoder |
|---|---|---|
| `team_id_7_a.ipynb` | Pre-trained Inception-v3 (CNN) | LSTM |
| `team_id_7_b.ipynb` | Vision Transformer (ViT) | BERT-based text decoder (Hugging Face Transformers) |

Both models are evaluated with BLEU, ROUGE and CIDEr.

## Data

A custom captions dataset (`train.csv` and `test.csv` with image paths and captions). The dataset is not included in this repository; the link and other details are in `Deep Learning Term Project.pdf`.

## Files

- `team_id_7_a.ipynb`: Part A, CNN encoder with LSTM decoder (PyTorch)
- `team_id_7_b.ipynb`: Part B, ViT encoder with Transformer decoder
- `Deep Learning Term Project.pdf`: problem statement and dataset details
