# AI_virtual_mouse
Creating a virtual mouse using Mediapipe involves utilizing hand tracking to control the mouse cursor's movement and clicks. Here's a simple README file to guide you through the process:

---

# Virtual Mouse Using Mediapipe

This project demonstrates how to create a virtual mouse using the Mediapipe library for hand tracking. The hand movements are tracked using the Mediapipe Hand module and translated into mouse cursor movement and clicks.

## Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)
- Mediapipe (`pip install mediapipe`)
- PyAutoGUI (`pip install pyautogui`)

## Usage

1. Clone this repository to your local machine.
   
```bash
git clone https://github.com/yourusername/virtual-mouse.git
```

2. Navigate to the project directory.

```bash
cd virtual-mouse
```

3. Run the `virtual_mouse.py` script.

```bash
python virtual_mouse.py
```

4. A window will open showing your webcam feed with hand tracking landmarks. Move your hand within the frame to control the mouse cursor.

5. Gestures:
   - Move your index finger to control the cursor's movement.
   - Make a "click" gesture by closing your index finger and thumb.
   - Make a "right-click" gesture by closing your middle finger and thumb.

6. Press `Esc` to exit the application.

## Customization

You can customize the behavior of the virtual mouse by modifying the following parameters in the `virtual_mouse.py` script:

- `MOVEMENT_SPEED`: Adjust the speed of cursor movement.
- `CLICK_THRESHOLD`: Set the distance at which a click is registered.
- `RIGHT_CLICK_THRESHOLD`: Set the distance at which a right-click is registered.
- `CAMERA_INDEX`: If you have multiple cameras, adjust the index to select the desired camera.

## Acknowledgments

This project is built upon the Mediapipe library by Google. For more information about Mediapipe and its capabilities, refer to the official documentation: [Mediapipe Documentation](https://google.github.io/mediapipe/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Remember to replace `"yourusername"` in the repository URL with your actual GitHub username if you plan to host the code on your GitHub repository.

This README provides a basic guide to get you started. Depending on your requirements, you can further enhance the project by adding more gestures, refining cursor control, or integrating other functionalities.
