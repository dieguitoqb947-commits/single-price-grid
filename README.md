# Single Price Grid Component

This is a responsive pricing card component built from a challenge on [Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). The component showcases a modern, professional approach to displaying subscription pricing information with a clear value proposition.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Features](#features)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Installation & Setup](#installation--setup)
- [Project Structure](#project-structure)
- [Key Learnings](#key-learnings)
- [Author](#author)

## Overview

### The Challenge

The objective was to build a pricing card component that:

- **Display pricing information** clearly with subscription cost and monthly billing
- **Show a list of benefits** that justify the subscription value
- **Include an interactive Sign Up button** with hover state effects
- **Use a clear visual hierarchy** to organize information effectively
- **Apply semantic HTML structure** with proper heading organization

### Features

✅ **CSS Grid Layout** - Two-column grid layout for pricing and benefits display  
✅ **Professional Color Scheme** - Teal headings, yellow accent text, and neutral typography  
✅ **Custom Typography** - Uses Google Fonts (Karla) for modern appearance  
✅ **Interactive Elements** - Sign Up button with hover effects  
✅ **Visual Benefits List** - Clearly itemized subscription advantages  
✅ **Semantic HTML** - Proper use of heading hierarchy and semantic tags  
✅ **CSS Grid & Flexbox** - Modern layout techniques

## Screenshots

**Desktop Design**
![Desktop Design](./design/desktop-design.jpg)

**Mobile Design**
![Mobile Design](./design/mobile-design.jpg)

## Technologies Used

- **HTML5** - Semantic markup with proper heading hierarchy
- **CSS3** - Grid layout, Flexbox, Transitions, and Transforms
- **Google Fonts** - Karla font family for typography

## Installation & Setup

1. **Clone or download the repository**

   ```bash
   git clone <repository-url>
   cd single-price-grid-component
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser
   - No build tools or dependencies required

3. **View the component**
   - Open the `index.html` file in your browser
   - The component displays as a 2-column grid layout

## Project Structure

```
single-price-grid-component/
├── index.html              # Main HTML file with semantic structure
├── styles/
│   └── style.css          # All styling (Grid, Flexbox, Media queries)
├── images/
│   ├── favicon-32x32.png  # Browser favicon
│   └── v748-toon-106.jpg  # Background image
├── design/
│   ├── desktop-design.jpg # Desktop layout reference
│   └── mobile-design.jpg  # Mobile layout reference
└── README.md              # This file
```

## Key Learnings

- **CSS Grid Implementation** - Creating multi-column layouts with `grid-template-columns`
- **CSS Flexbox** - Using Flexbox for component interior layouts and centering
- **BEM Naming Convention** - Organizing CSS classes using Block Element Modifier methodology
- **Semantic HTML** - Using `<section>`, `<header>`, `<aside>` for meaningful document structure
- **CSS Transitions & Transforms** - Button hover effects with color change and scale transform
- **Typography Hierarchy** - Creating visual distinction through color, size, and weight

### Color Palette

- **Primary Teal**: `hsl(179, 62%, 43%)` - For main headings
- **Accent Yellow**: `hsl(71, 73%, 54%)` - For highlights and important values
- **Text Gray**: `hsl(218, 22%, 67%)` - For body text
- **Background**: White with overlay background image

## Author

**Diego Quevedo**  
Frontend development enthusiast currently improving skills through Frontend Mentor challenges.

---

## Contributing

This is a personal challenge project. However, if you have suggestions for improvements or found any issues, feel free to open an issue or submit feedback.

## License

This project is open source and available under the MIT License.

## Resources Used

- [Frontend Mentor](https://www.frontendmentor.io/) - Challenge platform
- [Google Fonts](https://fonts.google.com/) - Karla typeface
- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - Layout reference
- [MDN Web Docs](https://developer.mozilla.org/) - HTML & CSS documentation
