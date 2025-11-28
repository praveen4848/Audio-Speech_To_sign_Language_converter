# Audio-Speech-To-Sign-Language-Converter

## Quick Start

### 1. Navigate to project directory
```powershell
# From Downloads folder
cd "Audio-Speech-To-Sign-Language-Converter (2)\core"

# Or full path
cd "C:\Users\nagar\Downloads\Audio-Speech-To-Sign-Language-Converter (2)\core"
```

### 2. Install dependencies
```powershell
pip install -r requirements.txt
```

### 3. Download NLTK data
```powershell
python -c "import nltk; nltk.download('averaged_perceptron_tagger'); nltk.download('wordnet'); nltk.download('omw-1.4')"
```

### 4. Run migrations
```powershell
python manage.py migrate
```

### 5. Run server
```powershell
python manage.py runserver
```

### 6. Open browser
```
http://127.0.0.1:8000/
```

## Project Structure

```
core/
├── A2SL/              # Django app
├── assets/            # Video files
├── templates/         # HTML templates
├── manage.py          # Django management
├── requirements.txt   # Dependencies
└── db.sqlite3         # Database
```

## Important Notes

- Use Chrome or Edge browser for speech recognition
- Internet connection required for Web Speech API
- Create user account to access animation feature

