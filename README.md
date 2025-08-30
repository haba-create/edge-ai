# Edge AI - Spatial Intelligence at the Edge

A cutting-edge website for Edge AI, a startup pioneering spatial computing solutions that run AI locally on edge devices. Our platform processes sensor data and controls actuators in real-time without internet dependency, enabling truly autonomous intelligent systems.

## 🚀 Overview

Edge AI transforms physical spaces with autonomous AI that makes decisions where they matter most - directly on your devices. From industrial automation to smart buildings, we bring intelligence to the edge for instant, reliable, and secure operation.

## ✨ Features

### Design & User Experience
- **Abstract Futuristic Design**: Dark theme with cyan/blue accents, animated grid backgrounds, and floating particles
- **Glass Morphism UI**: Modern glassmorphic components with backdrop blur effects
- **Smooth Animations**: Circuit line animations, gradient shifts, and scroll-triggered reveals
- **Responsive Layout**: Fully optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: Hover effects, animated buttons, and dynamic content loading

### Technical Capabilities Showcased
- **Sensor Fusion**: Multi-modal perception from cameras, LiDAR, IMU, and environmental sensors
- **Local AI Processing**: Sub-10ms inference with hardware acceleration
- **Actuator Control**: Direct control of motors, servos, and IoT devices
- **Offline Operation**: Complete autonomy without cloud dependency

## Technologies Used

- Pure HTML5, CSS3, and JavaScript
- Font Awesome for icons
- Google Fonts (Montserrat & Raleway)
- Edge AI API for chatbot functionality
- CSS animations and transitions for modern effects

## Project Structure

```
edge-ai-website/
│
├── index.html          # Main website file with all code
└── README.md          # This file
```

## Setup Instructions

1. **Clone or download the project files**
   ```bash
   git clone [your-repository-url]
   ```

2. **No additional setup required!**
   - The website is self-contained in a single HTML file
   - All dependencies are loaded from CDNs
   - The chatbot API is already configured

3. **Open in browser**
   - Simply open `index.html` in any modern web browser
   - For development: Use a local server (e.g., VS Code Live Server)

## Chatbot Configuration

The chatbot is configured to use the Edge AI API endpoint:
```
https://app.sensational-ai.space/api/v1/prediction/ab4924ed-4a06-40ff-9f8f-e897ef52fd8a
```

To modify the chatbot behavior, update the configuration in the `query()` function:

```javascript
"overrideConfig": {
    "supervisorName": "Edge AI Assistant",
    "supervisorPrompt": "Your custom prompt here",
    "summarization": true,
    "recursionLimit": 1,
}
```

## Customization

### Changing Colors
Update the CSS variables in the `:root` selector:
```css
:root {
    --primary-color: #000428;    /* Deep navy background */
    --accent-color: #4facfe;     /* Sky blue accent */
    --text-color: #ffffff;       /* White text */
    --secondary-text: #c0c0c0;   /* Light gray text */
}
```

### Modifying Content
- Hero section text can be found in the `<div class="hero-content">` section
- Feature cards are in the `<div class="features-container">` section
- Navigation links are in the `<nav class="nav-links">` section

### Background Image
To change the background image, update the URL in the `.background-image` CSS class:
```css
background-image: url('[your-image-url]');
```

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Optimization

- Uses CSS animations instead of JavaScript for better performance
- Lazy loading for off-screen content
- Optimized font loading with Google Fonts
- Minimal DOM manipulation

## Security Considerations

- All external resources loaded via HTTPS
- API endpoint secured with proper headers
- No sensitive data stored client-side
- Input sanitization for chat messages

## Deployment

The website can be deployed to any static hosting service:

1. **GitHub Pages**
   - Push to a GitHub repository
   - Enable GitHub Pages in settings

2. **Netlify**
   - Drag and drop the HTML file
   - Automatic deployment

3. **Vercel**
   - Connect GitHub repository
   - Auto-deployment on push

4. **Traditional Hosting**
   - Upload HTML file via FTP
   - No server-side requirements

## Troubleshooting

### Chatbot not responding
- Check browser console for errors
- Verify API endpoint is accessible
- Ensure CORS is enabled on the API

### Background image not loading
- Check image URL is correct
- Verify image is publicly accessible
- Clear browser cache

### Animations not working
- Ensure modern browser is being used
- Check for CSS syntax errors
- Disable browser extensions that might interfere

## Future Enhancements

- [ ] Add more interactive features
- [ ] Implement dark/light mode toggle
- [ ] Add more pages (About, Contact, etc.)
- [ ] Integrate analytics
- [ ] Add form submissions
- [ ] Implement newsletter signup

## License

[Your chosen license]

## Contact

[Your contact information]

---

**Note**: This website is optimized for modern browsers and best viewed on desktop or tablet devices.
