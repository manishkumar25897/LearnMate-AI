# LearnMate AI — Final Project Package
**Student:** Manish Kumar  
**Programme:** AICTE–BharatCares–IBM SkillsBuild Machine Learning and Applied AI Internship 2026

## Required submission items
The provided Masterclass 5 instructions indicate three deliverables: **Lean Canvas PDF, Concept Note, and PowerPoint Presentation**. They are included in `docs/`. The package also includes a runnable prototype and demo/viva notes.

## Project
LearnMate AI is an educational prototype aligned conceptually with SDG 4: Quality Education. It demonstrates supervised classification using four example indicators and provides general revision suggestions.

## Transparency
The prototype uses a synthetic demo dataset. It does not use real student data, does not diagnose a learner, does not make high-stakes decisions, and does not claim IBM watsonx integration or online deployment. Do not claim real-world learning impact.

## Run on Windows
1. Install Python 3.10–3.12 from https://www.python.org/downloads/ (select “Add Python to PATH”).
2. Extract the ZIP and open the folder in VS Code.
3. Open Terminal and run:
   ```powershell
   py -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```
   If activation is blocked, use Command Prompt and run `.venv\Scripts\activate.bat`.
4. Install packages:
   ```powershell
   python -m pip install --upgrade pip
   pip install -r requirements.txt
   ```
5. Run:
   ```powershell
   python -m streamlit run app.py
   ```
6. Open the local URL shown in the terminal, usually `http://localhost:8501`.

## Demo sequence
Dashboard → Explore Demo Data → Student Assessment (change sliders and click Generate learning support plan) → Model Evaluation.

## Included files
- `app.py` — working Streamlit prototype and Logistic Regression workflow
- `requirements.txt` — dependencies
- `docs/LeanMate_AI_Lean_Canvas.pdf` — Lean Canvas
- `docs/LeanMate_AI_Concept_Note.pdf` and `.docx` — concept note
- `docs/LeanMate_AI_Presentation.pptx` — presentation
- `docs/Demo_and_Viva_Guide.md` — speaking script and viva questions
- `docs/Submission_Checklist.md` — final checks
