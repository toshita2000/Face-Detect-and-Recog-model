# Face-Detect-and-Recog-model
Face Recognition system 
Recognition is done by LBPH recogniser. Local Binary Pattern (LBP) is a simple yet very efficient texture operator which labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number. LBPH is one of the easiest face recognition algorithms. It can represent local features in the images. It is possible to get great results (mainly in a controlled environment). It is robust against monotonic gray scale transformations. It is provided by the OpenCV library (Open Source Computer Vision Library).
The face recognition systems can operate basically in two modes:
Verification or authentication of a facial image: it basically compares the input facial image with the facial image related to the user which is requiring the authentication. It is basically a 1x1 comparison.Identification or facial recognition: it basically compares the input facial image with all facial images from a dataset with the aim to find the user that matches that face. It is basically a 1xN comparison.
# There are different types of face recognition algorithms, for example:
Eigenfaces (1991)
Local Binary Patterns Histograms (LBPH) (1996)
Fisherfaces (1997)
Scale Invariant Feature Transform (SIFT) (1999)
Speed Up Robust Features (SURF) (2006)
Each method has a different approach to extract the image information and perform the matching with the input image. However, the methods Eigenfaces and Fisherfaces have a similar approach as well as the SIFT and SURF methods.

# Parameters: the LBPH uses 4 parameters:
Radius: the radius is used to build the circular local binary pattern and represents the radius around the central pixel. It is usually set to 1.
Neighbors: the number of sample points to build the circular local binary pattern. Keep in mind: the more sample points you include, the higher the computational cost. It is usually set to 8.
Grid X: the number of cells in the horizontal direction. The more cells, the finer the grid, the higher the dimensionality of the resulting feature vector. It is usually set to 8.
Grid Y: the number of cells in the vertical direction. The more cells, the finer the grid, the higher the dimensionality of the resulting feature vector. It is usually set to 8.
