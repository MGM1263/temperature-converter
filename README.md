Temperature Converter

A simple Python application to convert temperatures between Celsius, Fahrenheit, and
Kelvin.

Installation
1. Clone this repository:
git clone <your-repo-url>
cd temperature-converter

2. Create a virtual environment:
python3 -m venv venv
source venv/bin/activate # macOS/Linux
venv\Scripts\activate # Windows

3. Install dependencies (if any):
pip install -r requirements.txt

Usage
python src/temp_app/converter.py

Features
• Convert Celsius ↔ Fahrenheit
• Convert Celsius ↔ Kelvin
• Clean, documented code
 Professional project structure

Author
Millgo 

Step 1.4: Create .gitignore
Tell Git which files to ignore:
Edit the file and add the following.
Virtual environment
venv/
env/
ENV/
Python bytecode
pycache/
*.pyc
*.pyo
*.pyd
.Python
IDE
.vscode/
.idea/
*.swp
*.swo
OS
.DS_Store
Thumbs.db
Project
.env
config.local
*log.