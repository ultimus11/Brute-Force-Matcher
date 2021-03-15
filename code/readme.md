Youtube video for explaination is here:
https://youtu.be/fswJipI6b_M

Steps:
read query and training images
Initiate SIFT detector
find the keypoints and descriptors with SIFT
BFMatcher with default params
Apply ratio test
cv.drawMatchesKnn expects list of lists as matches.

You can find more about it at 
https://docs.opencv.org/master/dc/dc3/tutorial_py_matcher.html
