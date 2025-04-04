# Vibrant Audio Visualizer - TLHA1232

A dynamic and visually engaging audio visualizer built with HTML, CSS, and JavaScript, leveraging the Web Audio API.  This project provides a compelling way to experience music by transforming audio frequencies into captivating visual patterns.



## Features

*   **Dynamic Visualization:**  Reacts in real-time to audio frequencies, creating a unique visual experience for each song.
*   **Customizable Style:**  Offers a vibrant color palette with animated gradient backgrounds and tunable visual parameters.
*   **MP3 Support:**  Easily load and visualize your own MP3 files.
*   **Responsive Design:**  Adapts seamlessly to different screen sizes and devices.  Specifically designed for full-screen viewing.
*   **Interactive Controls:**  Includes intuitive controls for play/pause, volume adjustment, and seeking within the audio track.
*   **Bass Kick Detection:**  Enhances the visual experience with responsive pulses and particle effects triggered by bass frequencies.
*   **Reflection Effect:**  Simulates a visually appealing reflection of the main visualizer.
*   **File Drag and Drop:** Simplifies file loading for a user-friendly experience.

## Technologies Used

*   **HTML5:**  Provides the structure and elements for the visualizer.
*   **CSS3:**  Styles the visualizer with modern design principles, animations, and responsive layouts.
*   **JavaScript:**  Handles audio processing, visualization logic, and user interaction.
*   **Web Audio API:**  Enables powerful audio analysis and manipulation directly in the browser.

## Setup and Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/TLHA1232/your-repo-name.git  # Replace with your actual repo name
    cd your-repo-name
    ```

2.  **Open `musicvisualiser2.0.html` in your web browser.**

    *   No local server is required as the project is entirely client-side.  However, some browsers may have restrictions on accessing local files due to security concerns.  If you encounter issues, consider using a simple local web server.

    *   **Optional: Using a local web server (Python):**

        ```bash
        python -m http.server
        ```

        Then navigate to `http://localhost:8000` in your browser.

## Usage

1.  **Upload Audio:**  Click the "Click or Drop MP3 Here" prompt to select an MP3 file from your computer, or drag and drop an MP3 file onto the page.
2.  **Controls:**  Use the play/pause button, volume slider, and progress bar to control the audio playback.
3.  **Enjoy:**  Immerse yourself in the dynamic visual representation of your music!

## Customization

Several visualization parameters can be adjusted within the JavaScript code to fine-tune the visual experience:

*   **`MIN_RADIUS`:**  The minimum radius of the core visual element.
*   **`MAX_RADIUS_INCREASE`:** The maximum amount the radius can increase in response to audio.
*   **`GLOW_BLUR`:** The blur radius of the glow effect.
*   **`GLOW_COLOR`:** The color of the glow effect.
*   **`BASE_LINE_WIDTH`:** The base width of the visualizer lines.
*   **`MAX_WIDTH_INCREASE`:** The maximum amount the line width can increase.
*   **`LERP_FACTOR`:**  The smoothing factor for the visualizer's responsiveness.
*   **`REFLECTION_ALPHA`:**  The transparency of the reflection effect.
*   **`BASS_PULSE_FACTOR`:** The strength of the background pulse triggered by bass.
*   **`BASS_KICK_THRESHOLD`:**  The threshold for detecting a bass kick.
*   **`BASS_KICK_COOLDOWN`:** The minimum time between bass kicks.
*   **`PARTICLE_COUNT`:** The number of particles in the effect.
*   **`PARTICLE_SPEED`:** The speed of the particles.
*   **`PARTICLE_FADE_SPEED`:** The rate at which particles fade out.
*   **`HUE_SHIFT_SPEED`:** The speed at which the color hue cycles.

These values are found within the `<script>` section of `THISISIT.html`.  Experiment with these values to create your own unique visual styles.

## Future Enhancements

*   **More Visualization Options:** Add different visualization modes (e.g., bar graphs, waveforms, etc.).
*   **User Interface Improvements:**  Provide a more comprehensive user interface for customization.
*   **Presets:** Allow users to save and load their preferred visualization settings.
*   **Cloud Integration:**  Enable playback and visualization of audio from online sources (e.g., SoundCloud, Spotify).
*   **Advanced Audio Analysis:** Implement more sophisticated audio analysis techniques to drive more complex visual effects.
*   **Mobile Optimization:** Further optimize for mobile devices.

## Credits

*   Developed by [TLHA1232](https://github.com/TLHA1232)

## License

This project is licensed under the [MIT License](LICENSE).  (You may need to create a LICENSE file)
