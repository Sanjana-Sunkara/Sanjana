# ASCII Basketball Shootout

#### Video Demo:  <INSERT_YOUR_VIDEO_URL_HERE>

#### Description:
ASCII Basketball Shootout is a fun, interactive terminal-based basketball shooting game developed in Python. The game challenges players to score as many baskets as possible by inputting an angle (in degrees) and power (a numeric value) for each shot. Using simple ASCII graphics, it simulates a basketball court with a moving hoop and animates the ball’s flight based on realistic projectile motion physics.

The hoop randomly changes position after each shot, adding variety and difficulty to the game. Players have a limited time (10 seconds) to input the shot parameters, making the game engaging and fast-paced. The player is allowed 5 shots per game, and scoring 3 or more triggers a celebratory beep sound.

The game runs entirely in the terminal and uses no external libraries beyond Python’s standard modules. It features:

- Animated ball movement using physics formulas for trajectory
- Randomized hoop positions to keep gameplay challenging
- Input timeouts to add urgency and pace
- Real-time score and shot tracking
- ASCII graphics for court, hoop, and ball visualization

This project was created as a final project for the Harvard CS50P (Introduction to Programming with Python) course. It showcases concepts such as:

- Input validation and timed input handling
- Basic physics calculations in programming
- Console graphics using ASCII characters
- Use of Python standard libraries for randomness, timing, and system calls
- Structuring code with functions for readability and modularity

Players interact by entering the shot angle (1 to 90 degrees) and power (1 to 30), aiming to make the ball pass through the moving hoop’s position. The game encourages experimenting with different shot parameters to master the arc and score points.

This README serves as documentation to explain the purpose, features, and instructions for the ASCII Basketball Shootout game. The included video demo visually demonstrates gameplay, showcasing how the ball arcs toward the hoop and how scoring is registered.

Thank you for checking out this project—hope you enjoy shooting hoops in your terminal!

---

## How to Run

1. Ensure Python 3 is installed on your system.
2. Open your terminal or command prompt.
3. Navigate to the project folder containing `project.py`.
4. Run the game using:

   ```bash
   python3 project.py
