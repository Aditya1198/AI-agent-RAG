AI Legal Team

## Gemini 2.5 Flash-Lite Integration

This project uses the Google Gemini 2.5 Flash-Lite model for all LLM and embedding operations. To use this app:

1. Obtain a Gemini API key from Google.
2. Enter your Gemini API key in the Streamlit sidebar when running the app.
3. The app will use the `gemini-2.5-flash-lite` model for all agent and team operations.

### Requirements
- `google-genai` Python package (installed automatically from requirements.txt)

### How to Run
```sh
# Activate your virtual environment, then run:
streamlit run legal_agent_team.py
```

For more details, see the code and comments in `legal_agent_team.py`.

## Features
- Multi-agent legal document analysis using Google Gemini 2.5 Flash-Lite
- Qdrant vector database for semantic search and retrieval
- Custom Gemini-based embedder (hash fallback)
- Streamlit UI for easy document upload and analysis
- Modular agent/team design for legal research, contract analysis, and strategy

## Usage Steps
1. Clone this repository and set up your Python virtual environment.
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the app:
   ```sh
   streamlit run legal_agent_team.py
   ```
4. Enter your Gemini API key, Qdrant API key, and Qdrant URL in the sidebar.
5. Upload a legal document (PDF) and select the analysis type.
6. View results, key points, and recommendations in the app.

## Troubleshooting
- **Gemini API errors:** Ensure your API key is valid and has access to the `gemini-2.5-flash-lite` model.
- **Qdrant connection issues:** Double-check your Qdrant API key and URL.
- **Dependency errors:** Run `pip install --upgrade google-genai` to ensure the latest Gemini support.
- **Model not found:** If `gemini-2.5-flash-lite` is not available, check your Google account/model access or try a different Gemini model.

## Contributing
Pull requests and issues are welcome! Please ensure new features are documented and tested.