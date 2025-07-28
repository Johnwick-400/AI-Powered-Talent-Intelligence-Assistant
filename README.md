# AI Powered Talent Intelligence Assistant

## Overview
The AI Assistant is an advanced, AI-powered platform designed to streamline and enhance every aspect of creating, analyzing, and optimizing job descriptions (JDs). Utilizing state-of-the-art language models, this tool provides intelligent support to recruiters and hiring managers throughout the JD lifecycle, ensuring accuracy, market alignment, and increased efficiency.

## Core Features

- **JD Creation & Input**
  - Upload existing JDs in PDF, DOCX, or TXT formats.
  - Auto-detect job titles or prompt for input if missing.
  - Step-by-step conversational AI for drafting JDs from scratch.

- **AI-Powered Data Extraction & Guidance**
  - Automatically parses uploaded JDs to extract structured data.
  - Identifies missing or incomplete sections and prompts for completion.
  - Uses chat-based interaction to collect required details (employment type, experience, location, salary, skills, etc.).

- **AI Skill Suggestion**
  - Analyzes roles to recommend must-have and good-to-have skills, with explanations.
  - Suggestions are fully editable by the user.

- **Market Analysis**
  - Evaluates talent availability, demand/supply trends, time-to-hire, and salary bands.
  - Focuses primarily on the Indian job market.
  - Combines real-time AI market research with fallback data templates.
  - Presents findings in clear tables and optional charts.

- **Role Mapping**
  - Suggests alternative job titles with match scores and rationale.
  - Supports broader and flexible recruitment strategies.

- **Review & Export**
  - Compiles a clean, standardized JD summary incorporating all inputs.
  - Allows downloading final JDs in DOCX format and exporting structured data as JSON.

- **Workflow & User Experience**
  - Visual progress tracking indicators.
  - Robust error handling and fallback strategies.
  - Session management to resume or iterate work seamlessly.

## API Integrations

- **Mistral API**  
  Utilized for advanced natural language understanding, including:
  - Parsing and summarizing job descriptions.
  - Skill and role mapping suggestions.
  - Driving multi-turn conversational workflows.

- **Gemini API**  
  Leveraged for:
  - Real-time market analysis (salary, skills demand, talent availability).
  - Context-aware, multi-turn conversational interactions.
  - Enhancing insights with multimodal capabilities where applicable.

## Typical User Flow

| Stage            | User Action                        | System Response                                      |
|------------------|----------------------------------|-----------------------------------------------------|
| Launch           | Select "Upload JD" or "Create New" | Presents appropriate JD creation or upload workflow |
| Input/Upload JD  | Provide JD file or enter details  | AI parses JD or initiates interactive chat form     |
| Field Completion | Fill in missing data via chat     | AI asks targeted questions to complete the JD data  |
| Skill Suggestions| Review and edit AI skill suggestions | Suggestions with rationale shown, editable          |
| Market Analysis  | Request market insights           | Displays market data, trends, and compensation stats|
| Role Mapping     | Review suggested alternative roles | Provides match scores and recommendations            |
| JD Finalization  | Review and edit compiled JD       | Editable summary with download options (PDF/DOCX/JSON)  |

## Technologies Used

- Natural Language Processing (NLP) & Large Language Models
- Python (or your development language)
- Mistral API for LLM capabilities
- Gemini API for market intelligence and conversational AI
- Data visualization libraries (e.g., matplotlib, Plotly) for charts
- (Add UI framework or other supporting tech as applicable)

## Installation & Usage

1. Clone the repository:
    ```
    git clone https://github.com/Johnwick-400/AI-Powered-Talent-Intelligence-Assistant
    ```
2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Set up environment variables for API keys:
    - `MISTRAL_API_KEY`
    - `GEMINI_API_KEY`
4. Run the application:
    ```
    python app.py
    ```
5. Follow the on-screen instructions to upload JDs, enter data, and explore features.

## Project Status

- Fully functional AI assistant with JD analysis, skill and role mapping, and market analytics.
- Designed to be modular and extensible for new features or market expansions.

## Contact

For questions or collaboration opportunities, please contact: [pavantejveesam26@gmail.com]

---

*This project is a personal AI development focused on automating and enhancing job description lifecycle management with state-of-the-art language models.*
