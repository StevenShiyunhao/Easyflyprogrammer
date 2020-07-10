# Easyflyprogrammer operation instrcution

## Content
1. Introduction
2. Preparation
3. Operation instruction

## Introduction 

This document explains how to use “Easyfly” software to write code into the offline programmer and use the programmer to flash the controller, daq card and hcu. If you have any trouble with this process please contact us by email   
(yunhao.shi@fftai.com ;  xin.chen@fftai.com) 

## Preparation

Since the Easyfly programming software works in Chinese version, the user interface will show messy code if user's computer applys different language environment. As the diagram shown below. The function of “Easyfly” won't affcted by the language. So following the operation instruction user can easily go through the programming process.  
<img src="https://github.com/StevenShiyunhao/images-/blob/master/1.png" width = "60%" height = "60%" div align =center >  

**Software, hardware and code file involved**

- Easyfly: Provided by Fourier Intelligence <img src="https://github.com/StevenShiyunhao/images-/blob/master/01.png" width = "7%" height = "7%" div align =center >
- Lower-level code document: Provided by Fourier Intelligence. The file end up with bin or hex suffix <img src="https://github.com/StevenShiyunhao/images-/blob/master/02.png" width = "15%" height = "15%" div align =center >  
- Offline programmer: <img src="https://github.com/StevenShiyunhao/images-/blob/master/03.jpg" width = "5%" height = "5%" div align =center >  
- coding board and wire: <img src="https://github.com/StevenShiyunhao/images-/blob/master/04.jpg" width = "10%" height = "10%" div align =center >  <img src="https://github.com/StevenShiyunhao/images-/blob/master/05.jpg" width = "10%" height = "10%" div align =center >  
## Operation instruction
-  **Flash the code to offline programmer**    
   Open the Easyfly software first.  
 
   
1) Choose the right controller "stem32" and the type "STM32F405xG"  
   <img src="https://github.com/StevenShiyunhao/images-/blob/master/2.png" width = "70%" height = "70%" div align =center >  
   <img src="https://github.com/StevenShiyunhao/images-/blob/master/3.png" width = "70%" height = "70%" div align =center >
   
2) Choose the number from 10-15 which corresponds to the number in the programmer.   
   Notice: Choosing the number smaller than 10 will cause unpredictable error.  
    <img src="https://github.com/StevenShiyunhao/images-/blob/master/4.png" width = "70%" height = "70%" div align =center >
3) Click to choose the file which will be witten into the programmer.  
   <img src="https://github.com/StevenShiyunhao/images-/blob/master/5.png" width = "70%" height = "70%" div align =center >
4) Click to write the file into the programmer  
   <img src="https://github.com/StevenShiyunhao/images-/blob/master/6.png" width = "60%" height = "60%" div align =center >
5) Wait untill it shows "编写成功！"  
   <img src="https://github.com/StevenShiyunhao/images-/blob/master/7.png" width = "60%" height = "60%" div align =center >

- **Programming your device with the offline programmer**

1. Keep the programmer power on with the USB connected to a power source. (Computer or a charger)
   <img src="https://github.com/StevenShiyunhao/images-/blob/master/8.jpg" width = "40%" height = "40%" div align =center >
2. Connect the coding board and wire with the offline programmer.  
   <img src="https://github.com/StevenShiyunhao/images-/blob/master/15.jpg" width = "40%" height = "40%" div align =center >
3. Connect the other side of the wire with the target device.  
   <img src="https://github.com/StevenShiyunhao/images-/blob/master/16.jpg" width = "40%" height = "40%" div align =center > 
4. Press the green button for 5 seconds and loosen. The screen will switch to the file number page. Click the green button once a time untill to the right number (eg. 13)  
   <img src="https://github.com/StevenShiyunhao/images-/blob/master/13.jpg" width = "40%" height = "40%" div align =center >  
5. Press the green button for 5 seconds and loosen to switch into the writing page  
   <img src="https://github.com/StevenShiyunhao/images-/blob/master/9.jpg" width = "40%" height = "40%" div align =center > 
6. Press the green button for one click to flash the program into the device controller
7. Wait untill the screen show "编写成功" and with a beep which means the process is finished.


