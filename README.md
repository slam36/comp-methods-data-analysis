# Various Projects from UW AMATH 482: Computational Methods for Data Analysis 

This repo contains my reports for the projects in a computational methods for data analysis course I took at the university of washington. This was by far my favorite class in my undergraduate career, and played a huge role in developing my curiosity for data science and machine learning.

Note: All of the code is in the appendix of the reports. Unfortunately I do not have access to some of the data files anymore. 

### SVD_Image_Processing
This report investigates the use of singular value decomposition for analyzing the cropped images of the Extended Yale Faces Database B. The goal was to explore the SVD algorithm and its use for image compression and reconstruction.

### Motion Tracking
This report investigates the use of principal component analysis (PCA) to empirically extract the governing equations of the motion of a spring-mass system. Multiple cameras were used to record the system at different angles and positions to capture the full dynamics of the system. The role of principal component analysis was to produce low-dimensional reductions of the dynamics and behaviors of the system from noisy, seemingly complex and random data.

### Music Genre Identification
This report investigates the application of the Linear Discriminant Analysis classification algorithm to differentiate between music genres. This algorithm uses a probabilistic approach to a sample training data set to classify new cases/data. The results show the simplicity and robustness of the LDA algorithm. The mp3 files are pre-processed with a Fourier and Gabor transform to create a spectrogram containing time and frequency resolution.

### Dynamic Mode Decomposition
This report investigates the use of dynamic mode decomposition (DMD) for separating video background and foreground. The background is the approximate low rank DMD reconstruction, and the foreground is the approximate sparse DMD reconstruction. The DMD method is very robust and fast, and can be used in applications that require video to be separated in real time. One application of this is for security cameras.

### Neural Network From Scratch
This report documents the process of implementing a feedforward neural network including back propagation from scratch using Matlab. In the report, the neural network was used to classify handwritten numbers from the MNIST database, but this code can be used for any dataset and can be easily extended to include other activation and loss functions.






