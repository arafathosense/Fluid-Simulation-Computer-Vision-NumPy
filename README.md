# Fluid Simulation 

This project is an interactive fluid simulation with real-time hand tracking using Computer Vision, OpenCV and NumPy. The simulation allows users to manipulate a 3D fluid cube with hand gestures captured from a webcam. Built by **HOSEN ARAFAT**, it opens your webcam, tracks one hand with MediaPipe, and injects energy into a 2D stable-fluid solver so it feels like you are stirring a cube filled with glowing fluid.

## Features

- Real-time 2D fluid simulation with adjustable parameters
- Hand tracking using webcam input
- Interactive injection of fluid and velocity based on hand movement
- 3D cube projection with fluid texture mapping
- Visual effects including vignette, sharpening, and stylized background
- Displays simulation parameters, hand info, and FPS

## Repository Structure

├── fluid_sim.py

├── hand_tracking.py

├── main.py        

├── requirements.txt     

├── README.md       

├── LICENCE                        

## Requirements

- Python 3.11+
- OpenCV (`cv2`)
- NumPy
- Optional: Numba for improved performance
- Compatible webcam

Install dependencies using:

```bash
pip install opencv-python mediapipe numpy numba
````

## Usage

Run the simulation with the default webcam:

```bash
python main.py
```
# Output
<img width="1365" height="726" alt="image" src="https://github.com/user-attachments/assets/4bb0a46b-7488-42c1-9148-f4b905c02ddc" />
<img width="1365" height="727" alt="image" src="https://github.com/user-attachments/assets/f5bdbe53-2f46-4938-81b4-60606f2dcbbb" />
<img width="1365" height="726" alt="image" src="https://github.com/user-attachments/assets/4a3f29dc-38a1-4b4e-a847-73983ca80bff" />



### Controls

**`ESC` or `q`: Quit the simulation**



## Notes

* Ensure your webcam is accessible
* For optimal performance, Numba acceleration is recommended
* The simulation dynamically adjusts cube position, rotation, and scale based on hand gestures


 ## Author
 
 **HOSEN ARAFAT** 
 
 **Repo:** https://github.com/arafathosense/Brain-Tumor-Detection-Data-Science
 
**If anyone wants a walkthrough or explanation, feel free to reach out!**


