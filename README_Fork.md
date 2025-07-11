# Steps to run the fork and run the agents repo
1. Fork the original repo: https://github.com/ed-donner/agents
2. Clone the forked repo
3. Install UV: curl -LsSf https://astral.sh/uv/install.sh | sh
4. Run: uv self update
5. Run: uv sync
6. Run: uv tool install crewai
7. Run: uv tool upgrade crewai
8. Open https://platform.openai.com
9. Signin and create a free key
10. Create .env file
11. Add Open AI Key in .env file: OPENAI_API_KEY=sk-proj-<The rest of the key>
12. Open any of the labs: e.g. 1_lab1.ipynb
13. Select the Kernel for Python to the latest one (.venv)