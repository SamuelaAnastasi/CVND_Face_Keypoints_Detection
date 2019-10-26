# CVND Face Keypoints Detection  

This project is part of the Udacity's Computer Vision Nanodegree.
It applies through OpenCV, the ORB image algorithm that creates feature vectors from detected keypoints on a subject.  

ORB has some great properties, such as being invariant to rotations, changes in illumination, and noise. In this notebook, we will see these properties in action and implement the ORB algorithm to
detect a person’s face in an image using facial keypoints.

The first step in the ORB algorithm is to locate all the keypoints in the training image. After the keypoints have been located, ORB creates their corresponding binary feature vectors and groups
them together in the ORB descriptor.
