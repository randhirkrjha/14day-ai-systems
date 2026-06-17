| Step | Command                                                                      | Purpose                      | Result                      |
| ---- | ---------------------------------------------------------------------------- | ---------------------------- | --------------------------- |
| 1    | `python --version`                                                           | Verify Python installation   | Python working              |
| 2    | `python -m venv .venv`                                                       | Create virtual environment   | `.venv` created             |
| 3    | `.venv\Scripts\activate`                                                     | Activate virtual environment | `(.venv)` prompt displayed  |
| 4    | `mkdir src scripts tests docs`                                               | Create project folders       | Folder structure created    |
| 5    | Create `.gitignore`                                                          | Ignore unwanted files        | Git exclusions configured   |
| 6    | Create `README.md`                                                           | Project documentation        | README added                |
| 7    | Create `scripts/hello_ai.py`                                                 | First Python script          | Script created              |
| 8    | `python scripts/hello_ai.py`                                                 | Execute script               | Script ran successfully     |
| 9    | `git --version`                                                              | Verify Git installation      | Git working                 |
| 10   | `git init`                                                                   | Initialize Git repository    | `.git` folder created       |
| 11   | `git status`                                                                 | Check repository state       | Files shown as untracked    |
| 12   | `git add .`                                                                  | Stage all files              | Files moved to staging area |
| 13   | `git status`                                                                 | Verify staged files          | Ready for commit            |
| 14   | `git commit -m "Day 2: initial project setup"`                               | Create first snapshot        | Commit `b2c9085` created    |
| 15   | `git log --oneline`                                                          | View commit history          | First commit visible        |
| 16   | `git branch -M main`                                                         | Rename branch                | `master` → `main`           |
| 17   | `git remote add origin https://github.com/randhirkrjha/14day-ai-systems.git` | Connect GitHub repository    | Remote configured           |
| 18   | `git push -u origin main`                                                    | First push attempt           | Authentication failed       |
| 19   | Browser authentication                                                       | Sign in to GitHub            | Access granted              |
| 20   | `git push -u origin main`                                                    | Push code to GitHub          | Success                     |
| 21   | `python -m pip freeze > requirements.txt`                                    | Generate dependency list     | requirements.txt created    |
| 22   | `git add requirements.txt`                                                   | Stage dependency file        | Ready for commit            |
| 23   | `git commit -m "Add requirements.txt"`                                       | Second snapshot              | Commit `d3080a9` created    |
| 24   | `git push`                                                                   | Upload second commit         | GitHub updated              |
