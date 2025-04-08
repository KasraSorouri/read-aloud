# read-aloud

## Description
This is a simple Text Reader web application that allows users to:
- Read text aloud using the Web Speech API
- Control speech with pause/resume and stop functionality
- Select different voices and adjust reading speed

The application is built with HTML, CSS, and vanilla JavaScript, with no external dependencies.

## Simple User Manual

### How to Use:
1. **Enter Text**: Type or paste your text in the left textarea
2. **Convert**: Click "Convert" to see an HTML version in the right panel
3. **Read Aloud**: 
   - Select a voice from the dropdown (optional)
   - Adjust the speed slider if needed
   - Click "Read Aloud" to start
4. **Control Playback**:
   - "Pause/Resume" to temporarily stop/continue reading
   - "Stop" to cancel reading completely
5. **Clear All**: Click "Clear All" to reset both text areas

### Tips:
- The app will try to automatically select a Finnish voice named "Harri" if available
- You can adjust reading speed during playback (0.5x-2x normal speed)
- The status message at the top right shows current activity

### Requirements:
- Modern web browser with Web Speech API support (Chrome, Edge, Firefox, Safari)
- Internet connection (for voice synthesis in some browsers)
