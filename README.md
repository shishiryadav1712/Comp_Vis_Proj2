# Comp_Vis_Proj2



# Computer Vision Project 2 - Edge Detection and Shape Recognition

## Overview
This project is implemented in a single Jupyter Notebook file, `Proj2.ipynb`, This project implements key computer vision algorithms, such as edge detection, corner detection, and shape recognition through the Hough transform. It also features interactive boundary tracing and circle detection functionalities.

## Prerequisites
To run this project, you will need the following:

- **Python 3.x** (Recommended version: 3.6 or above)
- Required Python libraries:
- Python 3.8+
- NumPy
- OpenCV (cv2)
- Matplotlib
- Pillow (PIL)
- SciPy


### Installing Dependencies
If you don't have the required libraries installed, you can install them using the following command:

```bash
pip install numpy matplotlib pillow opencv-python scipy jupyter
```

## How to Run the Project
1. **Open the Jupyter Notebook**:
   Navigate to the directory where `Proj2.ipynb` is located and start the Jupyter Notebook server by running:

   ```bash
   jupyter notebook
   ```

2. **Open `Proj2.ipynb`**:
   In the Jupyter Notebook interface that opens in your browser, locate and open the `Proj2.ipynb` file.

3. **Run Each Cell Sequentially**:
   - The notebook is structured such that each problem is handled in separate cells.
   - You can run each cell sequentially using the `Shift + Enter` command or by selecting `Run` from the toolbar.

4. **Review the Output and Observations**:
   - Each problem has corresponding outputs (images and visualizations) displayed below the respective code cells.
   - Observations and conclusions are documented within the notebook for each problem.

## Project Structure
The project files are organized as follows:

```


├── README.md            #Readme file
├── 1.png                # Image for Problem 1
├── 2-1.jpg              # Image for Problem 2 (Subproblem 1)
├── 2-2.jpg              # Image for Problem 2 (Subproblem 2)
├── 3.png                # Image for Problem 3 (Subproblem 1)
├── train.png            # Training image for Problem 3 (Subproblem 2)
├── test.png             # Test image for Problem 3 (Subproblem 2)
├── train.mat            # Data file for Problem 3 (Subproblem 2)
├── Proj2.ipynb          # Jupyter Notebook for the entire project
├── Output 1 -1.png      # Output of Problem 1 (Subproblem 1)
├── Output 1 -2.png      # Output of Problem 1 (Subproblem 2)
├── output-2.png         # Output for Problem 2
├── output 3-1.png       # Output for Problem 3 (Subproblem 1)
├── output 3-2.png       # Output for Problem 3 (Subproblem 2)
├── Cv_ProjectReport2_Shishir.pdf  # Full project report
```

- The file `Proj2.ipynb` contains the code and solutions for all the problems.
- There multiple images used in this project , which are used in following way 
In Problem 1, there is one image, 1.png, which will be used for both Subproblem 1 and Subproblem 2.
In Problem 2, there are two images, 2-1.jpg and 2-2.jpg, please conduct Corner Point Detection for both.
In Problem 3, use 3.png for Subproblem 1, and test.png, train.png, and train.mat for Subproblem 2.
- The comments in projectt structure section describes which image is output of which problem . The output images generated for each problem, stored for reference.
- `README.md` provides instructions on running the project.
- Cv_ProjectReport2_Shishir.pdf provides a detail report about the project 1.

## Additional Notes
- Ensure that the all the images provided are in the same directory as the `Proj2.ipynb` file to avoid any issues with loading the image.
- The notebook is self-contained, and all outputs will be displayed inline when run in the Jupyter environment.
 # Note 
 To run the problem 1 subproblem 2 , we need to press "q" to complete the selction of points and to get the output for it.


