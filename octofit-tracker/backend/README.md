# OctoFit Tracker — Backend

This folder will contain the Django backend for OctoFit Tracker.

Setup (local development):

1. Create a Python virtual environment:

```bash
python3 -m venv octofit-tracker/backend/venv
source octofit-tracker/backend/venv/bin/activate
```

2. Install dependencies:

```bash
pip install -r octofit-tracker/backend/requirements.txt
```

3. Use Django's management commands to create the project and apps.

Notes:
- Follow the repository's `.github/instructions` for required packages and conventions.
- Use Django ORM for database work; do not write direct MongoDB scripts.
