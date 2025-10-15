# Arcella Volley Scoreboard

A volleyball scoreboard application for tracking scores, sets, and timeouts during matches.

## Features

- Real-time score tracking for both teams
- Set management with automatic side switching
- Timeout tracking (2 per team per set)
- Point history visualization
- Team name and logo customization
- Local storage persistence
- Confetti celebration when a set is won
- Manual edit mode for adjustments

## Live Demo

Visit the live scoreboard at: **https://flevour.github.io/arcella-scoreboard/**

## GitHub Pages Deployment

This project is configured for automatic deployment to GitHub Pages using GitHub Actions.

### How it works

Every time you push changes to the `main` branch, the site automatically deploys to GitHub Pages. The workflow file at [.github/workflows/deploy.yml](.github/workflows/deploy.yml) handles the deployment.

### One-Time Setup (Already Complete)

To enable GitHub Pages for this repository:

1. Go to **Settings** → **Pages** in your GitHub repository
2. Under "Build and deployment" → "Source", select **GitHub Actions**
3. Save the settings

That's it! Future pushes to `main` will automatically deploy.

## Local Development

Simply open [index.html](index.html) in a web browser. No build process or dependencies required.

## Usage

1. Click team names to edit them
2. Click logos to change them (URL-based)
3. Click the large score numbers or use +/- buttons to adjust scores
4. Use the menu (bottom center) to:
   - End a set (auto-switches sides)
   - Manually switch sides
   - Enable manual edit mode for sets
   - Reset current set or entire match

## Technology

- Pure HTML with inline React (via CDN)
- Tailwind CSS for styling
- localStorage for state persistence
