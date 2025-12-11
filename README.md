# Toyota Company Intelligence Agent (LLM + Retrieval System)

## Case Study 2 - Data Analytics Senior Seminar

### Project Overview
AI-powered intelligence agent for Toyota Motor Corporation using Retrieval-Augmented Generation (RAG). The system analyzes 200+ pages of corporate documents to provide evidence-based answers to strategic questions.

### System Architecture
1. **Document Processing:** Toyota Integrated Report, ESG Data Book, Reuters analysis
2. **Chunking:** 292 semantic chunks (750 tokens each)
3. **Retrieval:** TF-IDF vectorization with cosine similarity
4. **LLM Integration:** GPT-3.5 Turbo with grounding prompts
5. **Interface:** Streamlit dashboard for interactive Q&A

### Key Features
- **Document-Grounded Q&A:** Answers based solely on provided corporate documents
- **Proper Citations:** Each answer cites specific chunk IDs as evidence
- **KPI Extraction:** Automated extraction of risk and ESG metrics
- **Interactive Dashboard:** User-friendly interface for exploration

### Repository Contents
- `toyota_analysis.py` - Main analysis and retrieval code
- `streamlit_app.py` - Interactive dashboard
- `data/` - Processed document chunks and metadata
- `Toyota_Intelligence_Agent_Report.pdf` - Complete project report

### Technologies Used
- Python (PyPDF2, scikit-learn, Streamlit)
- TF-IDF Vectorization
- GPT-3.5 Turbo API
- Retrieval-Augmented Generation (RAG)

### Authors
Shoumika Anannyo | Beloit College | Quantitative Economics & Data Analytics
