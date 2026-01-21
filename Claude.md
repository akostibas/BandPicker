# Claude Instructions for BandPicker Project

This file contains persistent commands and preferences for working on this project.

## Workflow Rules

1. **After every code change**: Commit and push to GitHub immediately
   - Repository: git@github.com:akostibas/BandPicker.git
   - Branch: main

2. **Before every push**: Increment the minor version number
   - Update in 3 places:
     - HTML title tag: `<title>BandPicker X.X - MUSIC SKYNET</title>`
     - Version display: `<div class="version">vX.X</div>`
     - Commit message: Start with `vX.X - `
   - Current version: v1.8

3. **Update this file**: When given new special commands or project rules, update this Claude.md file to persist them

## Project Info

- **Project Name**: BandPicker 1.0 (aka MUSIC SKYNET)
- **Purpose**: Band selection tool for Instant Band Night
- **Tech Stack**: Single HTML file with inline CSS/JS
- **Deployment**: GitHub Pages at https://akostibas.github.io/BandPicker/bandpicker.html

## Version History

- v1.0 - Initial prototype
- v1.1 - Instrument specification for Misc bucket
- v1.2 - Data persistence via localStorage
- v1.3 - Version numbering
- v1.4 - Added Claude.md for persistent instructions
- v1.5 - Improved tab contrast and readability
- v1.6 - Rock-and-roll visual styling with dark gradient background
- v1.7 - Improved error messaging for manual member selection
- v1.8 - Added Safari compatibility for backdrop-filter
