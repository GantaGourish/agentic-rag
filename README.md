# Agentic RAG

Retrieval-Augmented Generation (RAG) demo and utilities for agentic workflows.

## Summary

This repository contains experiments and utilities for building a small RAG system using Hugging Face models and local caching. It includes example code (`rag_code.py`), an interactive notebook (`notebook.ipynb`) and a minimal server (`server.py`). The project is suitable to showcase in a portfolio or resume.

## Features

- Retrieval + generation prototype using local HF models
- Caching of downloaded models under `hf_cache/` for reproducible demos
- Example server for serving embeddings / retrieval results
- Notebook with step-by-step walkthrough

## Quickstart

1. Create and activate a virtual environment:

```powershell
python -m venv .venv
& .venv\Scripts\Activate.ps1
```

2. Install dependencies:

```powershell
pip install -r requirements.txt
```

3. Run the notebook or example script:

```powershell
jupyter notebook notebook.ipynb
# or
python rag_code.py
# or start server
python server.py
```

## Files of interest

- `rag_code.py`: main demo code
- `server.py`: small HTTP demo server
- `notebook.ipynb`: walkthrough and examples

## Resume / Portfolio

See `PROJECT_OVERVIEW.md` for concise bullets you can paste into a resume or portfolio describing this project.

## Contributing

Contributions welcome — open an issue or submit a PR.

## License

This project is licensed under the MIT License — see `LICENSE`.
