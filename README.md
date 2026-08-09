# Leiden Algorithm Notebook

Single exploratory notebook: community detection over a similarity graph using
`igraph` + `leidenalg`, with sentence-transformer embeddings for similarity.

## Run

```bash
pip install -r requirements.txt
jupyter lab
```

## Docker

```bash
docker build -t leiden-algorithm-notebook .
docker run --rm -p 8888:8888 leiden-algorithm-notebook
```
