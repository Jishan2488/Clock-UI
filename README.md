# Clock-UI
Glassmorphism Animated Clock
A stylish 2D analog clock with a glass morphism effect, smooth sweeping hands, and a seamless light/dark mode toggle. Built with HTML5 Canvas, CSS3, and vanilla JavaScript – no external dependencies (except Font Awesome for icons).

https://link-to-screenshot.png <!-- Replace with actual screenshot if available -->

✨ Features
Smooth Second Hand – The second hand moves fluidly (60 steps per second) thanks to millisecond interpolation.

Light / Dark Theme Toggle – Click the floating orb to switch between light and dark themes. All colors transition smoothly.

Glassmorphism Design – Frosted glass background with backdrop filters, subtle shadows, and glowing accents.

Animated Decorations:

Pulsing glow ring behind the clock.

Rotating decorative dots around the dial.

Floating background dots with independent animations.

Digital Time Display – Shows current time in 24-hour format below the analog clock.

Responsive – Scales to fit any screen size while maintaining aspect ratio.

🚀 Live Demo
[Insert live demo link here if hosted]

📸 Screenshots
Light Mode	Dark Mode
https://light.png	https://dark.png
🛠️ Technologies Used
HTML5 – Structure

CSS3 – Styling, glass effects, animations, transitions

JavaScript (ES6) – Clock logic, canvas drawing, theme switching

Canvas API – Drawing the analog clock face and hands

Font Awesome – Icons for the theme toggle

📦 Installation & Usage
Clone the repository:

bash
git clone https://github.com/yourusername/glassmorphism-clock.git
Open index.html in your favorite browser.

Click the sun/moon button to toggle between light and dark themes.

No build step or server required – it's pure frontend.

🎨 Customization
Colors – Edit the lightPalette and darkPalette objects in the JavaScript section to change the theme colors.

Clock Size – Adjust the width of .clock-card in CSS or the canvas scaling factor.

Animation Speeds – Tweak transitionProgress increment or angleOffset increment for faster/slower transitions.

🧠 How It Works
The clock is drawn on a <canvas> element using JavaScript's 2D context.

requestAnimationFrame drives the animation loop, updating hand angles every frame.

Theme transition interpolates between two color palettes over a fixed duration.

CSS backdrop filters create the glass effect on the container and digital display.

Floating dots and glow ring are absolutely positioned divs with CSS animations.

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to check the issues page.

📄 License
This project is open source and available under the MIT License.

🙏 Acknowledgements
Inspired by modern UI trends (glassmorphism, neumorphism).

Icons by Font Awesome.

Enjoy the time! 🕰️

