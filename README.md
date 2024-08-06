# Radar with Ultrasonic Sensor and Arduino Code

## Project Description
This project involves developing a radar system using an ultrasonic sensor to detect and measure the distance of objects. The results are visualized on a screen, with the radar's firmware implemented using Arduino code and a Processing-based GUI for visualization.

## Hardware Required
- Arduino board
- Ultrasonic sensor (e.g., HC-SR04)
- Servo motor
- Jumper wires
- Breadboard

## Software Required
- Arduino IDE
- Processing IDE

## How to Use
1. Connect the ultrasonic sensor and servo motor to the Arduino board.
2. Upload the `main.ino` code to the Arduino board.
3. Open the Processing sketch (`visulzation.pde`) and run it.
4. Ensure the correct COM port is set in the Processing code (`myPort = new Serial(this, "COM5", 9600);`).
5. The radar system will visualize the detected objects on the screen using the Processing GUI.

## Code Explanation
The Arduino code rotates the servo motor from 15 to 165 degrees and back, while the ultrasonic sensor measures the distance to objects. The distance and angle are sent to the Serial Monitor and processed by the Processing GUI to visualize the data.
