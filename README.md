
# pH Sensor Arduino Calibration

Welcome to the pH Sensor Arduino Calibration repository!

This repository contains resources and code for calibrating pH sensors using Arduino microcontrollers. pH sensors are widely used in various applications such as water quality monitoring, hydroponics, aquaponics, and scientific research. Calibration is essential to ensure accurate pH measurements, as sensor readings can drift over time or vary depending on environmental conditions.

## Setup 
PH Limit: This potentiometer is to sets a limit value of the pH sensor circuit that causes the red LED to light up and the Do pin signal to turn ON.

Connect Po to Analog input A0 on Arduino, and G to Arduino GND. Run the given Arduino sketch below, and open the Serial Monitor of Arduino IDE to observe the reading, slowly adjust the potentiometer RV1 (the one near the BNC connector on the board) until the Po reading is equal to 2.50v.**

Happy pH sensing! 🌊🔬
