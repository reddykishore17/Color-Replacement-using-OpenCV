# Color Detection and Replacement using OpenCV

## Project Overview
This mini project focuses on detecting and modifying a specific color in images or live video streams using OpenCV.  
It uses computer vision techniques to isolate a target color range, create a mask, and replace that color dynamically with another, enabling visually appealing transformations and effects.

This concept is inspired by the **green screen (chroma key)** technique widely used in movie production, video editing, and visual effects, where a particular background color (often green or blue) is replaced with another image or scene.

## Technologies Used
- Python – Programming and logic implementation  
- OpenCV – Image and video processing  
- NumPy – Array manipulation and numerical operations  

## Key Features
- Detects and isolates target colors in a live video or image  
- Replaces the detected colors with a new color in real time  
- Uses the HSV color space for robust and accurate color segmentation  
- Demonstrates how to use masks and kernels to refine image processing  
- Provides an interactive and visual understanding of color detection principles  

## How It Works
1. The video frames are read and converted from BGR to HSV color space.  
2. A color range is defined (using HSV values) to create a binary mask.  
3. The mask isolates regions containing the target color.  
4. The selected colors is replaced with a new color of choice.  
5. The processed frame is displayed in real time, showing the transformation effect.  

## Real-World Applications
- **Green Screen (Chroma Keying):** Replacing colored backgrounds with other visuals, as used in movie editing and VFX  
- **Image and Video Filters:** Building color-based filters for creative applications  
- **Augmented Reality (AR):** Tracking and modifying color-based objects in real time  
- **Object Tracking:** Detecting and following objects of a specific color for robotics or automation projects  


## Project Highlights
- Helps understand fundamental computer vision and image segmentation techniques  
- Serves as a foundational project for more advanced ML and vision-based systems  
- Showcases how color spaces, masking, and bitwise operations combine to achieve real-world visual effects  

