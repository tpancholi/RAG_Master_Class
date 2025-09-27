# RAG-MasterClass - Euron

## Model Inference Platform
- [One Euri Platform](https://euron.one/euri)

## Notebooks
- [Rag Pipeline Demo](notebooks/rag_pipeline_demo.ipynb)
- [Document loading via langchain and llamaindex](notebooks/document_loading.ipynb)
- [Different chunking strategy](notebooks/chunking_splitting_metadata.ipynb)
- [Cosine similarity in vectors](notebooks/cosign_normalization.ipynb)
- [Vector DB Comparisons](notebooks/vectordb_comparision.ipynb)

### Important commands
# Show all available options

```
uv run ruff check --help
```

# Show statistics about fixes applied
```
uv run ruff check . --fix --show-fixes
```

# Show which files were processed
```
uv run ruff check . --show-files
```

# Combine multiple flags
```
uv run ruff check . --fix --show-fixes --show-files
```
