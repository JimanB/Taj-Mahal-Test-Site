# Taj Mahal Interactive Website

## Overview

An immersive, multimedia-rich website showcasing the Taj Mahal - one of the Seven Wonders of the World and a UNESCO World Heritage Site. This interactive experience combines historical information, multimedia content, and engaging visual elements to tell the story of this architectural masterpiece.

## Features

### Visual Design
- **Gradient Backgrounds**: Multiple layered gradients creating depth and atmosphere
- **Animated Shapes**: Floating geometric elements with CSS animations
- **Gold & White Color Scheme**: Inspired by the Taj Mahal's marble and decorative elements
- **Responsive Layout**: Optimized for all device sizes
- **Custom SVG Logo**: Vector-based Taj Mahal illustration

###  Multimedia Experience
- **Documentary Video**: 40-minute comprehensive documentary (local MP4 file)
- **Audio Tour**: Guided audio experience of the Taj Mahal (local MP3 file)
- **Virtual Tour**: YouTube embedded virtual walkthrough
- **Custom Audio Player**: Full-featured player with progress bar and volume control
- **Image Gallery**: Multiple format showcase (JPEG, PNG, GIF)

###  Educational Content
- **Historical Timeline**: Interactive timeline from 1592 to present
- **Architectural Features**: Detailed explanations of structural elements
- **Image Map**: Interactive diagram with hover information
- **Location Map**: Google Maps integration showing exact location

###  Interactive Elements
- **Hover Callouts**: Informative popups for architectural features
- **Scroll Animations**: Dynamic header effects
- **Music Controls**: Play/pause/volume for audio content
- **Responsive Image Map**: Clickable areas with detailed descriptions

## File Structure

```
taj_mahal/
├── test.html                 # Main website file
├── taj mahal documentary.mp4 # 40-minute documentary video
├── Taj Mahal.mp3            # Audio tour file
├── imagemap.jpg             # Interactive image map diagram
└── README.md               # Project documentation
```

## Technical Implementation

### HTML5 Features
- Semantic HTML structure
- Custom SVG graphics
- Image maps with interactive areas
- Embedded Google Maps
- Video and audio elements

### CSS3 Features
- CSS Grid and Flexbox layouts
- Keyframe animations
- Gradient backgrounds
- Responsive design with media queries
- Custom scroll effects

### JavaScript Functionality
- Custom audio player with progress tracking
- Interactive hover effects
- Scroll-based animations
- Dynamic content display

## Setup Instructions

### Local Deployment
1. Download all project files maintaining the folder structure
2. Ensure all media files are in the same directory as `test.html`:
   - `taj mahal documentary.mp4` (40-minute video)
   - `Taj Mahal.mp3` (audio tour)
   - `imagemap.jpg` (interactive diagram)

3. Open `test.html` in a modern web browser

### Important Notes

#### YouTube Video Issue
**Problem**: The YouTube virtual tour video may not work when accessed locally due to browser security restrictions.

**Solution**: 
- The website includes a direct link to the YouTube video: `https://www.youtube.com/embed/49HTIoCccDY`
- For full functionality, deploy the website to a web server rather than running locally

#### Missing Files
- **taj mahal documentary.mp4**: This file is referenced in the code but wasn't uploaded due to size conflicts with github. The documentary slot on the site this file to be present in the same directory.

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Media Requirements

### Video File
- **Format**: MP4
- **Duration**: 40 minutes
- **Location**: Same directory as HTML file

### Audio File  
- **Format**: MP3
- **Content**: Taj Mahal guided tour
- **Location**: Same directory as HTML file

### Image Files
- **imagemap.jpg**: Required for interactive features
- External images loaded from Unsplash and Giphy

## Customization

### Adding New Content
- Update the timeline section in the HTML
- Add new media cards to the multimedia grid
- Extend the image map with additional areas

### Styling Modifications
- Color scheme variables in CSS
- Animation timing and effects
- Layout breakpoints for responsive design

## Known Issues

1. **Local File Restrictions**: Some browsers block local file access for security
2. **Missing Image Map**: `imagemap.jpg` file required for full functionality
3. **YouTube Embed**: May require web server deployment for proper functionality

## Deployment Recommendations

For optimal performance:
1. Host on a web server (not local file system)
2. Compress large media files for faster loading
3. Use CDN for external resources
4. Implement caching strategies for repeated visits

## Credits

- **Design**: Custom implementation with Mughal architectural inspiration
- **Images**: Unsplash and Giphy for supplemental media
- **Maps**: Google Maps integration
- **Icons**: Font Awesome 6.4.0
- **Fonts**: Google Fonts (Playfair Display, Poppins)

---

*Note: This website is designed as an educational showcase and may require additional optimization for production deployment.*
