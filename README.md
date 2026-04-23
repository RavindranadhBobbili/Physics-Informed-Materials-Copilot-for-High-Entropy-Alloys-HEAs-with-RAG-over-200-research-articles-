materials_copilot/
├── app/
│   ├── __init__.py
│   ├── main.py              # FastAPI app
│   ├── models.py            # Pydantic models
│   ├── rag_engine.py        # RAG over HEAs
│   ├── ml_predictor.py      # Physics-informed ML
│   ├── dashboard.py         # Streamlit dashboard
│   └── utils.py
├── data/
│   ├── papers/              # 200 HEA research articles (PDFs)
│   ├── alloy_db.csv         # Known HEA properties
│   └── vector_store/        # ChromaDB persistence
├── requirements.txt
└── docker-compose.yml


fastapi==0.104.1
uvicorn==0.24.0
streamlit==1.28.1
chromadb==0.4.18
sentence-transformers==2.2.2
torch==2.1.0
numpy==1.24.3
pandas==2.0.3
scikit-learn==1.3.0
pymupdf==1.23.8
langchain==0.0.340
pydantic==2.4.2
python-multipart==0.0.6
plotly==5.17.0



Demonstrated skills

✅ Machine Learning (Random Forest, Gradient Boosting, PyTorch)
✅ Deep Learning (Custom PINN architecture)
✅ NLP (Sentence transformers, RAG, text splitting)
✅ Backend Development (FastAPI, async, middleware)
✅ Frontend (Streamlit, Plotly, data viz)
✅ DevOps (Docker, environment variables)
✅ MLOps (Model persistence, scaling)
✅ Materials Science (Phase diagrams, Hume-Rothery rules)
matplotlib==3.7.2
seaborn==0.12.2
joblib==1.3.2
