# Puspharaj M - Portfolio

<div align="center">

[Visit my Robotics & AI Engineer Portfolio](https://puspharajm2003.github.io/Portfolio-1/)



**A modern, responsive portfolio showcasing expertise in Robotics, AI, and Full-Stack Development**

[![Live Demo](https://img.shields.io/badge/Live_Demo-View_Portfolio-0ea5e9?style=for-the-badge&logo=github)](https://puspharajm2003.github.io/portfolio/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

</div>

## 🚀 Quick Preview

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Puspharaj M - Robotics & AI Engineer | Full-Stack Developer</title>
    <!-- Modern portfolio with gradient design and interactive elements -->
</head>
<body class="bg-slate-50 text-slate-700">
    <!-- Professional Hero Section -->
    <header class="card-responsive bg-gradient-to-br from-slate-800 to-slate-900 text-white">
        <div class="flex flex-col md:flex-row items-center gap-6 md:gap-8">
            <!-- Profile Image -->
            <img src="profile.jpg" alt="Puspharaj M" class="rounded-full border-4 border-slate-600">
            
            <!-- Profile Info -->
            <div class="flex-1 text-center md:text-left">
                <h1 class="text-responsive-xl font-extrabold mb-2">Puspharaj M</h1>
                <div class="text-responsive-lg text-sky-300 font-medium mb-4 md:mb-6">
                    <span id="typewriter-text">Robotics & AI Engineer | Full-Stack Developer</span>
                </div>
                
                <!-- Social Links -->
                <div class="flex justify-center md:justify-start space-x-4 md:space-x-6">
                    <a href="#" class="text-slate-300 hover:text-white"><i class="fab fa-linkedin"></i></a>
                    <a href="#" class="text-slate-300 hover:text-white"><i class="fab fa-github"></i></a>
                    <a href="#" class="text-slate-300 hover:text-white"><i class="fas fa-globe"></i></a>
                </div>
            </div>
            
            <!-- Download PDF Button -->
            <button onclick="downloadPDF()" class="bg-sky-500 hover:bg-sky-600 text-white py-3 px-6 rounded-full">
                <i class="fas fa-download"></i> Download as PDF
            </button>
        </div>
    </header>
</body>
</html>
```

## 📱 Features Overview

| Feature | Description | Code Snippet |
|---------|-------------|--------------|
| **Typewriter Effect** | Animated text introduction | `typewriter-text` with CSS animations |
| **Responsive Design** | Mobile-first approach | Tailwind CSS + custom media queries |
| **PDF Export** | One-click resume download | `html2pdf.js` integration |
| **Smooth Animations** | Scroll-triggered effects | AOS library implementation |
| **Timeline Layout** | Professional experience display | Custom CSS timeline components |

## 🛠️ Technical Implementation

### Core Structure
```html
<!-- Main Grid Layout -->
<div class="grid grid-cols-1 lg:grid-cols-3 gap-6 md:gap-8">
    <!-- Left Column - Main Content -->
    <div class="lg:col-span-2 space-y-6 md:space-y-8">
        <!-- About, Experience, Projects Sections -->
    </div>
    
    <!-- Right Column - Sidebar -->
    <div class="space-y-6 md:space-y-8 lg:sticky lg:top-8">
        <!-- Contact, Skills, Languages Sections -->
    </div>
</div>
```

### Responsive Timeline
```html
<!-- Desktop Timeline -->
<div class="timeline-item">
    <div class="timeline-dot"></div>
    <h4 class="text-lg font-semibold text-sky-700">Robotics Engineer</h4>
    <span class="text-sm text-gray-500">Apr 2025 - Aug 2025</span>
    <p class="text-md text-gray-700">VTS</p>
</div>

<!-- Mobile Timeline -->
<div class="timeline-mobile">
    <div class="timeline-item-mobile">
        <h4 class="text-lg font-semibold text-sky-700">Robotics Engineer</h4>
        <span class="text-sm text-gray-500">Apr 2025 - Aug 2025</span>
        <p class="text-md text-gray-700">VTS</p>
    </div>
</div>
```

### Skills Display
```html
<div class="flex flex-wrap gap-2">
    <span class="bg-sky-50 text-sky-700 text-sm font-medium px-2 py-1 rounded">
        Artificial Intelligence
    </span>
    <span class="bg-sky-50 text-sky-700 text-sm font-medium px-2 py-1 rounded">
        Machine Learning
    </span>
    <!-- More skills... -->
</div>
```

## 🎨 Design Highlights

### Color Scheme
- **Primary**: `#0ea5e9` (Sky-500)
- **Dark**: `#0f172a` (Slate-900)
- **Light**: `#f8fafc` (Slate-50)

### Typography
- **Font Family**: Inter (Google Fonts)
- **Scale**: Responsive text sizes for all devices

### Components
- **Cards**: Rounded corners with hover effects
- **Buttons**: Gradient backgrounds with smooth transitions
- **Navigation**: Fixed mobile bottom nav

## 📦 Dependencies

```html
<!-- Tailwind CSS -->
<script src="https://cdn.tailwindcss.com"></script>

<!-- HTML2PDF -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js"></script>

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<!-- AOS Animations -->
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
```

## 🚀 Quick Start

1. **Clone or Download** the HTML file
2. **Customize** personal information and links
3. **Deploy** to GitHub Pages or any web server
4. **Access** your portfolio at your deployed URL

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

### Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/puspharaj-m/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/puspharajm2003)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:puspharaj.m2003@gmail.com)

**Built with ❤️ using Modern Web Technologies**

</div>
