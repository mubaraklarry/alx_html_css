# Holberton School - Advanced CSS Project  
**Project:** Recreate a pixel-perfect landing page using only HTML & CSS  
**Student:** Mubarak Larry  
**Cohort:** [Your cohort number]  
**Start Date:** $(date '+%B %d, %Y')

## Project Overview
This project consists of recreating a complex, modern landing page **exactly** as designed in Figma using **only vanilla HTML and CSS** (no frameworks, no libraries).

### Objectives
- Master advanced CSS selectors and specificity
- Implement complex layouts using Flexbox and Grid
- Perfect understanding of the CSS cascade and inheritance
- Pixel-perfect implementation from design
- Responsive design across mobile, tablet, and desktop
- Clean, semantic HTML5 structure
- W3C valid code

### Design Reference
- Figma File: [Duplicate this design to your drafts](https://www.figma.com/design/5ZkA14tAOMzQIIHLxalU3s/Homepage--Copy-?node-id=0-1&p=f&t=AtnVg4RyXzNVTzWJ-0)
- Fonts used: Source Sans Pro, Spin Cycle OT
- All assets downloaded and included locally

### Features Implemented
- Fully responsive layout
- Smooth hover effects and transitions
- Custom typography scale
- Reusable CSS classes and variables
- Optimized image assets
- Semantic HTML5 structure

### File Structure

cat > index.html << 'EOF'
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechCon 2025 - The Future of African Tech</title>
    <meta name="description" content="Join Africa's largest technology conference in 2025">
    <meta name="author" content="Mubarak Larry">
    
    <!-- Figma Design Reference -->
    <!-- https://www.figma.com/file/XXXXX -->
    
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@300;400;600;700;900&display=swap" rel="stylesheet">
</head>
<body>
    <header class="header">
        <div class="container">
            <div class="logo">
                <span>TechCon</span>
            </div>
            <nav class="nav">
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#speakers">Speakers</a></li>
                    <li><a href="#schedule">Schedule</a></li>
                    <li><a href="#venue">Venue</a></li>
                    <li><a href="#tickets" class="btn-primary">Get Tickets</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section class="hero">
            <div class="container">
                <h1>TechCon 2025</h1>
                <p class="subtitle">The Future of African Innovation</p>
                <p class="date">March 15-17, 2025 • Accra, Ghana</p>
                <div class="hero-actions">
                    <a href="#tickets" class="btn-primary btn-large">Register Now</a>
                    <a href="#speakers" class="btn-secondary btn-large">View Speakers</a>
                </div>
            </div>
        </section>

        <!-- More sections will be added in next tasks -->
    </main>

    <footer class="footer">
        <div class="container">
            <p>&copy; 2025 TechCon. All rights reserved. Made with ❤️ by Mubarak Larry</p>
        </div>
    </footer>
</body>
</html>
