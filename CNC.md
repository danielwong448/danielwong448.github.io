## 3D Printed CNC Router

**Background:** Following the completion of my 3D printer, I now wanted a hobby sized CNC to complement it. The open source design of the 'MPCNC' from [V1Engineering](https://www.v1engineering.com/) was a suitable candidate, and allowed me to test the capabilities of my 3D printer. Being a mix of PLA plastic and mild steel tubing it is far from rigid, but is able to mill through wood, plastics, and aluminum with success. This machine proved to be a great platform for learning basic CAM and machining theory.

### Printing the Parts

The 3D printed parts total to ~2.2 kg of plastic filament and took ~120 hours. Printing overnight and daily reduced the total printing time to just over a week, but was overall successful with no failed prints. Some parts are seen in the pictures below:

<img src="images/IMG_3690.JPG?raw=true"  width="40%"/>

The large part seen in this photo took ~20 hours to print and weighs over 1 lb

<img src="images/IMG_3692.JPG?raw=true"  width="50%"/>

<img src="images/IMG_3721.JPG?raw=true"  width="40%"/>

### Assembly

Assembly of the CNC was straightforward, mostly comprising of fastening printed parts to steel tubing, squaring the rails, and installing electronics/wiring.
The Z-Axis of the CNC to which the router is mounted is seen in this photo:

<img src="images/IMG_3706.JPG?raw=true"  width="60%"/>

The rails on which the X and Y bearings ride on are seen mounted and squared on a board of 3/4" MDF. A simple plywood & plexiglass enclosure was built to house the CNC to contain debris and reduce noise.

<img src="images/IMG_3703.JPG?raw=true"  width="60%"/>

This photo shows the finished CNC without the router mounted, as well as the sliding plexiglass shielding on the enclosure.

<img src="images/IMG_3734.JPG?raw=true"  width="60%"/>

Finally, the CNC is completed and test cuts were performed in soft materials with good results. The CNC is controlled by an Arduino UNO with a CNC shield and DRV8825 stepper drivers. Nema 17 stepper motors were taken from the 3D printer to drive the CNC's motion.

<img src="images/IMG_3744.JPG?raw=true"  width="60%"/>

### Results

After overcoming the learning curve of CAM programming and the challenges of using a very underpowered and flimsy machine, I was able to acheive reasonable results using various HSM strategies such as trichodial milling and testing approriate feeds, speeds, and chipload. 

**1/4" Birch Plywood Finger Join Box**

<img src="images/IMG_3930.JPG?raw=true"  width="60%"/>

<img src="images/IMG_3932.JPG?raw=true"  width="60%"/>

**1/4" Plexiglass Desk Speaker Stand**

<img src="images/IMG_3846.JPG?raw=true"  width="60%"/>

<img src="images/IMG_3844.JPG?raw=true"  width="60%"/>

**1/4" 6061 Aluminum Bottle Opener**

<img src="images/IMG_3837.JPG?raw=true"  width="60%"/>

<img src="images/IMG_3877.JPG?raw=true"  width="60%"/>

