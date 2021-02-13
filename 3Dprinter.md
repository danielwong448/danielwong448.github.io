## COREXY FDM 3D Printer

**Background:** Since the recent rise of consumer level 3D printers, I have always wanted one of my own. I considered purchasing one, but did not like the build quality and kinematics style of the more affordable models so I decided to build my own.

### 1. Design Constraints and Criteria

For my purposes, I wanted a 3D printer with a reasonable build capacity, good dimensional accuracy, compact design, and to be fully enclosed/self contained. I set my target budget at ~$200, but this was surpassed, unsurprisingly. As I had no access to a 3D printer, all parts but one were designed to be manufactured from either steel, aluminum, or raw plastic.

### 2. Design

The first piece of the design was the steel frame weldment, which was designed to constrain linear rods for the X,Y,Z axis, as well as act as a frame for the enclosure. Utilizing 'COREXY' kinematics, I designed mounts for the X and Y axis motors, pulleyes, and mounts for their linear motion assemblies. The moving Z-axis assembly carries the print bed surface up and down, and was also designed to operate on linear rods, with a square thread lead screw driving its motion. Miscallaneous components such as the extruder mount, electronics mounting, and hot-end mount were designed as manufacturing progress was made.

### 3. Manufacturing

While most 3D printers both commercial and consumer level utilize aluminum extrusions for their frames, I was unable to find a reasonable quote for the necessary aluminum extrusion I needed. I had coincidentally been teaching myself to TIG weld at the time, and decided a steel frame for the printer would be a suitable first project. Despite low quality welds, adequate weld penetration was acheived in most joints, yielding a very strong and rigid frame; a bit overkill for this project. I have also yet to see any commercial or hobby built 3D printer anywhere made from steel tubing, so this is truly one of a kind.

<img src="images/IMG_1154.JPG?raw=true"  width="60%"/>

<img src="images/IMG_1156.jpg?raw=true"  width="60%"/>

Linear rail mounts for the Y-axis were created from scrap 6MM aluminum plate from a school project, they were cut using a jigsaw and sanded to dimension.

<img src="images/IMG_2645.JPG?raw=true"  width="60%"/>

<img src="images/IMG_2651.JPG?raw=true"  width="60%"/>

Mounts for the two NEMA17 bipolar stepper motors were fabricated from 1/8" aluminum plate, also recycled from a school project. The pictured brackets are actually a second version, there were 3 bracket designs, with the current used design placing the motors outside of the frame.

<img src="images/IMG_3028.JPG?raw=true"  width="60%"/>

Y-axis rails were mounted and adjusted to be square with the frame. Motors, pulleys, and 3D printed X-Y axis joint pieces are all assembled to allow testing of the X-Y motion under power. The motors are driven by A4988 stepper drivers on a RAMPS 1.4 board with an Arduino Mega 2560. The carriage moved smoothly in the X and Y directions.

<img src="images/IMG_3516.PNG?raw=true"  width="60%"/>

A Z-axis carriage was designed using a sheet metal bend of 16GA stainless steel from a scrapped dishwasher, linear bearing mounts were fabricated from vinyl garden trim and mounted to the carriage.

<img src="images/IMG_3334.JPG?raw=true"  width="60%"/>

1/2" diameter aluminum bar stock was recycled from a school project to be cut, drilled, and tapped for the Z-axis linear rod mounts. The complete mounted Z-axis and print bed is also seen below.

<img src="images/IMG_3352.JPG?raw=true"  width="60%"/>

<img src="images/IMG_3362.JPG?raw=true"  width="60%"/>

A mounting plate for the electronics and 400W power supply was designed and fabricated from 1/4" plexiglass sheet

<img src="images/IMG_3378.JPG?raw=true"  width="60%"/>

Endstops for the X,Y,Z axis were attached at various points of the frame, as well as the hot end of the 3D printer mounted to the X-axis carriage.

<img src="images/IMG_3377.JPG?raw=true"  width="60%"/>

Wiring of all components was completed, including thermistors, heated bed power supply, motor wiring.

<img src="images/IMG_3411.JPG?raw=true"  width="60%"/>

The machine was now printing, albeit with some flaws due to a faulty thermistor causing heating fluctuations. The first prints were parts which would make up a new X-axis carriage, as the aluminum one had many loose parts and excessive weight.

<img src="images/IMG_3459.JPG?raw=true"  width="60%"/>

The first two panels of the enclosure were cut from 1/4" plexiglass and fitted to the sides of the printer.

<img src="images/IMG_3476.JPG?raw=true"  width="60%"/>

Although the current Z-Axis assembly was adequately rigid for printing, a new Z-Axis was designed and fabricated from aluminum square tube and plexiglass. This assembly was much more rigid and had a more finished look.

<img src="images/IMG_3525.JPG?raw=true"  width="60%"/>

While changing out the Z-Axis assembly, the entire steel frame was sanded and painted. The newly installed parts are seen here.

<img src="images/IMG_3553.JPG?raw=true"  width="60%"/>

Lower enclosure panels were CNC cut from plexiglass sheet to hide the electronics and house a fan and various I/O.

<img src="images/IMG_3865.JPG?raw=true"  width="60%"/>

The lower panels were installed, along with a cable drag chain to better organize the wiring. A thin stainless steel sheet cover was installed on the rear of the printer.

<img src="images/IMG_3875.JPG?raw=true"  width="60%"/>

Although long overdue, the electrical components were mounted to a single plexiglass sheet and wires were better organized,

<img src="images/IMG_4217.JPG?raw=true"  width="60%"/>

Since my original intentions for this machine were to be able to print ABS plastic, the final enclosing panels were designed and fitted. The printer is now fully enclosed making it quieter, and heating within to ~45 deg. celcius ambient air temperature.

<img src="images/IMG_4248.JPG?raw=true"  width="60%"/>

<img src="images/IMG_4251.JPG?raw=true"  width="60%"/>

<img src="images/IMG_4262.JPG?raw=true"  width="60%"/>

The original COREXY pulley system had two belts running across the front of the printer, hindering accessibility. These were moved to the rear of the printer by redesinging the belt paths and redesigning motor mounts with integrated pulleys. The new design is shown here, works great so far.

<img src="images/IMG_4304.JPG?raw=true"  width="60%"/>

### 4. Results

After more fine tuning and troubleshooting, the 3D printer produces very good results with great consistency. The printer has now been through approximately over 200 hours of printing and ~8 lbs of plastic filament with no failures. Some examples are seen below.

<img src="images/IMG_3722.JPG?raw=true"  width="80%"/>
<img src="images/IMG_3615.JPG?raw=true"  width="80%"/>
<img src="images/IMG_3687.JPG?raw=true"  width="80%"/>

