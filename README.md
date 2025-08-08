# K_Culture_Hub

A# KoreaVerse - Discover Korean Culture



## Project Overview <a name="project-overview"></a>
KoreaVerse is a comprehensive website dedicated to showcasing the richness of Korean culture. From traditional heritage to modern K-Pop, this platform offers an immersive experience into all aspects of Korean culture. The project features a responsive design with beautiful animations and a carefully crafted color scheme inspired by traditional Korean aesthetics.

## Features <a name="features"></a>
- **Responsive Design**: Works seamlessly on mobile, tablet, and desktop devices
- **Modern UI/UX**: Clean, intuitive interface with smooth animations
- **Cultural Showcase**: Dedicated sections for traditional culture, cuisine, K-Pop, and language
- **Interactive Elements**: Hover effects, animated cards, and scroll-triggered animations
- **Korean-inspired Color Scheme**: Peach, orange, and red tones reflecting Korean aesthetics
- **Performance Optimized**: Fast loading times with optimized assets
- **Contact System**: Complete contact form with Google Maps integration

## Pages Structure <a name="pages-structure"></a>
```
koreaverse/
├── index.html               # Homepage
├── about.html               # About KoreaVerse page
├── pages/
│   ├── culture.html         # Traditional Korean culture
│   ├── food.html            # Korean cuisine section
│   ├── kpop.html            # K-Pop and entertainment
│   └── learn.html           # Korean language learning
├── assets/
│   ├── css/
│   │   └── styles.css       # Main stylesheet
│   ├── js/
│   │   └── main.js          # JavaScript functionality
│   └── images/              # All project images
└── README.md                # Project documentation
```

## Technologies Used <a name="technologies-used"></a>
- **Frontend**: HTML5, CSS3, JavaScript
- **CSS Framework**: [Tailwind CSS](https://tailwindcss.com/)
- **Icons**: [Font Awesome](https://fontawesome.com/)
- **Fonts**: [Google Fonts](https://fonts.google.com/)
- **Animations**: Custom CSS animations and transitions
- **Maps**: Google Maps API
- **Design Tools**: Figma (for initial mockups)

## Installation <a name="installation"></a>
To run KoreaVerse locally, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/yourusername/koreaverse.git
```

2. Navigate to the project directory:
```bash
cd koreaverse
```

3. Install live server (if needed):
```bash
npm install -g live-server
```

4. Start the development server:
```bash
live-server
```

The site will open in your default browser at `http://localhost:8080`

## Usage <a name="usage"></a>
1. Browse through the different sections using the navigation menu
2. Hover over cards to see interactive effects
3. Scroll down to trigger animations as content comes into view
4. Use the contact form to send inquiries
5. Explore Korean locations using the embedded map

## Customization <a name="customization"></a>
To customize KoreaVerse:

1. **Change Colors**: Modify the color palette in `tailwind.config.js`
```js
theme: {
  extend: {
    colors: {
      'peach-light': '#FFF5EE',
      'peach-primary': '#FFDAB9',
      'korean-red': '#CD1818',
      // Add your custom colors
    }
  }
}
```

2. **Update Content**: Edit HTML files to change text and images
3. **Add Pages**: Create new HTML files in the `pages` directory
4. **Modify Animations**: Adjust keyframes in the `<style>` section
```css
@keyframes fadeInDown {
  '0%': { opacity: '0', transform: 'translateY(-30px)' },
  '100%': { opacity: '1', transform: 'translateY(0)' },
}
```

5. **Update Map Location**: Replace the Google Maps embed URL with your preferred location

## Contributing <a name="contributing"></a>
Contributions are welcome! To contribute to KoreaVerse:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please ensure your code follows the existing style and includes appropriate documentation.

## License <a name="license"></a>
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact <a name="contact"></a>
For questions or support, please contact:

- **Project Lead**: Min-Ji Park
- **Email**: contact@koreaverse.com
- **Website**: [www.koreaverse.com](https://www.koreaverse.com)

---

**Experience the beauty of Korea with KoreaVerse - Where tradition meets innovation!** 