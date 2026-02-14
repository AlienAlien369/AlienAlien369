# 🛠️ GitHub Profile Setup Guide

## Prerequisites
- GitHub account
- Repository named exactly as your username: `your-username/your-username`
- Repository must be **public**

## Setup Steps

### 1. Create Profile Repository
1. Create new repository named exactly as your GitHub username
2. Make it public
3. Initialize with README

### 2. Enable GitHub Actions
1. Go to Settings → Actions → General
2. Select "Allow all actions and reusable workflows"
3. Save changes

### 3. Configure Snake Animation
1. Create `.github/workflows/snake.yml`
2. Copy the workflow code provided
3. Replace `Lakshya-Grover` with your username in README.md

### 4. First Run
1. Go to Actions tab
2. Click "Generate Snake Animation"
3. Click "Run workflow"
4. Wait 2-3 minutes for completion

### 5. Verify Output
Check that `output` branch is created with snake files.

## Common Issues

### Snake not appearing?
- Ensure workflow has run at least once
- Check Actions tab for errors
- Verify `output` branch exists

### Stats not loading?
- GitHub API rate limits may apply
- Try self-hosting stats if public instance is down
- Check username spelling in URLs

### Images broken?
- Some GIFs are hosted on user-images.githubusercontent.com
- Consider downloading and hosting in your repo's `assets` folder

## Customization

### Change Theme Colors
Modify `theme` parameter in stats URLs:
- `tokyonight` (current)
- `radical`
- `merko`
- `gruvbox`
- `dark`

### Add WakaTime Stats
1. Sign up at [wakatime.com](https://wakatime.com)
2. Get API key from settings
3. Add to repository secrets: `WAKATIME_API_KEY`
4. Uncomment WakaTime section in README

## Need Help?
- [GitHub Profile README Docs](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)
- [Snake Animation Repo](https://github.com/Platane/snk)
