# LoveNotes MVP

## Project Overview
A simple, romantic web application that helps users send thoughtful notes, poems, and sayings to their partners. The app gamifies relationship nurturing through streaks, milestones, and curated content.

## Architecture
- **Type**: Static single-page application (SPA)
- **Tech Stack**: 
  - Pure HTML/CSS/JavaScript (no build process)
  - Tailwind CSS (CDN)
  - Font Awesome icons (CDN)
- **Data Storage**: Browser localStorage
- **No Backend**: All functionality runs client-side

## Project Structure
```
/
├── index.html          # Main application file (complete SPA)
└── replit.md          # This documentation file
```

## Features
- Daily love note suggestions (text, poems, sayings, memes, images)
- Personalization (partner name, interests)
- Streak tracking
- Journey/milestone system
- Free tier (7 notes/cycle) + Premium tier concept
- WhatsApp integration for sharing

## Setup Details
- Serves static HTML on port 5000
- No dependencies to install
- No build process required
- Uses browser-based Web Share API and clipboard API

## Recent Changes
- **2025-11-07**: Initial import from GitHub, configured for Replit environment
