# Invoice_Extraction_OCR
Here is an outline of the steps you can take to build a solution to extract the specified entities from invoice images:

# 1) Prepare the dataset:
Split the dataset into training and testing sets.
# 2) Annotate the training images:
Use an annotation tool of your choice I have used labelImg
Save the annotations as a csv file containing the image filenames and their corresponding labels.
# 3) Train a machine learning model on the annotated dataset:
Choose a suitable machine learning model for the task (e.g. object detection, OCR, etc.).
we are using yolov5 model
Preprocess the images and labels for training.
Train the model on the training set.
# 4) Prepare an inference script:
Load the trained model.
Preprocess the test images.
Run the test images through the model and obtain the predicted labels.
Save the predicted labels as a csv file.
# 5) Plot the results over the test images:
Load the test images.
Load the predicted labels.
Draw bounding boxes around the predicted entities on the test images.
Display the annotated test images with the predicted entities.
