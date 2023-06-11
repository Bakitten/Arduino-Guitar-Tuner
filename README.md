# Arduino Guitar Tuner Project


## Acoustic and Electric Guitar Tuner

Welcome to the Arduino Guitar Tuner project! This repository contains all the necessary files and code to build your own Arduino-based guitar tuner. With this project, you can tune both acoustic and electric guitars with ease and precision.

### Introduction
The Arduino Guitar Tuner project aims to provide a convenient and accurate solution for tuning your guitar. Whether you are a beginner or an experienced musician, this tuner will ensure that your guitar is always perfectly in tune. The project supports both acoustic and electric guitars and provides on-screen instructions for tuning each string.

### Features
- Automatic detection of guitar notes and strings
- LCD screen for visual indications and tuning instructions
- Supports both acoustic and electric guitars
- Fast and accurate tuning
- User-friendly interface

### Hardware Requirements
To build the Arduino Guitar Tuner, you will need the following components:
- Arduino board (e.g., Arduino Uno)
- MAX9812 microphone module with built-in amplifier
- LCD screen with I2C interface
- 9V battery connector
- Audio jack
- LM386 audio amplifier (for electric guitar)
- LED ON/OFF button
- Cables

### Software Design
The Arduino code for the Guitar Tuner project focuses on accurate frequency detection and tuning guidance. The core functions of the tuner code include:
- `FindFrequency()`: Computes the frequency of the input signal (microphone or electric guitar) using the FFT algorithm available in the `arduinoFFT.h` library.
- `displayNoteAndTune()`: Displays the detected note and provides tuning instructions on the LCD screen.

### Installation and Usage
1. Clone or download this repository to your local machine.
2. Connect the hardware components as per the circuit diagram provided.
3. Open the Arduino IDE and upload the code to your Arduino board.
4. Connect your guitar to the tuner (either using the microphone or the audio jack).
5. Power on the tuner and follow the on-screen instructions to tune each string.

### Contribution
Contributions to this project are welcome. If you have any ideas, improvements, or bug fixes, feel free to open an issue or submit a pull request.

### License
This project is licensed under the [MIT License](LICENSE).

### Acknowledgments
The Arduino Guitar Tuner project was inspired by various online tutorials and projects related to guitar tuning using Arduino. Special thanks to the following resources:
- [Circuit Digest: Arduino Uno Guitar Tuner](https://circuitdigest.com/microcontroller-projects/arduino-uno-guitar-tuner)
- [Instructables: Arduino Guitar Tuner](https://www.instructables.com/Arduino-Guitar-Tuner/)
- [Instructables: Guitar Tuner With an Arduino](https://www.instructables.com/Guitar-Tuner-With-an-Arduino/)

### Conclusion
The Arduino Guitar Tuner project offers a cost-effective and accurate solution for tuning your guitar. With its user-friendly design and reliable performance, this project will enhance your guitar playing experience. Enjoy perfectly tuned strings with the Arduino Guitar Tuner!

**Note**: For more detailed information, including the project journal and code snippets, please refer to the [project website](https://github.com/your-username/arduino-guitar-tuner).

## Journal
Refer to the pdf in releases section for the detailed project journal.

## How to Contribute
Contributions are welcome! Follow these steps to contribute to the Arduino Guitar Tuner project:

1. Fork the

 repository.
2. Create a new branch for your contribution.
3. Make your changes and improvements.
4. Test your changes thoroughly.
5. Commit and push your changes to your forked repository.
6. Open a pull request, describing your changes in detail.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

Enjoy tuning your guitar with the Arduino Guitar Tuner!
