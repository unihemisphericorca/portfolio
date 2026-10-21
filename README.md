# Rachel Ang — Cybersecurity Portfolio

> A retro-inspired personal portfolio showcasing my journey in information technology, cybersecurity, and continuous learning.

<p align="center">
  <img width="1138" height="925" alt="Rachel Ang portfolio homepage" src="https://github.com/user-attachments/assets/48b7eb87-b10e-43d4-a659-fb8acbf7666c" />
</p>

<p align="center">
  <a href="https://unihemisphericorca.github.io/portfolio/Portfolio/hero.html">View the live portfolio</a>
</p>

## About the project

This website is a personal portfolio built with HTML and CSS. It uses a Windows-inspired interface to present my background, projects, certifications, and contact information in an approachable and memorable way.

The portfolio is designed to support my development toward the **cybersecurity field**, with an emphasis on problem-solving, responsible technology use, secure web practices, and lifelong learning.

## Cybersecurity focus

Areas I am interested in developing include:

- Security fundamentals and defensive security
- Secure web development and input validation
- Vulnerability awareness and risk reduction
- Networking and system administration
- Digital privacy and responsible handling of information
- Security certifications and hands-on technical practice

This repository is also used to apply secure development principles where appropriate. For example, the contact page includes browser-side input constraints and anti-spam considerations. Because the site is static, these controls are not a replacement for server-side validation, rate limiting, CSRF protection, output encoding, or parameterized SQL queries in a production application.

## Technologies

- **HTML5** — semantic page structure and accessible form controls
- **CSS3** — responsive layouts and retro desktop-inspired styling
- **GitHub Pages** — static hosting and deployment
- **Git/GitHub** — version control and project management

## Portfolio sections

- **Home** — introduction and portfolio landing page
- **About** — education, interests, languages, and personal background
- **Projects** — selected and future technical work
- **Certifications** — professional development and achievements
- **Contact** — a direct way to get in touch using the visitor's configured email client

## Running locally

No build system or package installation is required.

1. Clone the repository:

   ```bash
   git clone https://github.com/unihemisphericorca/portfolio.git
   ```

2. Open `Portfolio/hero.html` in a browser, or serve the project with a local HTTP server:

   ```bash
   python3 -m http.server 8000
   ```

3. Visit `http://localhost:8000/Portfolio/hero.html`.

## Security notes

This is a static front-end project. It does not contain a backend, database, authentication system, or server-side message-processing endpoint.

For a production contact system, I would add:

- HTTPS/TLS for all requests
- Strict server-side validation and length limits
- Output encoding before displaying user-controlled data
- CSRF protection where applicable
- Rate limiting and spam filtering
- Email-header injection protections
- Secure secret and API-key management
- Prepared statements or parameterized queries for any database operations
- Security headers such as a carefully configured Content Security Policy

Client-side validation improves usability, but it cannot by itself prevent SQL injection or other server-side attacks.

## Connect

- [GitHub](https://github.com/unihemisphericorca)
- [LinkedIn](https://www.linkedin.com/in/diangelorachel/)
- [Instagram](https://www.instagram.com/________________________rachel/)

## License

This project is a personal portfolio. Please contact me before reusing personal content, images, or branding.
