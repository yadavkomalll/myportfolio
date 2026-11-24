Komal Yadav — Digital Portfolio & Interactive Resume

A modern, responsive, single-page developer portfolio designed to double as a digital resume. Built with semantic HTML5, custom CSS variables ("Deep Sea Console" palette), and vanilla JavaScript—featuring an interactive, mouse-reactive node topology background and a modular project showcase.

✨ Key Features

Single-File Architecture: Zero build steps or complex bundlers required. Everything (HTML, CSS, JS) is cleanly modularized inside a single file for instant local testing and effortless static deployment.

Interactive Network Canvas: A custom HTML5 <canvas> background simulating a live infrastructure topology map that reacts smoothly to cursor movement and scroll depth, while respecting prefers-reduced-motion accessibility settings.

System Status Console: A custom hero UI widget mimicking a live developer interface monitor, highlighting core technical capabilities.

Capstone Architecture Breakdown: Dedicated featured layout for Neon Watchdog Pro (AI-Driven Insider Threat Detection System), complete with an end-to-end visual detection pipeline.

Fully Responsive & Accessible: Mobile-first navigation drawer, smooth scroll-reveal animations via IntersectionObserver, and semantic HTML landmarks.

📁 Repository Structure

├── index_11.html    # Complete portfolio source code (HTML, CSS, JS)
└── README.md        # Project documentation


💡 Deployment Tip: Before enabling GitHub Pages, rename index_11.html to index.html so GitHub automatically recognizes it as the root entry point of your site.

🛠️ Tech Stack

Core: HTML5 (100% single-file codebase), CSS3 (Custom Properties / CSS Grid & Flexbox), Vanilla JavaScript (ES6+)

Typography: Plus Jakarta Sans & JetBrains Mono

Icons: Lucide Icons

🚀 Getting Started (Local Setup)

Clone the repository:

git clone https://github.com/yadavkomalll/<your-repo-name>.git
cd <your-repo-name>


Run locally using Python:

python -m http.server 3000


Open your browser and visit http://localhost:3000/index_11.html (or http://localhost:3000 once renamed to index.html).

(Alternatively, open the folder in VS Code and launch with the Live Server extension).

🔧 Customization Checklist

Before sharing your live portfolio with recruiters, ensure you update the placeholder links in your HTML file:

Resume PDF Download: Place your resume PDF in the repository (e.g., Komal_Yadav_Resume.pdf) and update href="#" on the Download Resume button.

Project Links: Replace href="#" in the Featured Projects section with your live demo and repository URLs (including Neon Watchdog Pro).

Contact Form: Connect <form id="contactForm"> to a free static form handler like Formspree or Web3Forms to receive emails directly.

🌐 Deploying on GitHub Pages

Rename index_11.html to index.html in this repository.

Go to Settings > Pages in your GitHub repository.

Under Build and deployment, select Deploy from a branch, choose the main branch (/root), and click Save.

Your portfolio will go live at https://yadavkomalll.github.io/<your-repo-name>/.

© 2026 | Designed & Engineered by Komal Yadav (@yadavkomalll)
