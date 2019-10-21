# **TUTORIAL**

## **1. Introduction.**
This is a simple imageJ macro i wrote to modify the poor quality images acquired with an old camera in optical microscopy. I try to substract the background to the original picture and then modify the pixels with a gamma function to Hematoxylin/Eosin images from islets of Langerhans in pancreatic sections. The final result is an approach to the real image the observer can see in the microscope, avoiding the worse acquisition by the camera.

## **2. How to use a pre-made macro in imageJ.**
Note: You can download for free the last version imageJ at the official repository (https://imagej.nih.gov/ij/download.html) or at the FIJI repository (remember, Fiji Is Just ImageJ: https://fiji.sc/#download). 

2.1 You need to download directly the macro file (i.e. Islet_HE) or copy-paste the code in a .txt file. 
2.2 Then you have to run imageJ and open the image you want to apply the macro by **File>Open** and selecting the desired image.
<p align="center">
  <img src=https://github.com/adrianvillalba/Islet_HE/blob/master/Images/Captura.PNG width="600"/>
</p>
2.3 Finally you can run the macro by **Plugins>Macro>Run** and selecting the .txt file where the macro code is located. 
<p align="center">
  <img src=https://github.com/adrianvillalba/Islet_HE/blob/master/Images/2.1.png width="400"/>
</p>

## **3. Results.** 
The **input image** for the Islet_He macro is the acquired image in bright phase with a camera. In the example showed below, i used a Zeiss Axioskop 2 microscope with a coupled digital camera Nikon DS-Vi1 (https://www.nikoninstruments.com/en_EU/Products/Cameras/Camera-Heads/DS-Vi1). 
The **output image** is the corrected image with contrast/brightness adjusted and a gamma function applied to avoid the acquisition loss of transmitted light by the camera.

<p align="center">
  <img src=https://github.com/adrianvillalba/Islet_HE/blob/master/Images/Collage.jpg width="350"/>
</p>

