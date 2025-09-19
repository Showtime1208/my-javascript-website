# Personal Portfolio Website

A modern, responsive personal portfolio website built with vanilla JavaScript, HTML5, and CSS3. This website showcases my background as a Computer Science student at Northeastern University and highlights my interests in cooking, gaming, and sports.

## 🚀 Live Demo

Visit the website at: [Your Live URL Here]

## ✨ Features

- **Responsive Design**: Mobile-first approach with CSS Grid and Flexbox
- **Interactive Elements**: Smooth animations and hover effects
- **Visitor Counter**: Persistent counter using localStorage API
- **Contact Form**: Functional email integration using EmailJS
- **Modern UI/UX**: Clean, professional design with smooth transitions
- **Cross-browser Compatible**: Works on all modern browsers

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Styling**: CSS Grid, Flexbox, CSS Animations
- **Email Service**: EmailJS API
- **Storage**: localStorage API
- **Performance**: requestAnimationFrame for smooth animations

## 📁 Project Structure

```
my-javascript-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- A local web server (Python, Node.js, or any static file server)

### Installation

1. **Clone or download the repository**
   ```bash
   git clone [your-repo-url]
   cd my-javascript-website
   ```

2. **Start a local server**
   
   **Using Python:**
   ```bash
   python3 -m http.server 8000
   ```
   
   **Using Node.js:**
   ```bash
   npx serve .
   ```
   
   **Using PHP:**
   ```bash
   php -S localhost:8000
   ```

3. **Open your browser**
   Navigate to `http://localhost:8000`

## 📧 Contact Form Setup

To enable the contact form functionality, you'll need to set up EmailJS:

### 1. Create EmailJS Account
- Visit [EmailJS.com](https://www.emailjs.com/)
- Sign up for a free account

### 2. Add Email Service
- Go to "Email Services" in your dashboard
- Add Gmail, Outlook, or Yahoo service
- Connect your email account

### 3. Create Email Template
Create a template with these variables:
```
Subject: New Contact Form Message from {{from_name}}

From: {{from_name}} ({{from_email}})
Message:
{{message}}

---
This message was sent from your portfolio website.
```

### 4. Update Configuration
In `script.js`, replace these placeholders:
```javascript
emailjs.init('YOUR_PUBLIC_KEY');  // Your EmailJS public key
emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', templateParams)  // Your service and template IDs
```

## 🎨 Customization

### Personal Information
Update the following in `index.html`:
- Name and title in the hero section
- About section content
- Contact information
- Interests/hobbies

### Styling
Modify `styles.css` to:
- Change color scheme
- Adjust typography
- Update animations
- Modify layout

### Functionality
Enhance `script.js` to:
- Add new interactive features
- Modify animations
- Add additional form validation
- Implement new JavaScript features

## 📱 Responsive Design

The website is fully responsive and optimized for:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

## 🔧 Technical Details

### Performance Optimizations
- CSS animations using `transform` and `opacity` for better performance
- `requestAnimationFrame` for smooth counter animations
- Efficient event delegation
- Optimized image loading

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Key Features Implementation
- **Visitor Counter**: Uses localStorage for persistence and smooth animations
- **Contact Form**: EmailJS integration with validation and error handling
- **Smooth Scrolling**: Custom implementation with offset calculations
- **Mobile Menu**: Hamburger menu with touch-friendly interactions

## 🚀 Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to repository Settings → Pages
3. Select source branch
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Connect your GitHub repository
2. Deploy automatically on push
3. Custom domain support available

### Vercel
1. Import your GitHub repository
2. Automatic deployments
3. Global CDN included

## 📈 Future Enhancements

- [ ] Add dark mode toggle
- [ ] Implement blog section
- [ ] Add project showcase gallery
- [ ] Integrate with Google Analytics
- [ ] Add loading animations
- [ ] Implement PWA features

## 🤝 Contributing

This is a personal portfolio project, but suggestions and improvements are welcome!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Andres Matton-Conover**
- Email: andresmattonconover@outlook.com
- Phone: 908-300-7633
- Location: Boston, MA

---

*Built with ❤️ using vanilla JavaScript, HTML5, and CSS3*
