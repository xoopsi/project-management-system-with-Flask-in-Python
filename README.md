# Project Management System with Flask

A demo Project Management System implemented with Flask.  
This repository contains a short demo video and documentation describing the app architecture and main features.

## Demo
- Demo video: (paste your demo link here — YouTube or GitHub Release)
- Tip: For best UX host the video on YouTube (Unlisted) and embed the link here.

## Summary
This web app demonstrates core project management features:
- Project & client management
- Phase planning (Gantt) with weighted checklists
- Financial transactions with document uploads
- Progress reporting per phase with file attachments
- Interactive charts for planned vs actual progress (Plotly)
- User profiles with avatar upload

## Key Features
- Roles: System Admin, Project Manager, Accountant, Collaborator
- Create projects and phases; assign weights to phases and checklist items
- Gantt chart planning with validation (phase weights sum to 100)
- Record transactions (contract / income / expense) with file attachments
- Submit progress reports per phase; prevents regressive percentage updates
- Archive uploaded documents per checklist item
- Profile page: avatar upload and password change
- Interactive Plotly charts: planned vs actual progress, with a vertical line for today

## Tech Stack
- Backend: Python 3 + Flask
- ORM: SQLAlchemy (SQLite for demo)
- Charts: Plotly
- Frontend: Bootstrap + custom CSS (static/css/)
- Utilities: werkzeug (secure_filename, password hashing)

## Project Structure (high level)
- `app.py` — Flask app and routes
- `models.py` — SQLAlchemy models
- `templates/` — Jinja2 templates (HTML)
- `static/` — CSS, JS, images
- `uploads/` — uploaded files (add to `.gitignore`)
- `requirements.txt` — Python dependencies

## Notes
- This demo uses SQLite for simplicity. For production, use PostgreSQL/MySQL and Flask-Migrate.
- Use an environment variable for `SECRET_KEY` in production.
- Monitor storage usage for `uploads/` if many documents are stored.

## Contact
- Demo video: (paste link)
- Repository: https://github.com/xoopsi/project-management-system-with-Flask-in-Python
- Contact:
-   E-mail  :  hadi.shirin@gmail.com
-   Telegram : @mhshirin
