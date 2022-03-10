# PILFT
This is our image matching platform based on various image matching algorithms,it can complete the matching of various complex scene images.
## Terms of Use
The algorithms included in the image matching platform include SIFT, SURF, ORB, ASIFT, LoFTR, and PILFT. The matching function can be realized by importing the left and right images and clicking each algorithm button. The platform demo matching effect is as follows:
![image](https://user-images.githubusercontent.com/99948662/157581462-b590e246-5b85-4a18-b10f-d80320a390c5.png)
Matching points in the figure are marked by green crosshairs.The resulting matching points annotated in the images have all been corrected by RANSAC.After obtaining the matching results, the number of matching points, the correct rate, the root mean square error and the homography matrix between the two images can be calculated.
## About download and use
Click [here](https://drive.google.com/file/d/1WGApWE7riyL0B1gn7KcB0-OzmKKq8_dt/view?usp=sharing) to download, after downloading and decompressing, click "PILFT.exe" to run.
## Update
We will add more matching algorithms in the future, and will continue to improve the execution efficiency of PILFT and keep it updated in real time.
## Notice
The matching platform is developed based on PyQt of Python 3.7. In the process of importing matching images, the path where the images are located should be in English or numbers as much as possible.
