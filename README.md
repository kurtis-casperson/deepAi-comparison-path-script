# deepAi-comparison-path-script

DeepAi https://deepai.org/machine-learning-model/image-similarity has an Image Similarity API that compares two images and returns a value that tells you how visually similar they are.
The lower the the score, the more contextually similar the two images are with a score of '0' being identical.  

I used this post script in tandem with an end-to-end testing framework to compare snapShots of the Edge app, in edge-react-gui.

This script is specific for testing images on iOS, but can be modified simply.

The script creates a realtive directory path if one does not already exist. Then reads the absolute path, where the images are saved during the test,
and copies the images to the relative path if they do not exist.

The API then compares each set of images based on the path names and prints the result of the similarity.

