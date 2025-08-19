# git-laughs
# 😂 Git Laughs – Sitcom Edition

Make your commits funny!  
This Git hook plays a sitcom laugh track every time you `git commit`.

---

## 🚀 Setup
1. Clone this repo
2. Copy `hooks/post-commit` into your local repo’s `.git/hooks/`
3. Add `laugh.wav` into the `sounds/` folder
4. Make it executable (Linux/macOS/Git Bash on Windows)(Not necessary but safe to do):
   ```bash
   chmod +x .git/hooks/post-commit