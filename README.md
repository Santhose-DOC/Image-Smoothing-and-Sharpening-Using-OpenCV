# Image-Smoothing-and-Sharpening-Using-OpenCV

## Aim

To write a Python program using OpenCV to apply different smoothing filters (Averaging, Weighted Averaging, Gaussian, and Median) and sharpening filters (Laplacian Kernel and Laplacian Operator) for image enhancement.

## Software Used

- Anaconda – Python 3.7
- Jupyter Notebook / VS Code
- OpenCV (`cv2`)
- NumPy
- Matplotlib

## Algorithm

### Step 1: Import Libraries
Import the required libraries: OpenCV, NumPy, and Matplotlib.

### Step 2: Load the Image
Read the input image using `cv2.imread()`.

### Step 3: Convert Image
Convert the image from BGR to RGB format for proper display using Matplotlib.

### Step 4: Averaging Filter
- Apply the averaging filter using `cv2.blur()`.
- Reduce image noise by averaging neighboring pixel values.
- Display the filtered image.

### Step 5: Weighted Averaging Filter
- Create a custom weighted averaging kernel.
- Apply the filter using `cv2.filter2D()`.
- Display the filtered image.

### Step 6: Gaussian Filter
- Apply Gaussian smoothing using `cv2.GaussianBlur()`.
- Reduce noise using Gaussian-weighted pixel values.
- Display the filtered image.

### Step 7: Median Filter
- Apply median filtering using `cv2.medianBlur()`.
- Replace each pixel with the median value of its neighborhood.
- Display the filtered image.

### Step 8: Laplacian Sharpening Using Kernel
- Define a Laplacian sharpening kernel.
- Apply the kernel using `cv2.filter2D()`.
- Enhance image edges and fine details.
- Display the sharpened image.

### Step 9: Laplacian Operator
- Convert the original image into grayscale.
- Apply the Laplacian operator using `cv2.Laplacian()`.
- Detect edges and image details.
- Display the resulting image.

### Step 10: Display Results
Display the original image and all filtered images using Matplotlib in a grid layout for comparison.

## Program

**Developed By:** Santhose Arockiraj J

**Register Number:** 212224230248

**Program File:** `EXP5.ipynb`

## Output

### 1. Averaging Filter

- Averaging filter produces a blurred image by averaging neighboring pixels.

<img width="571" height="378" alt="image" src="https://github.com/user-attachments/assets/61c72cfa-0a6b-4284-bbf4-9c29a06493ef" />


### 2. Weighted Averaging Filter

- Weighted averaging provides a smoother result using a custom kernel.

<img width="571" height="378" alt="image" src="https://github.com/user-attachments/assets/3b6aa632-e5fd-4e4d-874a-7564a02a3555" />


### 3. Gaussian Filter

- Gaussian filter reduces noise while preserving important image features.

<img width="571" height="378" alt="image" src="https://github.com/user-attachments/assets/8468e2ac-d7af-4a0b-ad0e-1634caa3a1eb" />


### 4. Median Filter

- Median filter removes salt-and-pepper noise effectively.

<img width="571" height="378" alt="image" src="https://github.com/user-attachments/assets/26e1287d-a68d-4700-9a97-087644de4731" />


### 5. Laplacian Sharpening Using Kernel

- Laplacian kernel enhances edges and fine details.

<img width="571" height="378" alt="image" src="https://github.com/user-attachments/assets/6e42e3a8-828b-459a-b896-fb8f3d3635a1" />


### 6. Laplacian Operator

- Laplacian operator detects edges clearly in grayscale.

<img width="571" height="378" alt="image" src="https://github.com/user-attachments/assets/da8ea425-4cc8-4898-87f8-c83aad0c9f20" />


## Result

Thus, various smoothing and sharpening filters were successfully implemented using OpenCV.

The smoothing filters reduce noise and improve image quality, while sharpening filters enhance edges and fine details for better image enhancement and feature extraction.
