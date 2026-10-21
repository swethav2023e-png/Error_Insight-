# ErrorInsight – Intelligent Error Analyzer

## Run
1. Extract the ZIP.
2. Open the `ErrorInsight_Colorful` folder in VS Code.
3. Open Terminal in that folder.
4. Run `pip install -r requirements.txt`
5. Run `python app.py`
6. Open `http://127.0.0.1:5000`

IMPORTANT: Do not double-click templates/index.html. Start Flask and open the localhost address.

## Features
Professional colorful dashboard, JSON upload, error categorization, frequency analysis,
severity distribution, recurring errors, causes, recommendations and recent logs.

## API
GET /api/demo
POST /api/analyze (multipart field: file)
