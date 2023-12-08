
### Development environment
* Install PySerini ['docs'](https://github.com/castorini/pyserini/blob/master/docs/installation.md)

### Lucene indexing for sparse vectors (SPLADE)

```bash
python -m pyserini.index.lucene \
    --collection JsonCollection \
    --input collections/reddit_2019-07/collection_jsonl \
    --index indexes/lucene-index-reddit_test \
    --generator DefaultLuceneDocumentGenerator \
    --threads 9 \
    --storePositions \
    --storeDocvectors \
    --storeRaw
```

### Faiss indexing for dense vectors (SentenceTransformers)


### BibTex citation
```
TODO
```
