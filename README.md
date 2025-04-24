# -NEURAL-STYLE-TRANSFER

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: CHINTAM VIJAYA LAKSHMI

*INTERN ID*: CT06WC94

*DOMAIN*: ARTIFICIAL INTELLIGENCE

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTHOS

#INTERNSHIP TASK-3
#IMPLEMENT A NEURAL STYLE TRANSFER MODEL TO APPLY ARTISTIC STYLES TO PHOTOGRAPHS
#DELIVERABLE: A PYTHON SCRIPT OR NOTEBOOK WITH EXAMPLES OF STYLED IMAGES 
#TensorFlow Hub is an open repository and library for reusable machine learning.
#Pyplot is a collection of functions in the popular visualization package Matplotlib. 
#It functions manipulate elements of a figure, such as creating a figure, creating a plotting area
#The'import cv2' statement brings the OpenCV library into the Python script, allowing access to its functions for computer vision and image processing
#PIL is the Python Imaging Library which provides the python interpreter with image editing capabilities
#Loads image as an encoded array of bytes
#This operation returns a tensor with the entire contents of the input filename
#detects whether an image is a BMP, GIF and performs the appropriate operation to convert the input bytes string into a Tensor of type uint8
#Convert image to dtype, scaling its values if needed.
#tf.newaxis enables us to add a dimension to our tensor while keeping the same information available
#Scale the tensor values from [0, 1] to [0, 255]
#Convert the tensor to a NumPy array of type uint8 (unsigned 8-bit integer)
#Check if the tensor has more than 3 dimensions
#Ensure that the first dimension (batch size) is 1
#Remove the first dimension to get a single image
#Convert the NumPy array to a PIL Image and return it
#Load the content image from the specified file path
#Load the STYLE image from the specified file path
#Get the shape (dimensions) of the content image
#Get the shape (dimensions) of the style image
#Display the style image using Matplotlib
#Show the plot with the displayed image
#Display the content image using Matplotlib
#Show the plot with the displayed image
#Load the pre-trained image stylization model from TensorFlow Hub
#Apply the stylization model to the content and style images
#Convert the images to TensorFlow constants and get the stylized output
#Convert the stylized tensor to a PIL Image for visualization

#REFERENCE PIC 
![Image](https://github.com/user-attachments/assets/b5d930fb-ed99-4d1f-8607-fe472153fa88)
![Image](https://github.com/user-attachments/assets/655ec904-1cac-425a-a6d4-c5c9b8bb156b)
