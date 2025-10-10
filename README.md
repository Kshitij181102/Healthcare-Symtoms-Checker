# Healthcare Symptom Checker

**⚠️ EDUCATIONAL PURPOSE ONLY - NOT FOR MEDICAL DIAGNOSIS**

A symptom checker application that uses Google Gemini 2.0 Flash AI to suggest possible conditions and next steps based on user-reported symptoms.
           The Demo video link -https://drive.google.com/file/d/1PswlrShHgUyX8g87auT3HaxAcWbTcKTi/view?usp=sharing
## Quick Setup

1. **Get Google API Key** (Required)
   - Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Create a new API key
   - **Note**: A valid API key is required - the app will not work without it

2. **Configure Environment**
   ```bash
   cp .env.example .env
   # Edit .env and add your actual API key
   ```

3. **Install & Run**
   ```bash
   npm install
   npm start
   ```

4. **Access Application**
   - Frontend: http://localhost:3000
   - API: http://localhost:3000/api

## API Usage

**Analyze Symptoms:**
```bash
curl -X POST http://localhost:3000/api/symptoms \
  -H "Content-Type: application/json" \
  -d '{"symptoms": "headache and fever for 2 days"}'
```

**Get History:**
```bash
curl http://localhost:3000/api/history
```

## Tech Stack

- **Backend**: Node.js + Express
- **Database**: SQLite
- **AI**: Google Gemini 2.0 Flash
- **Frontend**: HTML/CSS/JavaScript
- **Deployment**: Vercel


## Safety Notice

This application is for educational purposes only. Always consult healthcare professionals for medical advice, diagnosis, or treatment."# Healthcare-Symtoms-Checker" 
