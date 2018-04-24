# Automatic-Defect-Inspection-of-Solar-Farm  

<img src="./Dataset/ref/images1.PNG">  
<img src="./Dataset/ref/images2.PNG">  
<img src="./Dataset/ref/images3.PNG">  

### These are different types of faults which occur in solar panel and by their thermal images, It can be visually detected !!! 
### Image1:From set of panels, one panel is brighter than rest one of them!! It's Over Heated- OverHeated Components Fault  
### Image2:In a single panel, Middle cells are having different heat variation, its because of diode short circuit- Bypass Diode Fault  
### Image3:There is a bright spot visible which is called HotSpot, It occurs due to dirt,scratched or cracks  
### Image4:It is Zoomed out Image where each small rectanle is panel and we can see bottom panels are yellow in color compared to upper panels, Its bacause of interconnection Fault - here bootom set of panels are disconnected from power supply.  
### Image5:It is a combination of Hotspot and known as Cluster of Thermal Anamolies  

<img src="./Dataset/ref/images4.PNG">     

### This is the process we have used to do fault classification and localization using deep learning technique 

<img src="./Dataset/ref/images5.PNG"> 

### As we can see,we have provided a test image and our trained model is able to classify what type of fault it is and put a bounding box around it. Here, It is detecting Diode Fault and certain Hotspots  

<img src="./Dataset/ref/images6.PNG">

### This is the extension part where we are showing causes of fault from our knowledge base  

<img src="./Dataset/ref/images7.PNG"> 

### This is the precautions of fault detected  

<img src="./Dataset/ref/images8.PNG">  
<img src="./Dataset/ref/images9.PNG">   
<img src="./Dataset/ref/images10.PNG">  
<img src="./Dataset/ref/images11.PNG">   

### Misclassification:<br />       
### 1.Diode Fault is misclassified as FI<br />             
### 2.OHC Fault is misclassified as Hotspot<br />      
### Zoomed Images creates confusion for deep learning model<br />    
### Solution: Train it on large Image set<br />      

<img src="./Dataset/ref/images13.PNG">   
<img src="./Dataset/ref/images14.PNG">  
 
 ### Conclusion:  
  
### This automatic defect inspection application for solar farms demonstrates that deep learning technology can be applied to solve real-world problems, such as unmanned inspection in harsh or dangerous environments7. The architecture of MobileNet can learn the sophisticated features from the input images for classification and detection tasks. This is a general solution for numerous inspection services in the markets, which can be used for oil and gas inspection, such as pipeline seepage and leakage; utilities inspection, like transmission lines and substations; and even for crisis response to emergencies. The UAVs can fly high up for close-up inspections without putting workers in danger. And the automatic defect inspection system can greatly improve the efficiency of mass data analysis without the help of skilled workers.  

