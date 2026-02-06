# RGB LED Control using Arduino

This is a simple IoT & Robotics beginner project to control an RGB LED using Arduino.

## 🔴🟢🔵 Project Description
In this project, an RGB LED is controlled using Arduino by turning ON and OFF the Red, Green, and Blue LEDs individually and in combinations.  
This project helps beginners understand:
- Digital output
- PWM (analogWrite)
- RGB color mixing

## 🛠 Components Used
- Arduino Uno
- RGB LED (Common Cathode)
- 3 × 220Ω Resistors
- Breadboard
- Jumper Wires

## 🔌 Pin Connections
| RGB LED Pin | Arduino Pin |
|------------|------------|
| Red        | 9          |
| Green      | 10         |
| Blue       | 11         |
| Common     | GND        |

## 💻 Code Explanation
- `digitalWrite()` is used to turn ON/OFF individual colors
- `analogWrite()` is used to mix colors using PWM
- `delay()` is used to hold each color for some time

## 🌈 Output
- Red color
- Green color
- Blue color
- Mixed colors like Purple, Yellow, and Cyan

