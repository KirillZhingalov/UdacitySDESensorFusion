# Section 1 : Compute Lidar Point-Cloud from Range Image

## Visualize lidar point-cloud (ID_S1_EX2)
## 1. Find and display 6 examples of vehicles with varying degrees of visibility in the point-cloud
#### Examples of clearly visible vechicles on point-cloud:
#### - Clearly visible car with trunk in front of our car
![ClearlyVisible1](img/clearly_visible1.png)
#### - Clearly visible front side of car in back of our car
![ClearlyVisible2](img/clearly_visible2.png)
#### Examples of car with visible only one side:
#### - Example of car with visibe left side
![VisibleSide1](img/visible_side1.png)
#### - Exaomple of cars with visible right sides
![VisibleSide2](img/visible_side2.png)
#### Examples with hardly visible cars:
#### - Example of hardly visible car behind of our car
![VisibleHardly1](img/hardly_visible1.png)
#### - Example of hardly visible car in front of our car
![VisiblleHardly2](img/hardly_visible2.png)


## 2. Identify vehicle features that appear as a stable feature on most vehicles (e.g. rear-bumper, tail-lights) and describe them briefly. Also, use the range image viewer from the last example to underpin your findings using the lidar intensity channel.

#### 2.1 Tail-lights clearly visible in intensity channel:
![TailLights](img/TailLightsExample.png)
#### 2.2 Rare bumper clearly visible in intensity channel:
![RareBumper](img/RareBumperExample.png)
#### 2.3 Licence plate clearly visible in intensity channel:
![LicencePlate](img/ReareBumperAndLicensePlateExample.png)

Such vechicle features can be easyly identified by intensyty because of their reflective properties of the material.

## Results visualization
### Darknet detections sample:
![Darknet](img/darknet_results.gif)

### FPN ResNet detections sample:
![FPNResNet](img/fpn_resnet_results.gif)