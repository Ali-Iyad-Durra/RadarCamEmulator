[Download RadarCamEmulator Setup Directly Here](https://github.com/Ali-Iyad-Durra/RadarCamEmulator/releases/download/Radar/RadarCamEmulator.exe)
<img width="598" height="464" alt="Capture" src="https://github.com/user-attachments/assets/ef965dea-98bf-43e0-9da5-d16cf79979f3" />

______________________________________________________________________________________________
RadarCamEmulator: Blue Object Detector 🔵🛰️
RadarCamEmulator is a specialized computer vision tool designed to identify and track blue-colored objects within a camera's field of view in real-time. By leveraging color-space filtering, it isolates specific blue hue ranges and emulates a radar-like tracking system for those targets.
______________________________________________________________________________________________
## 📦 Dependencies

This project requires the following libraries:
* -OpenCV 4.x:** Used for high-speed frame capturing, color space conversion (RGB to HSV), and image masking.
* -C++ Standard:** C++17 or higher.
______________________________________________________________________________________________
🔍 How it Works
The core engine of the emulator follows a streamlined detection pipeline:

1. Frame Capture: Pulls live frames from the connected camera.

2. Color Filtering (HSV): Converts the image from RGB to HSV (Hue, Saturation, Value) to accurately isolate blue shades regardless of lighting conditions.

3. Masking: Generates a binary mask where only the blue objects are visible.

4. Target Emulation: Calculates the coordinates of the detected blue segments and "pings" them on the radar interface.
_____________________________________________________________________________________________
🛠 Features
1. Precise Blue Isolation: Optimized to distinguish between various shades of blue while ignoring background noise.

2. Real-time Tracking: Low-latency detection suitable for fast-moving objects.

3. Dynamic Bounds: Automatically draws bounding boxes or "radar blips" around the detected blue objects.

4. Customizable Thresholds: Simple sliders (or API calls) to adjust the sensitivity of the blue filter.
_____________________________________________________________________________________________
📋 Requirements
1. Camera: Standard Webcam or Integrated Laptop Camera.

2. Lighting: Works best in well-lit environments to maintain color accuracy.

3. Hardware: Optimized for systems with dedicated GPUs (like NVIDIA RTX series) for smoother frame processing.
_____________________________________________________________________________________________
To End The programe Hold ESC Key in the Keybourd
