# Check-fruit-quality-with-your-virtual-IoT-device

## Requirements
- To properly run counterFit, please refer [requirements](https://github.com/jacjac1001/Check-fruit-quality-with-your-virtual-IoT-device/blob/main/requirements.txt).
- Create a Python virtual environment.
- Install the following libraries:
````
pip install azure-cognitiveservices-vision-customvision
````
````
pip install counterfit-shims-picamera
````

## Code and run your app.py
Source code: [app.py](https://github.com/jacjac1001/Check-fruit-quality-with-your-virtual-IoT-device/blob/main/app.py)

- After pasting the code, do not click "run code" but you need to open two seperate terminals.
- In the first terminal, type in:
````
counterfit
````
- Your counterFit will now run on port 5000: 
````
http://127.0.0.1:5000
````

## counterFIt webapp
- Ignore the 'Actuators' section.
- In the 'Sensors' section, in the sensor type, choose 'camera'
- Name it 'Picamera'
You can either add a file in your computer or use your built-in webcam.
### Import file from your computer
- Your image must be .jpg, .png, .bmp, or .gif format
