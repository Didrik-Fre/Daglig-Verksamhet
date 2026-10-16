# GIT CHEAT SHEET
## My Daglig-Verksamhet Project

My GitHub repository:
https://github.com/Didrik-Fre/Daglig-Verksamhet

**GitHub connects my Mac and Windows PC.**

---

# 1. START WORKING

Before I start coding, open my project in VS Code.

Open the terminal and type:

```bash
git pull
```

**What does this do?**

Downloads the latest changes from GitHub.

Now I can start coding!

---

# 2. SAVE MY WORK TO GITHUB

When I have finished coding, run these commands **one at a time**.

### Step 1 — Check my changes

```bash
git status
```

### Step 2 — Prepare my files

```bash
git add .
```

### Step 3 — Save my changes

```bash
git commit -m "Describe my changes"
```

Example:

```bash
git commit -m "Add new HTML page"
```

### Step 4 — Upload to GitHub

```bash
git push
```

**Done! My changes are now on GitHub.**

---

# 3. SWITCH BETWEEN COMPUTERS

## Mac → Windows

**On my Mac:**

```bash
git add .
git commit -m "Describe my changes"
git push
```

**On Windows:**

```bash
git pull
```

## Windows → Mac

**On Windows:**

```bash
git add .
git commit -m "Describe my changes"
git push
```

**On my Mac:**

```bash
git pull
```

**Remember:**
- `git push` = Send changes to GitHub.
- `git pull` = Get changes from GitHub.

---

# 4. COMMANDS I SHOULD KNOW

| Command | What it does |
|---|---|
| `git status` | Shows what has changed |
| `git pull` | Downloads changes |
| `git add .` | Prepares changed files |
| `git commit -m "message"` | Saves a snapshot |
| `git push` | Uploads changes |
| `git log --oneline -5` | Shows my last 5 commits |

---

# 5. IF SOMETHING GOES WRONG

### "Nothing to commit"

There are no new changes for Git to commit.

### "Everything up-to-date"

There are no new commits waiting to be uploaded.

### Git shows an error

**Stop and read the error.** Do not run random commands.

If I do not understand the error, I can copy it and ask for help.

---

# 6. MY SIMPLE DAILY ROUTINE

**When I start working:**

```bash
git pull
```

Then I write and save my code.

**When I finish working:**

```bash
git status
git add .
git commit -m "Describe my changes"
git push
```

---

## THE MOST IMPORTANT THING

**Before working:** `git pull`

**After working:** `git add .` → `git commit` → `git push`

GitHub keeps my Mac and Windows PC connected!