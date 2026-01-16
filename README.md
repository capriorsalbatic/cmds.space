# cmds.space

A collection of useful command-line scripts and tools accessible at [cmds.space](https://cmds.space).

## Cloudflare Pages Deployment Configuration

This repository is configured to deploy to **Cloudflare Pages** (not Cloudflare Workers).

### Cloudflare Pages Settings

When configuring the Cloudflare Pages project, use the following settings:

- **Build command**: *(leave empty)*
- **Build output directory**: `/`
- **Root directory**: *(leave empty)*
- **Deploy command**: *(remove/leave empty)*
- **Framework preset**: None

### What Gets Deployed

The repository contains static HTML files and shell scripts that are served directly. The `.cfignore` file ensures that only the necessary files are deployed to Cloudflare Pages, excluding:

- `.git/` directory and git-related files
- `.github/` directory
- `.wrangler/` directory
- `node_modules/`
- Configuration files (wrangler.jsonc, .gitignore, .cfignore, README.md)

### Files in This Repository

- `index.html` - Main landing page
- `linuxinit` - Linux initialization script
- `macinit` - macOS initialization script
- `wininit` - Windows initialization script
- `windebloat` - Windows debloat script
- `map` - System mapping utility

## Usage

Visit [cmds.space](https://cmds.space) to access the scripts and tools.
