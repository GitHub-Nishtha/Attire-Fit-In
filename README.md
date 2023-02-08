# Attire-Fit-In
Final year project (2022)


Introduction
The trend of online shopping is increasing. Trying on clothes virtually in these times will allow the customers to get an idea of how the cloth will look on them, which will substantially improve the customer experience. This is heading towards the idea of virtual dress fitting or virtual fitting. Image-based virtual fitting is basically an image generation task that changes a person's garment to another garment specified in another product image.
Virtual try-on, ‘Attire Fit-in’, which would help people visualize how a particular piece of clothing would look on them. Our model would generate a synthetic image of the client trying the clothing item.

Getting Started
Pre-requisites
Python: (3.6 - 3.8.5)

Procedure
1. git clone https://github.com/rishabh15b/B.Tech-CS----2022.git
2. In this open 14_Grp_AttireFitIn.
3. Code folder contains the code.
Step 1:

conda create --name attire-fit-in python=3.7.13
Step 2:

conda activate attire-fit-in
Step 3:

pip install -r requirements.txt
Step 4:

Upload your dataset in given path dataset\test folder.
 **Cloth & Image size should be 768*1024** 
Step 5:

To get cloth mask run clothmask.py given in code folder

To get Segmentation of custom image run Segmentation Code Getting segmented image from above save it in given path dataset\test\image-parse folder

To get Openpose of custom image run Openpose Code Save the custom image in Images folder. Getting openpose image from above save it in given path dataset\test\openpose-img folder & openpose json in dataset\test\openpose-json folder

Step 6:

For running Attire fit it:
```bash 
python tinkterc.py --name output  ##output is folder name given by user where results are saved. 

The results will be saved and will be shown using tkinter app.
Team
Rishabh Balaiwar (Roll No: 18052100542, email :18052100542@ietlucknow.ac.in)
Nishtha Shukla (Roll No: 1805232038, email :1805232038@ietlucknow.ac.in)
Himani Srivastava (Roll No: 1805232026, email :1805232026@ietlucknow.ac.in)
