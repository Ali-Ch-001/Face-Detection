# Face Detection Script

## Description
This is a simple face detection script that uses Google Colab to capture a photo from your webcam, detect faces in the image using the dlib library, and display the image with rectangles drawn around detected faces.

## Requirements
- Google Colab
- dlib
- OpenCV
- numpy

## Image
![](https://github.com/Ali-Ch-001/Face-Detection/assets/108975862/de2f32e7-b976-470c-9e48-61eb06e1dfba)


## Installation
To use this script, you'll need to have the necessary libraries installed in your Google Colab environment. You can install them using the following commands:

```python
!pip install dlib
!pip install opencv-python
!pip install numpy
```

## Usage

	1.	Take a Photo: The script uses your webcam to capture a photo. Ensure you have a working webcam and grant the necessary permissions to access it.
	2.	Detect Faces: The captured photo is processed to detect faces using the dlib library.
	3.	Display the Result: The script draws rectangles around detected faces and displays the image.

## Steps

	•	Step 1: Clone the repository or copy the script into a new Python notebook in Google Colab.
	•	Step 2: Ensure you have the necessary libraries installed as mentioned in the Installation section.
	•	Step 3: Run the script in Google Colab. Follow the prompts to capture a photo using your webcam.
	•	Step 4: The script will process the image and display it with rectangles around detected faces.
