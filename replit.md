# My Fan Page - HTML/CSS Lab

## Overview
This is a static HTML/CSS educational project designed for students to learn HTML elements and webpage structure by creating a fan page for their favorite TV character, celebrity, historical figure, or role model.

## Project Type
- **Type**: Static Website (HTML/CSS)
- **Framework**: Vanilla HTML/CSS
- **Server**: Node.js with `serve` package
- **Port**: 5000

## Project Structure
```
.
├── index.html          # Main HTML file (starter template)
├── style.css           # CSS styling
├── U1LAB1.md          # Lab instructions and requirements
├── package.json       # Node.js dependencies
└── node_modules/      # Dependencies (gitignored)
```

## Running the Project
The project uses a simple static file server that runs automatically via the configured workflow:
- Command: `npx serve . -l 5000`
- The server serves all files in the current directory on port 5000

## Lab Requirements
Students need to create a fan page that includes:
1. Header/Intro section with name, quote, and picture
2. About Me section describing the person
3. Achievements/Last Seen section with at least 3 nested divs
4. Other section with links to related websites

### HTML Elements Required:
- HTML skeleton (html, head, body)
- At least two header elements (h1, h3, etc)
- At least one paragraph element
- At least one image element
- At least one anchor element
- All elements nested inside body
- Sections encapsulated in divs
- Stretch: Display items as a list

## Deployment
Configured for Replit autoscale deployment (static site hosting).

## Recent Changes
- **2025-10-06**: Initial Replit setup completed
  - Installed Node.js 20
  - Added `serve` package for static file serving
  - Configured workflow to run on port 5000
  - Created .gitignore for Node.js
  - Set up deployment configuration for autoscale
