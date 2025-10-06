Stella and Space Weather: An Interactive Story
Overview
Stella and Space Weather is an educational, interactive web story designed to introduce primary and secondary school students to the concepts of space weather. Through a narrative guided by Stella, a Solar Flare, users learn about the Sun's activity, the phenomenon of auroras, the impact on technology, and the protective role of Earth's magnetic field.

The project is built as a single-page application (index.html) using vanilla HTML, CSS, and JavaScript, prioritizing simplicity, accessibility, and direct interaction.

Key Features
Chapter-Based Narrative: A six-chapter story designed for easy, step-by-step learning.

Interactive Aurora Simulation: A dynamic canvas simulation where users can adjust the "Solar Wind Intensity" to see how it affects the visibility and movement of the aurora.

Text-to-Speech (TTS): A Listen function allows users to hear the story read aloud (using a friendly, English female voice where available).

Navigation & Quiz: Simple arrow-key or button navigation, plus a short, graded quiz to check understanding.

Educational Resources: A dedicated sidebar panel for a Glossary and Safety Tips related to space weather.

Getting Started
To view and run the project, you only need a modern web browser.

Installation
Clone the Repository:

Bash

git clone [TU_REPO_URL_AQUÍ]
Navigate to the Directory:

Bash

cd stella-and-space-weather
Open the File:
Simply open the index.html file in your preferred web browser.

Bash

Example (on macOS)
open index.html
Technology Stack
The project intentionally uses a minimal stack to ensure broad compatibility and ease of deployment.

HTML5: Structure and Semantics.

CSS3: Styling and Responsive Design (using CSS variables for a dark, thematic look).

Vanilla JavaScript (ES6): All interactivity, including the TTS, navigation logic, quiz grading, and the canvas-based aurora simulation.

📐 Project Structure
stella-and-space-weather/
├── index.html        # Main and only file: contains HTML, CSS, and JavaScript.
├── images/           # Placeholder directory for the story's visual assets.
│   ├── sol.jpg
│   ├── llamarada1.jpg
│   ├── Aurora.jpg
│   └── ... (other images)
└── README.md         # This file.

Planned Improvements / To-Do
[ ] Implement a dynamic PDF generation feature for the 📄 Download PDF button (currently a placeholder).

[ ] Expand the quiz section with more questions.

[ ] Enhance the responsiveness for very small mobile screens.

[ ] Add a full accessibility audit for the interactive canvas elements.

Contributing
Contributions are welcome! If you have suggestions for new features, bug fixes, or educational content enhancements, please feel free to open an issue or submit a pull request.

Author
jose francisco vazquez milan 
violeta sofia fregoso ramos
leonela guadalupe gutierrez martinez 

https://github.com/milanjos

License
This project is licensed under the MIT License - see the LICENSE file for details.
