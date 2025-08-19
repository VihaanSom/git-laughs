# 🎶 git-laughs: 90's Sitcom Post-Commit Hook 😂

Welcome to **git-laughs** – specifically, the post-commit hook that brings 90’s sitcom vibes right to your terminal!

## What is This?

This repo contains a custom **git post-commit hook** that plays a classic 90’s sitcom sound effect after every commit.  
Now, every time you commit, you’ll hear the sweet jingle of nostalgia—think laugh tracks, theme songs, and more!

## 📀 How It Works
- You add a **post-commit hook** to your repo.
- Every time you `git commit`, it plays a canned 90’s sitcom laugh track.
- Boom. Instant morale boost. Developers nearby will either:
  - Think you’re a genius.
  - Think you’ve lost it.
  - Both. (Most likely both.)
## How to Use

### 1. Clone the Repo

```bash
git clone https://github.com/VihaanSom/git-laughs.git
cd git-laughs
```

### 2. Install the Post-Commit Hook

Copy the provided `post-commit` script into your local repo’s `.git/hooks` directory:

```bash
cp post-commit /path/to/your/project/.git/hooks/
chmod +x /path/to/your/project/.git/hooks/post-commit
```

### 3. Ensure You Have Audio Support

- **Linux:** Make sure you have `aplay`, `paplay`, or `mpv` installed.
- **macOS:** `afplay` should work out of the box.
- **Windows:** Use `PowerShell` or WSL with a compatible audio player.

### 4. Add Your Favorite Sitcom Sounds

Place your `.wav` sound files in the `sounds/` folder, and edit the script to point to your favorites if needed!

### 5. Commit and Enjoy!

```bash
git commit -m "My hilarious change"
```

Listen for an iconic 90's sitcom sound after every commit.  
Coding has never been this fun!

---

🚨 Disclaimer

We’re not responsible if:

Your coworkers stage an intervention.

Your hackathon judges laugh harder at your commits than your project.

You get addicted and start committing code just to hear the laugh track.
