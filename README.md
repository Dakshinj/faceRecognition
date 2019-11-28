# Face Recognition using Transfer learning
Face recognition falls into 2 categories:

Face verification - check if the person is the correct one (passport verification at the airport).

Face Identification – Who is the person?

Transfer Learning – 2 types of transfer learning:

Fine tuning - Replace a trained neural network’s fully connected layer head and then train

Feature extraction (best suited for face recognition) - Pre-trained neural network serves as a feature extractor.
Allow the input to propagate forward and taking the output from specific layer

# Dataset Used

14 celebrity with 3 more identities

https://www.kaggle.com/danupnelson/14-celebrity-faces-dataset

# Directory Structure

Train data:
dataset/train/identity_1/pictures

Test data:
dataset/test/Identity_1/pictures

video data:

      
# Train Model Used

FaceNet model trained by Hiroki Taniai on MS-Celeb-1M dataset

https://github.com/nyoki-mtl/keras-facenet

# References

[1] https://machinelearningmastery.com/how-to-perform-face-recognition-with-vggface2-convolutional-neural-network-in-keras/
