# DOTSALGO
# overview
This web-based application allows users to generate SVG (Scalable Vector Graphics) images using dots algorithm. The tool supports both image selection and webcam usage for input, and it provides a convenient interface to adjust algorithm parameters.
# Features
-Image and Webcam Modes: Choose between selecting an image from your device or using your webcam as the input source.
-Canvas Size: Adjust the width and height of the canvas to suit your requirements.
-Background Removal: For webcam input, the tool utilizes the Remove.bg API to remove the background, providing a clean input image.
-Algorithm Selection: Choose from different algorithms (currently supports the dots algorithm) to visualize and generate SVG images.
-Interactive Parameters: Adjust algorithm parameters using sliders and other input controls for real-time feedback.
-SVG Preview: Visualize the SVG output in real-time, with the ability to download the generated SVG file.
-AxiDraw Integration: Integrate with the AxiDraw pen plotter by providing an AxiDraw API endpoint. A button is available to send the SVG data to the AxiDraw for printing
# How to Use
-Select Image or Use Webcam:

Click the "Image" tab to upload an image or the "Use Webcam" tab to use your webcam as the input source.
Adjust the canvas width and height as needed.
Adjust Parameters:

-Choose the desired algorithm from the dropdown menu.
Adjust algorithm-specific parameters using the provided controls.
Click the "Use Image" button to apply changes.
Preview and Download:

-Visualize the SVG output in real-time.
Click the "Download SVG" button to download the generated SVG file.
Print with AxiDraw:

-Axicli 
Used Axicli to connect or communicate with the penplotterS

# Additional Notes
-This tool utilizes the Remove.bg API for background removal. Ensure a stable internet connection for optimal functionality.

# Credits
Remove.bg API: https://www.remove.bg/
AxiDraw Pen Plotter: https://www.axidraw.com/
AxiCli : https://axidraw.com/doc/cli_api/#introduction
