![IMG_6832](https://github.com/user-attachments/assets/efb1f750-c7e9-4606-997c-4385db00b7a5)
# smart-home-
A smart home system designed to monitor and control actuators according to the measurements recorded by different sensors to sustain the required garden environment, while also implementing a password-based authentication mechanism to ensure authorized access.

Components Used:

- Controller:
• Arduino UNO

- Sensors:
• IR sensor    • LM35 sensor (temperature sensor)     • LDR sensor

- Actuators: 
• Servo Motor   • Fan      • LEDs

- User Interface:
• LCD       • Keypad.

System Operation:

- Initialization: 
Upon system startup, the Arduino board initializes all
components, including sensors, actuators, keypad,
and LCD.

- Garden Access Control: 
When motion is detected in the garden area by the
IR sensor, the system triggers the access control
mechanism. The servo motor opens the garden
door, allowing access to the garden. 

- Password Authentication: 
After detecting motion and opening the door, the
system prompts the user to enter a password via the
keypad. The entered password is compared against
a predefined password stored in the system. If the
password matches, access to the garden is granted,
and the system proceeds to monitor and control
garden conditions. If the password is incorrect, the
system provides visual and auditory feedback,
indicating a wrong password entry, and continues to
prompt the user until a correct password is entered.

- Garden Environment Monitoring: 
The system continuously monitors environmental
conditions in the garden using sensors. The LM35
temperature sensor measures the temperature, and
the cooling fan is activated if the temperature
exceeds a specified threshold. The LDR measures
ambient light levels, adjusting the brightness of the
garden lighting accordingly.
