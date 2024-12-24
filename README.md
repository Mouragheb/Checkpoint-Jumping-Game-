# CheckPoint Jumping Game HTML/CSS/JS

A Pen created on CodePen.io. Original URL: [https://codepen.io/Mouragheb/pen/azowoLJ](https://codepen.io/Mouragheb/pen/azowoLJ).

Project Summary: CheckPoint Jumping Game

The CheckPoint Jumping Game is a browser-based 2D platformer game where the player controls a character to navigate platforms, avoid falling off, and reach checkpoints. It provides an engaging gaming experience with smooth animations, responsive controls, and collision detection.

Technologies and Languages Used
	1.	HTML:
	•	Used to structure the game’s interface and layout.
	•	Contains key elements like:
	•	The game title, instructions, and start button (<div> and <button> elements).
	•	The <canvas> element for rendering the game graphics.
	•	Hidden screens for checkpoint notifications and the end of the game.
	2.	CSS:
	•	Styles the game’s appearance, ensuring a visually appealing design.
	•	Implements responsive design using media queries for different screen sizes.
	•	Provides consistent styling with variables (e.g., --main-bg-color, --golden-yellow).
	•	Adds hover effects and animations to buttons for a polished user experience.
	3.	JavaScript:
	•	The core technology for game logic and interactivity.
	•	Handles:
	•	Player controls: Arrow keys for movement and spacebar for jumping.
	•	Physics: Gravity, collision detection, and velocity management.
	•	Game animations: Uses the requestAnimationFrame() API for smooth updates.
	•	Collision detection: Ensures the player interacts with platforms and checkpoints.
	•	Object-oriented programming (OOP): Classes are used for modularity:
	•	Player: Represents the character controlled by the user.
	•	Platform: Represents platforms the player can stand on.
	•	CheckPoint: Represents checkpoints the player must reach.
	•	Game state management: Tracks progress and displays appropriate screens (e.g., checkpoint reached, game over).
	4.	Canvas API:
	•	A key part of the HTML5 specification for rendering the game graphics.
	•	The getContext("2d") method is used to draw shapes, such as the player, platforms, and checkpoints, directly on the screen.
	•	Enables dynamic updates for animation and movement.

Gameplay Experience
	1.	Start Screen:
	•	Players are welcomed with instructions and a “Start Game” button.
	•	Clicking the button initializes the game by displaying the canvas and hiding the start screen.
	2.	Player Movement:
	•	Players use arrow keys for horizontal movement and the spacebar to jump.
	•	Gravity and collision detection create realistic interactions with platforms.
	3.	Objectives:
	•	Players navigate through a series of platforms to reach yellow checkpoints.
	•	Progression is linear, requiring checkpoints to be reached in order.
	4.	Challenges:
	•	Players must avoid falling off platforms and navigate increasingly tricky layouts.
	•	Platforms are spaced apart, requiring precise jumping and movement.
	5.	Game Completion:
	•	When the final checkpoint is reached, a congratulatory screen is displayed.

Developer Experience
	1.	Problem-Solving:
	•	Implementing physics-based movement, like gravity and velocity, required a strong understanding of mathematical principles.
	•	Collision detection involved logical conditions to ensure smooth gameplay interactions.
	2.	Design Challenges:
	•	Balancing simplicity and visual appeal using CSS.
	•	Ensuring the game looks good across devices with responsive scaling.
	3.	Learning Outcomes:
	•	The developer leveraged JavaScript’s OOP capabilities to make the code modular and reusable.
	•	Gained hands-on experience with the Canvas API, which is vital for creating 2D graphics.
	4.	Improvements Considered:
	•	Adding more levels, dynamic obstacles, or power-ups for greater engagement.
	•	Introducing sound effects and music to enhance the gaming experience.

Summary of the Experience

This project demonstrates a thoughtful application of web technologies to create an interactive, engaging game. It showcases the developer’s ability to combine HTML, CSS, JavaScript, and the Canvas API into a cohesive experience. The CheckPoint Jumping Game not only entertains but also serves as a learning experience in creating browser-based games. It’s an excellent example of using modern web technologies to bring a creative idea to life.
