# Arduino LED Blinking – QA Documentation

## 1. Project Overview

This project demonstrates a basic embedded system using an Arduino
board and an LED. The objective is to blink an LED at a fixed interval
and document the quality assurance and problem-solving process using GitHub.

## 2. Hardware Used

- Arduino Uno
- LED
- 220Ω resistor
- Breadboard
- Jumper wires

## 3. Software Used

- Arduino IDE
- Arduino C/C++
- GitHub

## 4. Hardware Connection

The LED is connected to Arduino digital pin 13 through a 220Ω resistor.

The LED cathode is connected to GND.

## 5. Working Principle

The Arduino configures the LED pin as an output.

The LED is switched ON for one second and then OFF for one second.
This process repeats continuously.

## 6. Expected Behaviour

1. LED turns ON.
2. LED remains ON for approximately 1 second.
3. LED turns OFF.
4. LED remains OFF for approximately 1 second.
5. The cycle repeats continuously.

## 7. Testing Procedure

1. Connect the LED and resistor to the Arduino.
2. Open the `src/led_blink.ino` file in Arduino IDE.
3. Select the appropriate Arduino board and COM port.
4. Upload the program.
5. Observe the LED.
6. Verify that the LED turns ON and OFF at approximately 1-second intervals.

## 8. QA Process

GitHub Issues were used to document problems identified during
development and testing.

Each issue included:

- Problem description
- Expected behaviour
- Observed behaviour
- Severity
- Root cause
- Proposed solution
- Verification procedure

## 9. GitHub Workflow

The project used:

- GitHub Issues for problem tracking
- Branches for implementing fixes
- Commits for recording changes
- Pull Requests for reviewing and merging changes
- Issue references for traceability

## 10. QA Issues

- Issue #1 – LED blinking interval
- Issue #2 – GPIO initialization
- Issue #3 – LED pin configuration
- Issue #4 – Project documentation

## 11. Learning Outcome

This project demonstrated how GitHub can be used to improve
documentation, traceability, issue tracking and collaborative
problem solving in an embedded-system project.
