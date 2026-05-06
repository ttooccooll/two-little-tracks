# Artist Website Specification

## Project Overview
- **Project Name**: Two Little Tracks - Electronic Music Artist
- **Type**: Single-page artist website
- **Core Functionality**: Showcase electronic music artist with audio player, bio, and visual identity
- **Target Users**: Fans, promoters, label representatives

## UI/UX Specification

### Layout Structure
- **Header**: Fixed navigation with artist name and nav links
- **Hero**: Full-viewport section with artist image as background, artist name
- **Music Section**: Audio player for tracks with track list
- **About Section**: Artist biography
- **Contact Section**: Links to social media/booking
- **Footer**: Copyright and minimal info

### Responsive Breakpoints
- Mobile: < 768px
- Desktop: >= 768px

### Visual Design

#### Color Palette
- **Background**: #0a0a0a (deep black)
- **Primary Text**: #f0f0f0 (off-white)
- **Accent**: #00ff88 (electric green)
- **Secondary**: #1a1a1a (dark gray)
- **Muted Text**: #666666

#### Typography
- **Primary Font**: "Syne", sans-serif (from Google Fonts)
- **Secondary Font**: "Space Mono", monospace (from Google Fonts)
- **Hero Title**: 6rem desktop, 3rem mobile, font-weight 800
- **Section Titles**: 2rem, font-weight 700
- **Body**: 1rem, font-weight 400

#### Spacing
- Section padding: 100px vertical
- Container max-width: 1200px
- Standard gap: 2rem

#### Visual Effects
- Image has subtle green glow/overlay
- Buttons have neon green hover glow
- Smooth scroll behavior
- Track items have hover highlight
- Audio player styled with accent color

### Components

#### Navigation
- Artist name (left)
- Nav links: Music, About, Contact (right)
- Transparent background, becomes solid on scroll (optional)
- Mobile: hamburger menu

#### Hero Section
- Full viewport height
- Image as background with dark overlay
- Artist name centered
- Tagline: "Electronic Music"
- Scroll indicator

#### Music Player
- Track list with:
  - Track title
  - Duration
  - Play/pause button per track
- Visual feedback for playing track
- Uses Web Audio API or HTML5 audio

#### About Section
- Two-column layout (image + text)
- Short bio paragraph
- Equipment/influences list

#### Contact Section
- Social links as icons/text
- Email contact
- Booking info

## Functionality Specification

### Core Features
1. **Audio Playback**: Play/pause individual tracks, only one plays at a time
2. **Smooth Scroll**: Navigation links scroll to sections
3. **Responsive Design**: Works on all devices
4. **Visual Feedback**: Shows which track is playing

### User Interactions
- Click track to play/pause
- Click nav link to smooth scroll
- Hover effects on interactive elements

### Edge Cases
- Handle audio loading errors gracefully
- Pause one track when another starts

## Acceptance Criteria
1. Page loads with image displayed prominently
2. Both audio tracks are playable
3. Navigation scrolls to correct sections
4. Site is responsive on mobile
5. Visual design matches spec colors/fonts
6. All hover effects work