# Buy or Bye Project Rules

## GitHub Auto-Backup & Deploy Policy
- Whenever you modify code or configuration files in this project (`d:\Naver MYBOX\내 문서\09. 개인\Business\APP\App General\buy_or_bye`), after running your verification checks, **automatically commit and push to `origin main`** (`https://github.com/crengineer86-dot/buy-or-bye.git`) without waiting for an extra request from the user.
- Before staging (`git add`), verify via `git status --short` that temporary files, logs, or secrets are not staged (respect `.gitignore`).
- Use `C:\Program Files\Git\cmd\git.exe` (or `git` on `PATH`) to run `git add`, `git commit`, and `git push origin main`.
- Summarize the commit hash and confirm the push result in your final response. (Note: pushing to `main` automatically updates GitHub Pages and triggers the `.github/workflows/build-apk.yml` APK build.)
