# 📘 Notes: Python + AI DevOps Assistant Journey

## ✅ Setup Progress

### GitHub & Project
- Created repository: **ai-devops-assistant**
- Accessing it from VS Code

### Python Environment
- Installed Python 3.11+
- Created virtual environment:
  ```bash
  python3 -m venv .venv
  source .venv/bin/activate
- Why venv? → Keeps dependencies isolated per project (like Composer in PHP).

### requests (library)
- Purpose: Makes HTTP requests (GET, POST, etc.)
- Why: Needed for calling APIs (OpenAI, AWS, Docker)
- Install: `pip install requests`
- Example:
  ```python
  import requests
  response = requests.get("https://api.github.com")
  print(response.status_code)
  print(response.json())