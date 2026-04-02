# My HTML/CSS Webpage with Docker

A modern, responsive webpage built with pure HTML and CSS, containerized with Docker using Nginx.

## Project Structure

```
.
├── index.html       # Main HTML file
├── styles.css       # Stylesheet
├── Dockerfile       # Docker configuration
├── .dockerignore    # Docker ignore file
└── README.md        # This file
```

## Features

- Responsive navigation bar
- Hero section with gradient background
- About section with animated cards
- Services grid layout
- Contact form with validation styles
- Sticky header
- Smooth scrolling
- Hover animations
- Mobile-friendly design

## Getting Started

### Run Locally (without Docker)

Simply open `index.html` in your browser.

### Run with Docker

**1. Build the Docker image:**
```bash
docker build -t my-webpage .
```

**2. Run the Docker container:**
```bash
docker run -d -p 8080:80 --name my-webpage-container my-webpage
```

**3. Open your browser and navigate to:**
```
http://localhost:8080
```

**4. Stop the container:**
```bash
docker stop my-webpage-container
```

**5. Remove the container:**
```bash
docker rm my-webpage-container
```

## Tech Stack

- **HTML5** - Structure
- **CSS3** - Styling & Animations
- **Nginx (Alpine)** - Web Server
- **Docker** - Containerization
