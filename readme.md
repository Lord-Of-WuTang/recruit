# Moka Recruitment Website

A clean, responsive recruitment form for Team Moka built with HTML5 and CSS3.

## 📋 Overview

This is a simple yet elegant recruitment website that allows potential team members to apply for various positions at Team Moka. The form collects essential information including personal details, position preferences, availability, and a personal message.

## 🚀 Features

- **Clean, Modern Design**: Professional appearance suitable for recruitment
- **Responsive Form**: Works well on desktop and mobile devices
- **Multiple Position Options**: Frontend Developer, Backend Developer, UI/UX Designer
- **Availability Selection**: Full-time or part-time options
- **Form Validation**: Built-in HTML5 validation for required fields
- **Accessible**: Proper form labels and semantic HTML structure

## 📁 Project Structure

```
moka-recruitment/
├── index.html          # Main HTML file
├── styles.css          # CSS styling (referenced but not included)
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and form elements
- **CSS3**: Styling (external stylesheet)
- **No JavaScript**: Pure HTML/CSS implementation

## 📝 Form Fields

The recruitment form includes:

1. **Full Name** (required text input)
2. **Email Address** (required email input with validation)
3. **Position Selection** (required dropdown with options):
   - Frontend Developer
   - Backend Developer
   - UI/UX Designer
4. **Availability** (required radio buttons):
   - Full-Time
   - Part-Time
5. **Personal Message** (required textarea for applicant information)

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- A web server (optional, for local development)

### Installation

1. Clone or download the project files
2. Ensure you have both `index.html` and `styles.css` in the same directory
3. Open `index.html` in your web browser

### Local Development

For local development with live reloading:

```bash
# Using Python
python -m http.server 8000

# Using Node.js 
npx http-server

# Or simply open index.html directly in your browser
```

## 🎨 Customization

### Styling
- Modify `styles.css` to change colors, fonts, and layout
- The form uses semantic HTML classes for easy styling

### Adding New Positions
To add new job positions, edit the select element in `index.html`:

```html
<option value="new-role">New Role Title</option>
```

### Form Handling
Currently, the form doesn't have backend processing. To make it functional:

1. Add a `action` attribute to the form element
2. Set up server-side processing (PHP, Node.js, etc.)
3. Or integrate with a form service (Formspree, Netlify Forms, etc.)

## 📱 Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+



## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Support

For questions or support regarding this recruitment form, please contact Team Moka.

---

**Team Moka** - Building amazing things together! 🚀