# Starbucks Landing Page Design

A modern, responsive landing page for Starbucks Coffee Company built with HTML, CSS, and JavaScript. This project features an interactive product showcase with dynamic color themes and smooth animations.

## 🎨 Features

### Interactive Elements
- **Dynamic Image Slider**: Click on thumbnail images to change the main product display
- **Color Theme Switching**: Background circle color changes dynamically based on selected product
  - Green (#017143) - Default Starbucks theme
  - Pink (#eb7495) - Second product theme
  - Purple (#d752b1) - Third product theme
- **Responsive Navigation Menu**: Mobile-friendly hamburger menu that transforms on smaller screens
- **Smooth Animations**: Hover effects on thumbnails and interactive elements

### Design Features
- **Modern UI/UX**: Clean, minimalist design with Starbucks brand colors
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Circular Background Decoration**: Dynamic circular shape that adapts to screen size
- **Social Media Integration**: Links to Facebook, Twitter, and Instagram

## 📁 Project Structure

```
Starbucks-landing-page-design/
│
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styling and responsive design
├── img/
│   ├── logo.png        # Starbucks logo
│   ├── img1.png        # Main product image 1
│   ├── img2.png        # Main product image 2
│   ├── img3.png        # Main product image 3
│   ├── thumb1.png      # Thumbnail 1
│   ├── thumb2.png      # Thumbnail 2
│   ├── thumb3.png      # Thumbnail 3
│   ├── menu.png        # Mobile menu icon
│   ├── close.png       # Mobile menu close icon
│   ├── facebook.png    # Facebook icon
│   ├── twitter.png     # Twitter icon
│   ├── instagram.png   # Instagram icon
│   ├── favicon-32x32.webp  # Site favicon
│   └── Attribution.txt # Image attribution file
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Starbucks-landing-page-design.git
   cd Starbucks-landing-page-design
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser, or
   - Use a local development server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (with http-server)
     npx http-server
     ```

3. **View in browser**
   - Navigate to `http://localhost:8000` (if using a server)
   - Or open `index.html` directly in your browser

## 💻 Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: 
  - Flexbox for layout
  - CSS Clip-path for circular background
  - Media queries for responsiveness
  - Custom animations and transitions
- **JavaScript (Vanilla)**: 
  - DOM manipulation
  - Event handling
  - Dynamic style changes

## 🎯 Key Functionality

### JavaScript Functions

1. **`imgslider(anything)`**
   - Updates the main product image when a thumbnail is clicked
   - Parameter: Image path string

2. **`changeCircleColor(color)`**
   - Changes the background circle color dynamically
   - Parameter: Color hex code (e.g., '#017143')

3. **`toggleMenu()`**
   - Toggles the mobile navigation menu
   - Adds/removes 'active' class to menu elements

### CSS Features

- **Responsive Breakpoint**: 991px
  - Desktop: Full navigation menu, side-by-side layout
  - Mobile: Hamburger menu, stacked content layout
- **Custom Font**: Poppins from Google Fonts
- **Smooth Transitions**: 0.5s transition on interactive elements

## 📱 Responsive Design

The page is fully responsive with breakpoints at 991px:
- **Desktop (>991px)**: 
  - Full navigation menu
  - Side-by-side content layout
  - Larger images and text
  - Circular background on the right side

- **Mobile (≤991px)**:
  - Hamburger menu icon
  - Stacked content layout
  - Smaller images and adjusted text sizes
  - Circular background at the bottom center
  - Social media icons in a vertical sidebar

## 🎨 Color Scheme

- **Primary Green**: #017143 (Starbucks brand color)
- **Pink Accent**: #eb7495
- **Purple Accent**: #d752b1
- **Text Color**: #333 (dark gray)
- **Background**: #fff (white)

## 📝 Customization

### Changing Product Images
1. Replace images in the `img/` folder
2. Update image paths in `index.html` (lines 33, 37-39)
3. Ensure thumbnail images match the aspect ratio

### Modifying Colors
1. Update color values in `index.html` onclick handlers (lines 37-39)
2. Update primary color in `css/style.css` (line 64, 75, etc.)

### Adding More Products
1. Add new thumbnail images to `img/` folder
2. Add new `<li>` elements in the thumb list (lines 36-40)
3. Create corresponding main product images
4. Update JavaScript if needed for additional functionality

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Images sourced from [FreePNGImg](https://freepngimg.com/)
- Font provided by [Google Fonts](https://fonts.google.com/)
- Design inspired by Starbucks brand aesthetics

## 📧 Contact

For questions or suggestions, please open an issue on GitHub.

---

**Note**: This is a front-end design project for educational/portfolio purposes. It is not affiliated with or endorsed by Starbucks Coffee Company.

