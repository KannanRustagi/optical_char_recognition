## Problem Statement - ML-based OCR
<br>
Optical Character Recognition or OCR is a technology that enables the conversion of printed or handwritten text into machine readable text. OCR is used to extract text from various sources such as scanned documents, images, or even videos, and convert it into
editable and searchable formats.<br>
The process of OCR involves several steps such as scanning the input document or image, segregating individual characters based on
predefined patterns and recognizing them by comparing characters with some known character database or by using machine
learning.<br>
<br>
ML techniques can be employed in different stages of OCR, such as image preprocessing, text localization, character segmentation,
and character recognition.<br>
For our case, the training phase involves feeding the algorithms with labeled examples of characters, allowing them to learn the
relationships and features that distinguish different characters. During the recognition phase, the ML models apply the learned
knowledge to recognize and classify characters in new inputs.<br>
The given dataset contains 1000 images and each image contains 5 characters which are all alphabets. Our objective is to split the
image into the characters and do character recognition. In the end, using the trained model we will try to predict characters in different
images entirely and thereby checking the robustness of our system in recognition phase.<br>
<br>
As mentioned above, we want to identify the characters from the image. For accomplishing this, we have trained the model using various
ML algorithms such as Logistic Regression, Support Vector Machine, Decision Trees, Random Forest for the classification task.<br>


