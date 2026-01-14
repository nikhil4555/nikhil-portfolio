# Nikhil's Portfolio

A modern, interactive portfolio website showcasing my work as a Software Engineer with expertise in full-stack development.

## About

This portfolio features a sleek, animated design with custom cursor effects, particle backgrounds, and smooth scrolling animations. Built with vanilla JavaScript, HTML5, and CSS3, it demonstrates my skills in creating engaging web experiences.

## Features

- **Custom Cursor**: Interactive cursor with smooth follower animation
- **Particle System**: Dynamic particle background with mouse interaction
- **Typing Animation**: Animated text introduction
- **Smooth Scrolling**: Enhanced navigation with scroll animations
- **Responsive Design**: Fully responsive across all devices
- **Contact Form**: Integrated with EmailJS for direct messaging
- **Animated Illustrations**: Custom CSS-based coding geek illustration
- **Skill Bars**: Animated progress bars showing technical proficiencies
- **Project Showcase**: Featured projects with live links

## Tech Stack

### Frontend
- HTML5
- CSS3 (Custom Properties, Grid, Flexbox)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Inter, JetBrains Mono)

### Backend Integration
- EmailJS for contact form functionality

### Skills Highlighted
- **Frontend**: Angular, JavaScript, TypeScript, CSS3
- **Backend**: Node.js, Java, MongoDB, PostgreSQL
- **Cloud & Tools**: AWS, Docker, Git, Figma

## Projects Featured

1. **KR Techno Hall Ticket System**
   - Hall ticket management system for educational institutions
   - Technologies: HTML, CSS, JavaScript, Node.js, Handlebars, MongoDB
   - [Live Demo](https://krtechnohallticket.onrender.com/)

2. **BidIT - Online Auction Platform**
   - Real-time auction platform with bidding functionality
   - Technologies: Angular, Node.js, Express, MongoDB
   - [GitHub](https://github.com/nikhil4555/BidIT)

## Setup & Installation

1. Clone the repository:
```bash
git clone https://github.com/nikhil4555/nikhil-portfolio.git
```

2. Navigate to the project directory:
```bash
cd nikhil-portfolio
```

3. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

4. Visit `http://localhost:8000` in your browser

## Configuration

### EmailJS Setup
To enable the contact form, update the EmailJS credentials in `script.js`:
```javascript
emailjs.init("YOUR_PUBLIC_KEY");
emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', form)
```

## File Structure

```
nikhil-portfolio/
├── index.html          # Main HTML file
├── style.css           # Styles and animations
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
├── LICENSE             # License file
└── .gitignore          # Git ignore rules
```

## Performance Features

- Optimized particle system with FPS monitoring
- Throttled scroll and resize event handlers
- Lazy loading animations
- Efficient DOM manipulation
- Service Worker ready for PWA capabilities

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contact

- **Email**: nikhilgummadavelly05@gmail.com
- **Location**: Hyderabad
- **GitHub**: [github.com/nikhil4555](https://github.com/nikhil4555)
- **LinkedIn**: [linkedin.com/in/nikhilgummadavelly](https://www.linkedin.com/in/nikhilgummadavelly/)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- EmailJS for contact form integration

---

**Note**: This portfolio is continuously updated with new projects and improvements. Feel free to reach out for collaborations or opportunities!
