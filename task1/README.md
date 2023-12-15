## Task 1: Behaviour Simulation

#### Setup

Downlaod data and run:

```bash
>> pip install -r requirements.txt
```

#### Finetune SBERT (`mpnet-base`)

Make negative (large likes difference) and positive (similar likes) tweet content pairs from the training data and use the contrastive loss to finetune our SBERT.

```bash
>> python finetune-sbert.py
```

#### Generate Embeddings

Use finetuned `mpnet-base` to generate embeddings for the tweet content and tweet metadata. Use `clip-vit-base` to generate embeddings for the tweet media.

```bash
>> python gererate-embeddigns.py
```

#### Embedding Search

Use the generated embeddings to search for similar tweet content and tweet metadata with FAISS.

```bash
>> python embedding-search.py
```
