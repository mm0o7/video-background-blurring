# video-background-blurring
The purpose of this project is to blur the background of a video and detect humans in the video using BodyPix and OpenCV libraries. The project will be implemented using Python programming language.  

**Tools**: The following tools will be used for this project:  
•	Python: for implementation of the code.  
•	OpenCV: for capturing the video and processing the frames.  
•	BodyPix: for human segmentation in the frames.  
**Background Blur**: The first step of the project is to blur the background of the video. This is achieved by applying a Gaussian blur filter to the frames of the video. The blur is applied to the entire frame, except for the human silhouette detected by BodyPix.  

**Human Detection**: The second step of the project is to detect humans in the video using BodyPix. BodyPix is a machine learning model that can segment the human body from the background in real-time. The BodyPix model is trained on a large dataset of human images and can accurately detect the human silhouette in various lighting and environmental conditions.  

**Video Processing**: The video processing is done using OpenCV. The video is captured using the OpenCV library and is processed frame by frame. The BodyPix model is applied to each frame to detect the human silhouette, which is then used to apply the blur filter to the background of the frame.  

**Output**: The output of the project is a video with a blurred background and only the human silhouette is visible. The video is saved in a specified location with a user-defined filename.  

**GitHub**: The code for this project will be uploaded to GitHub for easy access and sharing. The code will be well-documented to make it easy for other users to understand and use.  

**Conclusion**: This project aims to blur the background of a video and detect humans in the video using BodyPix and OpenCV libraries. The project provides an easy-to-use implementation for video processing and output. The project will be shared on GitHub for easy access and sharing.  
