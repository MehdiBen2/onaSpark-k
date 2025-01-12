# OnaSpark Project

## Overview
OnaSpark is a web application designed to [brief project description].

## Deployment on Koyeb

### Prerequisites
- Koyeb account
- Git repository

### Deployment Steps
1. Connect your GitHub/GitLab repository to Koyeb
2. Ensure `requirements.txt` is up to date
3. Configure `koyeb.yaml` for build and run commands
4. Set environment variables in Koyeb dashboard

### Environment Variables
- `DATABASE_URL`: Connection string for your database
- `SECRET_KEY`: Application secret key
- `DEBUG`: Set to `False` in production

### Deployment Configuration
- **Platform**: Koyeb
- **Build Method**: Direct Python deployment
- **Build Command**: 
  ```
  python3 -m venv venv
  . venv/bin/activate
  pip install -r requirements.txt
  ```
- **Run Command**: `python app.py`
- **Port**: 8000

### Local Development
```bash
# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

## Contributing
Please read our coding guidelines before contributing.

## License
[Specify your license]
