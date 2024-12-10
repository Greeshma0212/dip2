Weighted Voronoi Image Stippling with GUI in MATLAB
Project Title
Weighted Voronoi Image Stippling with GUI

Team Member
Your Name (if applicable)
Project Overview
This project implements a Weighted Voronoi Image Stippling System using MATLAB. The goal is to generate stippled images by distributing points based on image brightness and visualizing Voronoi diagrams for geometric representation. The system includes a Graphical User Interface (GUI) for ease of use, allowing users to load datasets, define stippling parameters, and view results interactively. The stippling process utilizes pixel brightness for weighted point generation and Voronoi diagram construction.

Features
Dataset Loader: Load a folder containing multiple images for processing.  data set from kaggle : https://www.kaggle.com/datasets/nunenuh/pytorch-challange-flower-dataset
Customizable Stippling Points: Define the number of points for stippling dynamically.
Image Navigation: View processed images with "Previous" and "Next" buttons.
Voronoi Diagram Visualization: Displays geometric cell boundaries over the stippled image.
Status Updates: Provides real-time feedback during image processing.
Output Saving: Saves processed images with stippling and Voronoi overlays into a designated folder.
Dataset
The dataset used for this project consists of high-resolution flower images.

Source: Custom dataset or publicly available image datasets.
Dataset Size: User-defined based on the folder contents.
Contents: .jpg or .png images with rich textures and varied brightness for testing.
Requirements
MATLAB: Version R2021b or higher.
Toolboxes: Image Processing Toolbox.
Operating System: Compatible with Windows, Linux, and macOS.
Installation and Usage


Clone this repository to your local machine:
git clone https://github.com/yourusername/Weighted-Voronoi-Image-Stippling.git


Open MATLAB and navigate to the folder containing the project files.
Run the script weighted_voronoi_gui.m to launch the GUI:
matlab

weighted_voronoi_gui

Steps to follow in the GUI:
Load Dataset: Use the "Browse" button to select a folder of images.
Set Points: Specify the number of stippling points in the input field.
Run Stippling: Click "Run Stippling" to process the images.
Navigate Results: Use the "Previous" and "Next" buttons to view the processed images.
Processed images will be saved in an Output folder inside the selected dataset directory.
Format and Size of Input Images
Supported formats: .jpg, .png.
Images are processed at their original resolution, ensuring accuracy in brightness-based stippling.
Code Overview
This project includes the following main files:

weighted_voronoi_gui.m
Main GUI code that provides functionalities for dataset selection, input parameters, and visualization of results.
generate_weighted_points.m
Function to generate weighted random points based on pixel brightness.
weighted_voronoi_stippling.m
Core stippling algorithm that computes Voronoi diagrams and overlays them on the input image.
process_voronoi_stippling.m
Batch processing script to handle multiple images and save outputs.
Output
The GUI displays:

Original Image: The input image selected from the dataset.

![image](https://github.com/user-attachments/assets/58228c90-9b3f-4fa6-8d37-f13e2d937df1)

Processed Image: Includes stippling points (red dots) and Voronoi overlays (green lines).
Navigation Controls: Interactive buttons to view results for each image.
Output Folder: All processed images are saved with overlays for later use.
Example Outputs
Below are some example outputs generated by the system:

GUI Window


![image](https://github.com/user-attachments/assets/3c39e256-b001-49f3-87cb-4a671dc0ddc5)

Processed Images with Voronoi Overlays
Original Image	Processed Image with Voronoi Overlay



Acknowledgments
This project uses MATLAB for implementation and leverages high-resolution image datasets for testing.








