Gerald's Portfolio Website
A personal portfolio website showcasing skills, experience, projects, education, and contact details for Gerald Mulwa, an Electrical Engineer passionate about renewable energy, embedded systems, and AI-powered solutions.

📌 Features
Responsive Navigation Menu – Links to Home, Interests, Experience, Projects, Education, and Contact sections.

About Section – Personal introduction with a downloadable CV.

Interests Section – Highlights professional areas of interest.

Experience Section – Summary of professional work experience.

Projects Showcase – Detailed descriptions and GitHub links for featured projects.

Education Section – Academic background and related activities.

Contact Section – Click-to-call, email, WhatsApp, and Facebook contact options.

Message Form – Integrated with Formspree to receive messages directly.

Footer – Copyright.

🛠️ Technologies Used
HTML5 – Semantic and accessible structure.

CSS3 – External stylesheet for styling (style.css).

JavaScript – For interactive elements (index.js).

Formspree API – For form submission handling.

📂 Project Structure
makefile
Copy
Edit
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── index.js            # JavaScript file
├── media/              # Images and CV
│   ├── gerald.jpg
│   ├── gerald1.jpg
│   └── gerald's-CV.pdf
└── README.md           # Project documentation
🚀 Getting Started
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/<your-username>/<your-repo>.git
2️⃣ Open in Browser
Simply open index.html in your browser.

3️⃣ Customize
Update media/gerald.jpg, media/gerald1.jpg, and media/gerald's-CV.pdf with your own images and CV.

Modify text in index.html to reflect your personal details.

Adjust style.css for preferred colors and layout.

📧 Contact Form Setup
This project uses Formspree for message handling:

Go to Formspree.io.

Sign up and get a unique form endpoint.

Replace the form action URL in:

html
Copy
Edit
<form action="https://formspree.io/f/xzzvagak" method="POST">
with your own Formspree endpoint.

📌 Live Demo
You can deploy this portfolio using:

GitHub Pages

Netlify

Vercel

Example deployment command for GitHub Pages:

bash
Copy
Edit
git add .
git commit -m "Initial commit"
git push origin main
Then enable GitHub Pages in your repository settings.

📜 License
This project is licensed under the MIT License – feel free to use and adapt it.
