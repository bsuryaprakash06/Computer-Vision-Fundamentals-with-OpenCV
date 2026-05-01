# Computer-Vision-Fundamentals-with-OpenCV

This project demonstrates fundamental image processing techniques using OpenCV in Python. Through this work, I learned how to read and manipulate images, understand image representations (grayscale, RGB, and HSV), perform basic transformations such as cropping, resizing, and flipping, and apply operations like brightness and contrast adjustment. I also explored color space conversions, channel splitting and merging, and simple image annotation using text and shapes.

## Features

* Read and display images in grayscale and color formats
* Convert between BGR, RGB, and HSV color spaces
* Extract image properties such as width, height, and channels
* Crop, resize, and flip images
* Adjust brightness and contrast
* Split and merge color channels (BGR and HSV)
* Add text and draw shapes on images
* Save processed images

## Technologies Used

* Python
* OpenCV (cv2)
* NumPy
* Matplotlib
* Jupyter Notebook

## Project Structure

* `OpenCV-Introduction.ipynb` – main notebook file
* `Eagle_in_Flight.jpg` – used for grayscale conversion and transformations
* `Apollo-11-launch.jpg` – used for annotation and drawing
* `boy.jpg` – used for brightness, contrast, and channel operations

## How to Run

1. Install required libraries:

   ```
   pip install opencv-python numpy matplotlib notebook
   ```

2. Launch Jupyter Notebook:

   ```
   jupyter notebook
   ```

3. Open the `.ipynb` file and run all cells.

## Output

### Original Image & Cropped Image

<table>
<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/1fa17d8f-0551-4d43-8805-06346d1bd019" width="350"/><br>
Original Image
</td>
<td align="center">
<img width="367" height="369" alt="{5F59CAA8-DD13-4128-B31F-3C3E25851917}" src="https://github.com/user-attachments/assets/96b03da7-76e6-4dd1-aa7f-523345ab58fe" /><br>
Cropped Image
</td>
</tr>
</table>

### Original Image & Annotated Image

<table>
<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/5ceb573c-0393-4977-ba23-47e60afa4352" width="350"/><br>
Original Image
</td>
<td align="center">
<img src="https://github.com/user-attachments/assets/9ab96a7c-ae24-4648-8bf8-15f650dd77b0" width="350"/><br>
Annotated Image
</td>
</tr>
</table>

### Adjusting Brightness
<img width="1085" height="261" alt="{3E7E5D4F-7261-4C15-899D-6E92EECA05D1}" src="https://github.com/user-attachments/assets/ccb0ceea-12e6-41bc-a822-30509fac102d" />

### Adjusting Contrast
<img width="1085" height="258" alt="{8A901E7A-26DF-4B25-B558-D2763A35F1D6}" src="https://github.com/user-attachments/assets/65176285-6006-41dc-8ab4-e1547e4c26f5" />



## Conclusion

This project provides a strong foundation in computer vision by covering essential image processing operations and demonstrating how images can be analyzed and manipulated using OpenCV.
