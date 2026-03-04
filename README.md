# Omada Leadership Hub Builder

A guided wizard that helps leaders at Omada Health create personalized AI instructions for their Perplexity Space.

## What it does

Walks users through 8 steps to define their leadership context, communication style, values, and working preferences. Outputs a complete instructions block (≤5,000 characters) ready to paste into a Perplexity Space.

## Features

- **90% guided selections** — chip-based inputs minimize typing
- **Grouped options** — voice traits, banned words, focus areas organized by category
- **Live preview** — see your profile building in real time
- **Character budget** — live counter ensures output fits Perplexity's 5,000 char limit
- **Section editing** — review screen lets you jump back to any section
- **Inline coaching** — contextual guidance at each step
- **Mobile-friendly** — responsive layout, touch-optimized targets

## How to use

### Option 1: Direct file sharing
Download `index.html` and open it in any browser. No build tools, no dependencies.

### Option 2: GitHub Pages (recommended for sharing)
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch**, select `main`, select `/ (root)`
4. Save — your site will be live at `https://[your-username].github.io/[repo-name]/`
5. Share that URL with your team

## Tech

Single HTML file. No framework, no build step, no external dependencies beyond Google Fonts. Runs entirely in the browser — no data is sent anywhere.

## Output

The wizard generates a plaintext instructions block structured for Perplexity Spaces:
- Role and context
- Three operating modes (Analyst, Advisor, Assistant)
- Voice and style preferences
- Leadership values and constraints
- Focus areas
- Personal defaults (stress patterns, decision style, conflict approach)
- Optional unique touches

Users copy the output and paste it into their Perplexity Space instructions field.
