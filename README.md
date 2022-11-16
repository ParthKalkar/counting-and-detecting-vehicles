# counting-and-detecting-vehicles
In this project, I worked on detecting and counting vehicles in a given image or a video.

We will be using openCV for image processing and HAAR Cascade which is used for object detection. 

We can also create our own customized HAAR Cascade

## Scope
As HAAR CASCADE is used for object detection we have a very vast scope for this project. It can be used for any type of object detection. We can also create our own custom HAAR CASCADE for specific objects.  

With this kind of identification and localization, object detection can be used to count objects in a scene and determine and track their precise locations, all while accurately labeling them.

## Technology
1. Python
2. OpenCV
3. HAAR CASCADE
4. Flask

## Steps
1. Loading the image from the internet.
2. Resizing the image and convert it into a numpy array. 
3. Converting image into Grayscale. 
4. Load the XML file which contains the HAAR Cascade. 
5. Using HAAR Cascade to detect the vehicle in the image.
6. Use the contours to create a rectangle around all the detected vehicles (cars).
7. Similarly we will perform these operations for another image for bus detection. 
8. Will use `bus_detection.xml` for bus detection.
9. We will also perform these operations on a video. 
10. Save the video with object detection.

## Run
1. Create the copy of the project.
2. Open command prompt and change your current path to folder where you can find `app.py` file.
3. Create environment by command given below - $ `conda create -name <environment name>`
4. Activate environment by command as follows - $ `conda activate <environment name>`
5. Use command below to install required dependencies - $ `python -m pip install -r requirements.txt`
6. Run application by command - $ `python app.py` You will get url copy it and paste in browser.
7. You have sample_data folder where you can get images to test.

## Interface
![Screenshot from 2022-11-16 18-40-54](https://user-images.githubusercontent.com/50231750/202231318-e468ec82-3128-46ee-ab39-f7a7553e9130.png)



## Car - Bus Input
![image](https://user-images.githubusercontent.com/50231750/202220643-240e1938-696a-44b4-8ff5-96cd877b8310.png)

![Screenshot from 2022-11-16 18-41-16](https://user-images.githubusercontent.com/50231750/202231461-19e1f791-adba-4b94-bc03-cd58ed9721c5.png)


![image](https://user-images.githubusercontent.com/50231750/202221088-e41207ef-f34d-412b-ab27-7e9ea0a263a1.png)

![Screenshot from 2022-11-16 18-57-18](https://user-images.githubusercontent.com/50231750/202231506-62ad689f-fc80-4032-96ba-d52e2e215e29.png)





## Car - Bus Output
![image](https://user-images.githubusercontent.com/50231750/202220708-80363f42-f10f-462d-adf1-1ce937aa0d75.png)

![Screenshot from 2022-11-16 18-56-11](https://user-images.githubusercontent.com/50231750/202231597-399ca270-b08a-4027-a21d-a74ab5c84556.png)


![image](https://user-images.githubusercontent.com/50231750/202220808-b785772a-492b-4e3f-b52e-3bd990d076ff.png)
![Screenshot from 2022-11-16 18-56-55](https://user-images.githubusercontent.com/50231750/202231652-9f8cd513-1323-4732-b616-8707eb6897e3.png)




## Video


https://user-images.githubusercontent.com/50231750/202221315-1ab97a51-62d7-4676-a5ec-bd32e1a9b169.MP4



## Conclusion
We started with downloading the image we will be working on and performed different operations on that image. We saw how we can use haar cascade which is used for object detection. We saw how different haar cascade is used for car detection, bus detection. Similarly, you can use many pretrained haar cascades for different object detection.
