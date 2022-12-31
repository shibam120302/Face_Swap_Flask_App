# Face Swap Flask App
![fsfa](https://i.ytimg.com/vi/cltK58JAOJM/maxresdefault.jpg)

Most of you would have used or seen many filters that let you swap your face with your friends, celebrities or even animals. These filters are very popular in social media platforms such as Instagram, Snapchat and face app. Have you ever wondered how this is done? With Python and OpenCV it is actually very simple to build this application. The concept behind this is to detect certain points on the face and then replace it with the swapping image. Though simple, it does involve a lot of factors like lighting, facial structure and camera angle. To avoid these complications, we will implement this on two images of celebrities. 

In this article, we will implement a face-swapping technique for two images of celebrities using OpenCV and python.

### Steps used for this project:


1.Taking two images – one as the source and another as a destination.

2.Using the dlib landmark detector on both these images. 

3.Joining the dots in the landmark detector to form triangles. 

4.Extracting these triangles.

5.Placing the source image on the destination.

6.Smoothening the face.
