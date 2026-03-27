# PythonFlaskAPI – Text Analyzer Web App

A simple Flask-based web application that provides a text analysis interface via web forms and HTML templates.[page:1]

## Features

- Flask backend application (`webpython.py`) for handling routes and text processing.[page:1]
- HTML templates for layout and content pages (`home.html`, `about.html`, `post.html`, `layout.html` and `templates/`).[page:1]
- Dependency management via `requirements.txt` for easy environment setup.[page:1]

## Project Structure

- `webpython.py` – Main Flask application file (routes, request handling, and text analysis logic).[page:1]
- `templates/` – Jinja2 templates for rendering pages in the browser.[page:1]
- `home.html`, `about.html`, `post.html`, `layout.html` – Top-level HTML files used for the web UI.[page:1]
- `requirements.txt` – Python package dependencies for the project.[page:1]
- `.gitignore` – Standard ignores for Python projects and virtual environments.[page:1]

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Annamalai23/PythonFlaskAPI.git
   cd PythonFlaskAPI
   ```

2. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/macOS
   venv\Scripts\activate      # Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask app:
   ```bash
   python webpython.py
   ```

5. Open the app in your browser:
   - Navigate to `http://127.0.0.1:5000/` (or the host/port shown in the terminal).

## Customization

- Update `templates/` and the HTML files to change the look and feel of the UI.[page:1]
- Modify `webpython.py` to adjust routes or extend the text analysis logic.[page:1]

## Requirements

- Python 3.x
- Packages listed in `requirements.txt`.[page:1]

## License

This project is currently unlicensed; feel free to add a license of your choice (e.g., MIT, Apache 2.0) if you plan to share or reuse it.
