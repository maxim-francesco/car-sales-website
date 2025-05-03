# Car Sales Website

A fully responsive car sales website built as part of the **Tailwind CSS v4 From Scratch Beginner To Pro** course on Udemy. This project showcases modern web development techniques using **Tailwind CSS v4**, featuring a dynamic navigation bar, car listing cards, a testimonial section, and a contact form.

## ✨ Features
- **Responsive Navigation Bar**: Adapts seamlessly across devices with a mobile-friendly hamburger menu.
- **Site Banner**: Full-width banner with a background image, centered text, and call-to-action buttons.
- **Car Listings**: Grid-based card components displaying car images and details, responsive across breakpoints.
- **Testimonial Section**: Card-based layout for client testimonials, optimized for mobile and desktop.
- **Contact Form**: Accessible and styled form with input validation and responsive design.
- **Footer**: Multi-column footer with social media links and navigation.

## 🛠️ Technologies Used
- **HTML5**: Semantic markup for structure.
- **Tailwind CSS v4**: Utility-first CSS framework for styling.
- **JavaScript**: Basic interactivity (e.g., hamburger menu toggle).
- **Node.js & npm**: For Tailwind CSS setup and build process.

## 🚀 Getting Started

### Prerequisites
- **Node.js** and **npm** installed on your machine.
- A modern web browser (e.g., Chrome, Firefox).

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/maxim-francesco/car-sales-website.git
   cd car-sales-website
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Build Tailwind CSS**:
   ```bash
   npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
   ```

4. **Run the project**:
   - Open `index.html` in a browser, or use a local server (e.g., `npx serve` or VS Code Live Server).

## 📖 Project Structure
```
car-sales-website/
├── src/
│   ├── input.css        # Tailwind CSS input file
    └── images/          # Project assets (car images, etc.)
    └── output.css       # Compiled Tailwind CSS
    └── style.css        # Extra CSS File
    └── index.html       # Main HTML file
├── node_modules/        # Node Modules
├── package.json         # Node.js dependencies
├── package-lock.json    # Node.js dependencies
├── .gitignore           # Git ignore file
└── README.md            # This file
```

## 🌟 What I Learned
- Applied **Tailwind CSS v4** utility classes to create responsive, modern layouts.
- Mastered **Flexbox** and **Grid** for dynamic component placement.
- Implemented responsive design with Tailwind’s breakpoint utilities (e.g., `sm:`, `md:`, `lg:`).
- Styled interactive elements with hover, focus, and active states.
- Configured and optimized Tailwind CSS with JIT mode for efficient builds.

## 🔗 Live Demo
[[View the live demo here](https://maxim-francesco.github.io/car-sales-website/index.html)]

## 🙌 Acknowledgments
- Thanks to **Ashutosh Pawar** for the excellent **Tailwind CSS v4 From Scratch Beginner To Pro** course.
- Inspired by modern car sales websites for design and functionality.

## 📬 Contact
- **GitHub**: [Maxim Francesco](https://github.com/maxim-francesco)
- **LinkedIn**: [Maxim Francesco](https://www.linkedin.com/in/francescomaxim/)
- **Email**: [maaximfrancesco@gmail.com]

Feel free to explore the code and provide feedback! 🚗
