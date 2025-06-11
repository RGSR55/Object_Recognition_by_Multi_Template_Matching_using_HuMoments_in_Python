# Object_Recognition_by_Multi_Template_Matching_using_HuMoments_in_Python
This work proposes a template-based detection method using Hu’s moments to classify pictograms and distinguish those that are incomplete, thereby avoiding misclassification.

First, the image is binarized, segmented, and cropped. Then, the seven Hu’s moments are calculated and compared against the feature vectors extracted from template image. Secondly, the Euclidean distance is applied to judge the similarity before finishing the template matching. The identified similarities serve as indicators of object correspondences, thus demonstrating the efficacy of the proposed method across diverse rotations, translations and scalings transformations. The final classification and count results are shown on the test image, with pictograms labeled by category and summarized in a dictionary format.

## Examples

![1](https://github.com/user-attachments/assets/40cb7f71-dff6-463d-9167-9e15e8707d9f)
![2](https://github.com/user-attachments/assets/8c53b825-8109-4f17-8626-48b9d2b2df81)
### Dictionary format
![3](https://github.com/user-attachments/assets/44bc5ed8-e862-41df-8e0c-164f024bd839)

## Usage

1. Clone this repository or download the following files
2. Install Anaconda Prompt
3. Set Up Conda Environment
4. Install the required dependencies  to run the Jupyter notebook
