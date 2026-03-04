# Image Basics Test 12 Assignment

## Overview
In this assignment, you will implement several features to manipulate and display images using Python in Jupyter Notebook. You'll work from the provided starter code to the final solution code.

## Learning Objectives
By completing this assignment, you will learn how to:
- Import and manipulate images using image processing libraries.
- Display images within a Jupyter Notebook.
- Apply transformations to images.

## Your Coding Environment
You will work in a Jupyter Notebook environment. Your workspace consists of the following:
- **Editor Tabs**: Where you will write and modify your code.
- **Run Button**: Click this to execute your code and see the results.
- **Commit Button**: Use this to save your changes for grading.
- **Autograder Feedback**: After committing, check for feedback—look for a ✅ if everything is correct or a ❌ if there are issues.

## Workflow
1. Edit the code in the editor tabs.
2. Click the **Run Button** to execute your changes.
3. Use the **Commit Button** to save your work.
4. Check the feedback from the autograder to see if your implementation is correct.

## Implementation Instructions
### 1. Import Required Libraries
Add the following import statement at the top of your code:  
```python
import matplotlib.pyplot as plt
```

### 2. Load and Display the Image
Modify the code to load and display an image using `plt.imshow()`. Implement the following lines:
```python
image = plt.imread('path/to/image.jpg')  # Load your image
plt.imshow(image)  # Display the image
plt.axis('off')  # Turn off axis labels
plt.show()  # Show the image
```

### 3. Image Transformation
You need to implement a function to transform the image. Define a function called `transform_image()`:
```python
def transform_image(image):
    # Implement your transformation logic here
    return transformed_image
```

### 4. Apply the Transformation
After loading the image, apply the transformation by calling `transform_image(image)`. Don’t forget to display the transformed image as well:
```python
transformed_image = transform_image(image)
plt.imshow(transformed_image)  # Display the transformed image
plt.axis('off')  # Turn off axis labels
plt.show()  # Show the transformed image
```

## Example Usage
Once implemented, running your notebook should display both the original and transformed images. Ensure your image path is correct to avoid file not found errors.

## Hints & Tips
- Make sure the image file path is correct when loading your image.
- Check the function return values to ensure transformations are applied correctly.
- If you encounter visual issues, verify whether the image display settings in `matplotlib` are correctly configured.