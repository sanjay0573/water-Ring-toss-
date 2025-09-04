# Water Ring Toss Game

A web-based recreation of the classic handheld water ring toss game, built with HTML, JavaScript, and p5.js. Players use buttons to make colorful rings fly and stack on a central peg, with support for both PC and mobile play. The game features vibrant graphics and a nostalgic feel, inspired by retro water-based toys.

## Features
- **Gameplay**: Click "Push Left" or "Push Right" buttons to make all rings fly upward with a left or right nudge. Use arrow keys (PC) or device tilt (mobile) to guide rings to the peg.
- **Objective**: Stack all five rings on the central peg to win, triggering a "You Win!" message and a "Play Again" button.
- **Graphics**:
  - Hollow rings (not balls) with thick outlines and inner circles for a retro look.
  - Water gradient background and bubble effects when buttons are pressed.
  - Textured brown peg with rounded edges.
- **Controls**:
  - **PC**: Arrow keys for left/right tilt, round "Push Left" and "Push Right" buttons at the bottom.
  - **Mobile**: Device tilt for left/right movement, touch buttons for ring movement.
- **Play Again**: Rectangular "Play Again" button at the top appears after winning to reset the game.
- **Responsive Design**: Canvas scales to fit PC and mobile screens.

## Demo
Play the game online at: `https://<yourusername>.github.io/<repo-name>` (replace `<yourusername>` and `<repo-name>` with your GitHub details after enabling GitHub Pages).

## Screenshots
![Gameplay Screenshot](screenshot.png)  
*Note: Add a screenshot by uploading `screenshot.png` to the repository and updating the path above.*

## Setup Instructions
1. **Clone or Download**:
   - Clone the repository:
     ```bash
     git clone https://github.com/<yourusername>/<repo-name>.git
     ```
   - Or download the ZIP file from the repository page on GitHub.

2. **Run Locally**:
   - Open `index.html` in a modern browser (e.g., Chrome, Firefox).
   - For best results, use a local server to avoid `file://` restrictions:
     ```bash
     python -m http.server 8000
     ```
     Then access at `http://localhost:8000`.

3. **Host Online**:
   - Upload `index.html` to a GitHub repository.
   - Enable GitHub Pages:
     - Go to **Settings > Pages** in your repository.
     - Select the **main** branch and save.
     - Access the game at `https://<yourusername>.github.io/<repo-name>` after a few minutes.

## Requirements
- A modern web browser (Chrome, Firefox, Safari, etc.).
- Internet access for the p5.js CDN (`https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.2/p5.min.js`).
- Mobile devices require motion sensor access for tilt controls (may prompt for permission).

## How to Play
1. **Start**: Open the game in a browser via the GitHub Pages URL or locally.
2. **Controls**:
   - Click **Push Left** or **Push Right** (round buttons at the bottom) to make all rings fly upward with a left or right nudge.
   - Use **left/right arrow keys** (PC) or **tilt your device** (mobile) to align rings with the central peg.
3. **Goal**: Stack all five rings on the peg to win. A "You Win!" message appears.
4. **Restart**: Click **Play Again** (top button) after winning to reset the game.

## Development
- **Tech Stack**: HTML, CSS, JavaScript, p5.js.
- **Physics**: Low gravity and damping for a floaty, water-like ring movement.
- **Graphics**: Water gradient, bubble animations, and vibrant ring colors (#FF0000, #00FF00, etc.) for a nostalgic aesthetic.

## Contributing
Contributions are welcome! Fork the repository, submit issues, or create pull requests to add features like sound effects, themed designs, or difficulty levels.

## License
This project is licensed under the [MIT License](LICENSE).  
*Note: Add a `LICENSE` file to the repository if desired.*

## Credits
Developed as a fun, nostalgic project inspired by classic handheld water ring toss games and community discussions on retro toys.