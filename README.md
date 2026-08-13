# Scoop Bucket

Personal Scoop bucket for Windows applications.

## Usage

```powershell
scoop bucket add hayden-bucket https://github.com/hayden-cn/scoop-bucket
scoop install hayden-bucket/<app>
```

Replace the repository URL with your fork URL if this bucket is hosted under a different account.

## Structure

- `bucket/`: Scoop manifests.
- `bin/`: helper scripts for testing, formatting, URL checks, hash checks, and version checks.
- `deprecated/`: manifests kept for reference after deprecation.
- `scripts/`: package-specific helper scripts.
- `.github/workflows/`: CI, issue, pull request, and update automation.

If any manifest infringes rights or should be removed, please open an issue.
