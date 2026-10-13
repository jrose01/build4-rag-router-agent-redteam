# build4-rag-router-agent-redteam
Stripped-down RAG router agent repo for red team testing 

## Purpose
This app is a Streamlit front end for our Build4 RAG router data analysis agent.

## Files
- `app_streamlit_build4.py` = Streamlit frontend
- `src/build4_rag_router_streamlit.py` = build4 backend logic
- `src/tools` = tool registry and functions
- `rag_store/` = RAG index and metadata (raig_fass.index and rag_chunks.pkl) 
- `data/` = test data set(s)
- `requirements.txt` = Python dependencies

## Deployment notes
- This app is deployed on Streamlit Community Cloud
- The OpenAI API key is stored in Streamlit secrets
- The app is shared with redteam testers
