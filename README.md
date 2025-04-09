# WeighScan AI

## Overview
WeighScan AI is an intelligent, AI-driven web application that estimates the weight of materials such as steel sheets and paddy bags using image and video analysis. By leveraging machine learning and image processing, WeighScan AI eliminates the need for traditional weighing scales, ensuring accurate and tamper-proof material weight estimation.

## Features
- **AI-powered Object Detection**: Automatically detects and counts sheets/bags from images and videos.
- **Real-time Scanning**: Supports live scanning via webcam.
- **Material Weight Estimation**: Calculates weight based on density, volume, and specific gravity.
- **Tare Weight Adjustment**: Automatically subtracts the container/vehicle weight.
- **Gradio UI Interface**: User-friendly interface with image, video, and real-time scan options.
- **Industrial Applications**: Ideal for warehouses, construction sites, and quality control.

## Technologies Used
- **Python** (Google Colab environment)
- **Gradio** (for user interface)
- **OpenCV** (for image and video processing)
- **Ultralytics YOLO** (for object detection)
- **NumPy & Pandas** (for calculations and data handling)

## How It Works
1. **Upload an Image/Video** or use the live scanning feature.
2. **Select Material Type** (e.g., Steel, Paddy Bags) and enter its density & specific gravity.
3. **Define Dimensions** (Length, Width, Height) of the material/container.
4. **Tare Weight Adjustment**: Enter the weight of the container or vehicle.
5. **Weight Calculation**: The app computes the estimated weight and displays the result.

## Installation & Setup
1. Open **Google Colab** and install dependencies:
   ```sh
   !pip install ultralytics gradio opencv-python numpy
   ```
2. Upload the WeighScan AI script and run it.
3. Open the Gradio UI link and start testing with images or video.

## Future Enhancements
- Integration with **RFID/barcode scanning** for inventory tracking.
- Support for **multiple materials** and custom material database.
- **Mobile App version** for field operations.
- **Cloud-based data storage & reporting dashboard**.

## Contribution
We welcome contributions! Feel free to fork the project, report issues, or suggest enhancements.

## License
This project is licensed under the Apache License 2.0.

---
🚀 **WeighScan AI: Revolutionizing Industrial Weighing with AI & Computer Vision!**

![Screenshot 2025-04-09 221818](https://github.com/user-attachments/assets/fa3a1616-4905-479f-83c7-18f72cb3b502)
![Screenshot 2025-04-09 221827](https://github.com/user-attachments/assets/b98fd64e-ba8d-4606-ace0-8017c0d1a352)
