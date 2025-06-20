# 3D Analog Clock

## Overview
The 3D Analog Clock is a web-based application built with HTML, CSS, and JavaScript, designed to display a real-time analog clock with a modern 3D aesthetic. Created by Roshan Kumar Prajapati, the clock features a dynamic background, 3D effects, and smooth hand animations, making it both functional and visually appealing. It is responsive and optimized for both desktop and mobile devices.

## Features
- **Clock Display**: A circular analog clock with numbered markers (1–12), hour, minute, and second hands, and a center cap.
- **3D Styling**: 
  - Clock face with radial gradient and inset shadow for depth.
  - 3D perspective applied to the clock using CSS `transform: rotateX(20deg)`.
  - Numbers positioned around the clock with CSS transforms for a circular layout.
  - Hands with distinct styles (hour: thick, minute: medium, second: thin and red) and smooth transitions.
- **Dynamic Background**: A brick wall background with a subtle animated gradient effect using CSS `@keyframes`.
- **Responsive Design**: Centered layout with flexible sizing for various screen sizes.
- **Real-Time Functionality**: JavaScript-driven clock hands that update every second to reflect the current time.

## Tech Stack
- **HTML5**: Structure of the clock, including numbers, hands, and center cap.
- **CSS3**: Styling, 3D effects, animations, and responsiveness (`styles.css`).
- **JavaScript**: Logic for updating clock hands in real-time (`script.js`).

## Project Structure
```
3d-analog-clock/
├── index.html         # Main HTML file
├── styles.css        # CSS styles for 3D effects and layout
├── script.js         # JavaScript for clock functionality
├── brick-wall.jpg    # Background image
├── LICENSE.md        # MIT License
└── README.md         # This file
```

## Prerequisites
- A modern web browser (e.g., Chrome, Firefox, Edge).
- A code editor (e.g., VS Code) for customization.
- The `brick-wall.jpg` image for the background (replace with a suitable image if needed).

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/The-Roshan/3d-analog-clock.git
cd 3d-analog-clock
```

### 2. Verify Background Image
- Ensure `brick-wall.jpg` is in the project root.
- Replace with a similar high-quality image (JPEG or PNG) if needed, updating the `background` property in `styles.css`.

### 3. Open the Website
- Open `index.html` in a web browser:
  ```bash
  open index.html  # macOS
  start index.html  # Windows
  ```
- Alternatively, use a local development server (e.g., VS Code Live Server) for a better experience.

### 4. Customize (Optional)
- Edit `styles.css` to modify colors, 3D effects, or background animation.
- Update `script.js` to add features like sound effects or time zone support.
- Modify `index.html` to adjust the clock’s structure or add new elements.

## Usage
1. **View Time**: The clock displays the current time with hour, minute, and second hands updating in real-time.
2. **Interact**: Hover over the clock to observe 3D effects (if additional hover styles are implemented in `styles.css`).
3. **Responsive**: Access the clock on mobile or desktop for a consistent experience.
4. **Background Animation**: Enjoy the subtle gradient animation over the brick wall background.

## Deployment
- **Static Hosting**:
  1. Upload `index.html`, `styles.css`, `script.js`, and `brick-wall.jpg` to a hosting service (e.g., GitHub Pages, Netlify, Vercel).
  2. Configure the service to serve `index.html` as the entry point.
- **GitHub Pages Example**:
  1. Push the repository to GitHub.
  2. Enable GitHub Pages in the repository settings, selecting the `main` branch.
  3. Access the site at `https://the-roshan.github.io/3d-analog-clock`.
- **Netlify Example**:
  1. Drag the project folder into Netlify’s dashboard.
  2. Deploy and use the provided URL.
- **Local Server**:
  ```bash
  python -m http.server 8000
  ```
  Visit `http://localhost:8000`.

## Notes
- **Background Image**: Ensure `brick-wall.jpg` is present to avoid a missing background. Optimize the image for web use to reduce load time.
- **JavaScript Logic**: The `script.js` file must implement logic to rotate the hour, minute, and second hands based on the current time (e.g., using `Date` and `setInterval`).
- **Styling**: The provided CSS includes 3D effects and animations; ensure `styles.css` is complete for full visual impact.
- **Enhancements**: Consider adding features like a digital time display, sound ticks, or customizable themes.
- **SEO**: Update meta tags in `<head>` (e.g., `description`, `keywords`) for better visibility.
- **License**: Include the MIT License (as provided previously) in `LICENSE.md` to clarify usage terms.

## License
This project is licensed under the MIT License. See `LICENSE.md` for details.

## Contributing
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`.
3. Commit changes: `git commit -m "Add your feature"`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.

## Acknowledgments
- Built with vanilla HTML, CSS, and JavaScript for educational purposes.
- Inspired by modern analog clock designs with 3D aesthetics.
- Created by Roshan Kumar Prajapati.

## Contact
For questions or feedback, contact Roshan Kumar Prajapati:
- Email: roshanjsr5555@gmail.com
- Phone: +91 7061126213
- GitHub: [The-Roshan](https://github.com/The-Roshan)
