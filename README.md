This project is a prototype of face recognition program used for a hackthon. This program can be used for small set of people and works impressively good. It is a very easy for the reader who has a basic understanding of CNN algorithm.
This file contains 3 important sub-files
1. Sample_collection- This program uses opencv to focus on the person sitting in front of the camera and capture image samples.
2. Face_recognition- This program is used to filter and train the model for the given sets of sample images captured from the pervious program file.
3. Facefrontend- This program is used to take the .H5 model file created by the "Face_recognition" program.Collect the test samples on the run and predict the faces which was configured.
