# Image-to-3D-Project
This was my 4th year project, the final year project of my Bachelor's degree. 
The associated report can be found here: [4th year project Luke Hawkes.pdf](https://github.com/leh115/Image-to-3D-Project/files/6750551/4th.year.project.Luke.Hawkes.pdf)

The network was based on a UNET architecture. A single 480x270 2D image was used to generate the results shown below.
The output point cloud is animated by varying the azimuth angle:

https://user-images.githubusercontent.com/66416355/117352680-2ba5f500-aea7-11eb-8463-82d1d7ee79f0.mp4

The same image input in a larger network with an increased density of Points:

https://user-images.githubusercontent.com/66416355/117352920-73c51780-aea7-11eb-9490-506f1ba2f09a.mp4


A subject of research was the concept of a surface penalty (as discussed in the report). The video below demonstrates how 3 points can be connected to form a plane. A fourth point then measures it's distance to the plane. This distance has been dubbed the "surface penalty" and was researched as a potential loss function for the network.
Surface Penalty explanatory video:

https://user-images.githubusercontent.com/66416355/117443786-8a638100-af30-11eb-992c-a50b9c0d15f8.mp4


