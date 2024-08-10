# detects a face
Use arduino to switch ON a LED when the HuskyLens detects a face


## 1. Setup the Hardware:


- Components Needed: Arduino board, HuskyLens AI Camera, LED, and jumper wires.

  
- Connect HuskyLens:

  
   -Connect the HuskyLens to the Arduino using jumper wires. HuskyLens typically communicates using the I2C protocol

  
## 2. Install the HuskyLens Arduino Library:


- Ensure you have the HuskyLens library installed in the Arduino IDE.


- Go to Sketch > Include Library > Manage Libraries and search for "HuskyLens." Install the library.

## 3. Write the Arduino Code:

- Initialize communication between the Arduino and the HuskyLens in the code.


- Set up the LED pin as an output.


- In the loop, continuously check if HuskyLens detects a face. If a face is detected, turn on the LED.


<img width="388" alt="image" src="https://github.com/user-attachments/assets/55b12f14-3198-4990-b0ef-fedd4dcc10b0">


## 4. Test the System:

- Once the code is uploaded, bring the HuskyLens in front of a face.


- If the HuskyLens detects a face, the Arduino will receive the signal, and the LED should light up.


- If the face is no longer detected, the LED will turn off.


![صورة واتساب بتاريخ 1446-02-05 في 15 38 39_704197c7](https://github.com/user-attachments/assets/4bb8c396-7eef-4c51-a6a8-25858ac73b68)



