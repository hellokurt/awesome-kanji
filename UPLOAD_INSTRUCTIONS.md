# Upload Instructions

## Option 1: Upload via GitHub website

1. Create a new GitHub repository, for example `awesome-kanji`.
2. Upload these files into the repository root:
   - `README.md`
   - `LICENSE`
   - `CONTRIBUTING.md`
   - `.gitignore`
3. Commit the files.
4. GitHub will automatically render `README.md` on the repository homepage.

## Option 2: Push from terminal

```bash
git init
git add README.md LICENSE CONTRIBUTING.md .gitignore
git commit -m "Add awesome kanji resources"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/awesome-kanji.git
git push -u origin main
```
