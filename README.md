
# Workout Clock Web App

## Overview

The **Workout Clock** is a web application designed to help users manage their workout intervals effectively. It features a simple and user-friendly interface that allows users to set "On" and "Off" times for interval training, providing audio cues to signal transitions between workout phases. The app is built using HTML, CSS (with Tailwind CSS and DaisyUI), and JavaScript.

## Features

- Set customizable **On** and **Off** times in seconds.
- Start, pause, and reset the timer.
- Visual countdown display in a user-friendly format.
- Audio notifications for transitioning between workout phases.
- Responsive design for optimal use on various devices.

## Technologies Used

- **HTML**: Markup language for structuring the app.
- **CSS**: Stylesheet language for styling the app (using [Tailwind CSS](https://tailwindcss.com/) and [DaisyUI](https://daisyui.com/)).
- **JavaScript**: Programming language for implementing functionality.
- **Audio**: Sound notifications for workout transitions.

## Installation

To run the Workout Clock Web App locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/workout-clock.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd workout-clock
   ```

3. **Open the `index.html` file in your web browser**:

   ```bash
   open index.html   # macOS
   start index.html  # Windows
   xdg-open index.html  # Linux
   ```

4. **Ensure you have the audio files** (`ontime.mp3` and `offtime.mp3`) in the same directory for sound notifications.

## Usage

1. **Set your On and Off times**:
   - Input the desired number of seconds for your workout and rest periods in the input fields.

2. **Start the Timer**:
   - Click the **Start** button to begin the timer. The display will show the countdown.

3. **Pause/Resume the Timer**:
   - Click the **Pause** button to stop the timer. Click it again to resume.

4. **Reset the Timer**:
   - Click the **Reset** button to return the timer to the initial On time.

## Code Structure

- **HTML (`index.html`)**: Contains the structure of the app.
- **CSS**: Inline styles are included for styling the layout.
- **JavaScript**: Contains the logic for the timer functionality and audio notifications.

## Screenshots

![Workout Clock Screenshot](gym.png) <!-- Update with the actual path of the screenshot if available -->

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to modify any sections as needed!
