# RAG Data Pipeline

> 🚧 **Work in progress.** This repo is an early-stage exploration of the data-ingestion stage of a RAG pipeline. The document-ingestion notebook works; the rest is still being built.

A work-in-progress project exploring the data ingestion and parsing stages of a
Retrieval-Augmented Generation (RAG) pipeline — loading source documents,
parsing them, and preparing them for embedding and retrieval.

## Contents

```
.
├── 0-DataIngestParsing/
│   └── 1-dataingestion.ipynb    # Document ingestion & parsing experiments
├── main.py
├── pyproject.toml               # Project metadata (managed with uv)
└── requirements.txt
```

## Setup

This project uses [uv](https://github.com/astral-sh/uv) for dependency
management.

```bash
uv sync
# or with pip:
pip install -r requirements.txt
```

## Usage

Open the notebook to follow the ingestion/parsing steps:

```bash
jupyter notebook 0-DataIngestParsing/1-dataingestion.ipynb
```

## License

Released under the [MIT License](LICENSE).
