# Trouble-shooting-Switched-Mode-Power-Supply-SMPS

 #### Hi, Shubh this side, I am here to give a bit of description about the work i have done.
 
 👇                                                                                                    
![SMPS image](https://user-images.githubusercontent.com/79529647/120190687-cb685180-c1cd-11eb-92da-f4dbd9939cee.jpg)
 
 #### Here is the picture of Switched mode power supply(SMPS). 
 #### Let me first tell you what is it, As the name says its a power supply which i got from the Aquaguard(water purifier). Its work in water purifier is to give 24 volts input to the motor of water purifier. So it takes in the AC supply and returns the DC 24 volt as output.
 #### I got this non working  SMPS from my Aquaguard which stopped working due to it ,I thought to fix the SMPS.

👆  

#### Here is the early video of it: https://github.com/shubh0811/Trouble-shooting-Switched-Mode-Power-Supply-SMPS/blob/master/SMPS%20video.mp4

#### One of the Capacitor had it's pin broken, i took it out. Other Capacitor were looking fine.
#### I checked the continuity it seemed well. In these type of SMPS their is more chance of a IC to be false. I took a battery and in the pcb itself it tried touching the wire with its pins. I found this LED glowing.                                                               


![IMG_20210217_190638-01 (1)](https://user-images.githubusercontent.com/79529647/120305499-a8997400-c285-11eb-9359-dbafa1a0be3d.jpg)                                                                        

#### Now i tried to Check the other IC the same way, i didn't get any response.I checked it with the Multimeter but again their was not satisfying response. I thought of changing it and took it out.
https://github.com/shubh0811/Trouble-shooting-Switched-Mode-Power-Supply-SMPS/blob/master/False%20IC.mp4    
####  After this I checked the other components on the board like: Fuse, Capacitors, Diodes, resistors etc. Other things seemed work well.

#### I got the new components for replacing the false components and soldered them in the PCB.                                     
![IMG_20210401_120209](https://user-images.githubusercontent.com/79529647/120320141-b0154900-c296-11eb-8f42-8c955102cc9e.jpg)
#### Although  the soldering was not up to the mark because i had to join a piece of steel in it, because the path of the PCB was un connected. 

#### After connection of the new components i connect the SMPS to the main supply and it perfectly worked gave the output of the 24 volt.


#### Here is the video if you wish to check it ,https://github.com/shubh0811/Trouble-shooting-Switched-Mode-Power-Supply-SMPS/blob/master/Perfectly%20working%20SMPS.mp4                       




