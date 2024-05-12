A simple command line utility that prints "start" when the camera detects movement, and "stop" when the movement stops.
It is intended to be used alongside a shell script that monitors the terminal output and performs appropriate actions, such as launching or stopping a separate video recording application.

Written in Rust with minimal dependencies, the eye-hal crate only.

# TO DO:
- Command line settings (currently settings are hard coded)
- Shell script example
- Skip motion detection if image is too dark
- Processing: brightness
