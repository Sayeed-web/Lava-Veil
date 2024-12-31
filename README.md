LavaVeil CSS Framework

LavaVeil is a modern, feature-rich CSS framework designed to simplify web development while providing flexibility, performance, and ease of customization. It aims to rival and surpass existing CSS frameworks by blending comprehensive utility classes, responsive features, accessibility improvements, and modern design components. This project delivers a robust foundation for developers to create stunning and user-friendly web applications.

🌐 Website: LavaVeil Official Website

http://lava-veil.infy.uk


Key Features
Utility Classes

LavaVeil introduces a wide array of utility classes to enable rapid prototyping and customization without writing additional CSS. Examples include:

    Spacing utilities: u-p-0, u-m-1, etc.
    Flexbox utilities: u-d-flex, u-flex-column, etc.
    Text alignment utilities: u-text-left, u-text-center, etc.

Responsive Grid System

A highly customizable grid system supports fractional layouts and ensures consistent designs across various screen sizes. Example classes:

    u-grid-1-3
    u-grid-2-4

Effortlessly create responsive, complex layouts.
Dark Mode and Theming

LavaVeil uses CSS variables for seamless theming. Switch between light and dark modes or customize colors to match your brand.

.theme-dark {
  background-color: var(--dark-bg);
  color: var(--light-bg);
}

Animation Utilities

Built-in animations allow dynamic effects without external libraries:

    u-fade-in
    u-bounce

Example:

@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

Accessibility Enhancements

Adheres to WCAG 2.1 standards with features like:

    Focus-visible outlines for keyboard navigation.
    ARIA role-based styling for elements like alerts.

Typography System

A scalable typography system ensures consistency with classes like:

    u-fs-1 (font size)
    u-fw-bold (font weight)

Buttons and States

Includes versatile button options such as gradient buttons, hover states, and rounded options.

Example:

.u-btn-gradient {
  background: linear-gradient(45deg, #ff6f61, #d84315);
  color: #fff;
  padding: 10px 20px;
}

Modern Components

LavaVeil includes a suite of modern components:

    Modals: Elegant, customizable modal windows.
    Cards: Flexible cards with hover effects.
    Pagination: Stylish and responsive pagination.
    Badges: Informative badges for alerts or notifications.

Predefined Color Schemes

Provides background and text color classes inspired by material design principles:

    bg-blue, text-red, etc.

Custom Sidebar and Navigation Systems

Responsive side navigation menus and navbar components to organize content effectively.
Why Choose LavaVeil?

    Scalability: Designed to grow with your project.
    Performance: Optimized for speed and minimal resource usage.
    Accessibility: Ensures usability for everyone.
    Ease of Use: Simple class naming conventions and detailed documentation.

Getting Started
Installation

🌐 Website: LavaVeil Official Website
http://lava-veil.infy.uk


Usage

Link the CSS file in your HTML:

<link rel="stylesheet" href="lavaveil.css">

Customization

Modify :root variables to customize the theme:

:root {
  --primary-color: #007bff;
  --dark-bg: #343a40;
  --light-bg: #f8f9fa;
}

Project Structure

    lavaveil.css: Main CSS framework file.
    examples/: Example HTML files demonstrating framework usage.
    README.md: Documentation for installation and usage.
