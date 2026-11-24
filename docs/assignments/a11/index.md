# A11 – Motor Selection

## Objective

Select motors and couplers for the two-lead-screw tensile tester designed in A10 and design a bracket to mount each motor to the frame. The drive system must move the crosshead at 1–50 mm/min and provide enough torque to apply a 2 kN tensile load with a safety factor of 4.


### Motor Selection Parts 1-3 Riley Gardner

I selected two 60 W Oriental Motor brushless DC gearmotors, one for each lead screw. Using the screw lead of 0.100 in/rev from A10, I calculated that each screw must turn at 0.394–19.69 rpm to move the crosshead at 1–50 mm/min. Each gearmotor provides 8.2 N·m of rated torque, which exceeds the required 5.64 N·m per screw. The required torque includes the safety factor of 4.

![Motor selection reference](ST.jpg)

![Motor speed and torque calculations](H1.jpg)

[Oriental Motor gearmotor, gearhead, and driver](https://catalog.orientalmotor.com/en-us/item/blv-r-series-brushless-dc-motor-speed-control/shop-blv-r-series-brushless-dc-motors/blmr460shk-gfv-gfv4g50-blvd-krd)

### Motor Mount 

I designed an 8 mm thick aluminum plate in SolidWorks to mount each motor to the top of the frame. I used the motor’s four-hole mounting pattern, added four separate holes for the frame bolts, and included a center opening to align the motor shaft with the lead screw. I checked the bearing stress at the bolt holes and selected the 8 mm plate for stiffness and thread engagement in the tapped motor holes.

![Motor mount bearing stress calculations](H2.jpg)

![SolidWorks model of the motor mount](C1.jpg)

[Download the motor mount bracket CAD file (SolidWorks)](MotorMount.SLDPRT)

### Coupler Selection

I selected two NBK MJC-40CS-WH-10-15 flexible jaw couplings. Each coupling connects a 15 mm motor shaft to the 10 mm machined end of a lead screw. Its 10 N·m torque rating exceeds the 5.64 N·m design torque per screw.

![Coupler selection and torque verification](H3.jpg)

## Parts 4–6 Ty Hord

For this assignment, I had to do some handwritten calculations. After I was done with those, I moved over to Cad work, where I made the frame assembly and did an FEA on all of the forces. I took screenshots and completed multiple meshes of each assembly as well as the uprights. Once I was done recording my information and gathering my screenshots, I wrote up my results, and we put them into the website.

### Hand Calculations

![Hand calculations, page H4](./H4.jpg)

![Hand calculations, page H5](./H5.jpg)

![Hand calculations, page H6](./H6.jpg)

![Hand calculations, page H7](./H7.jpg)

![Hand calculations, page H8](./H8.jpg)

![Hand calculations, page H9](./H9.jpg)

### Finite Element Analysis

#### Frame and Motor Mounts

![C2 – Frame and motor mount displacement plot](./C2.jpg)

![C3 – Frame and motor mount displacement contour around the mounting holes](./C3.jpg)

![C4 – Frame and motor mount von Mises stress plot](./C4.jpg)

![C5 – Stress distribution around the mounting holes](./C5.jpg)

#### Vertical Frame Components

![C6 – Upright von Mises stress plot](./C6.jpg)

![C7 – Upright X-displacement plot](./C7.jpg)

![C8 – Upright simulation run summary](./C8.jpg)

![C9 – Second upright von Mises stress plot](./C9.jpg)

![C10 – Second upright X-displacement plot](./C10.jpg)

### CAD Files

- [A11 assembly](./assignment11.asm.1)
- [Motor mount](./mount.prt.2)
- [Frame](./frame2.prt.1)
- [Vertical uprights](./q6uprights.prt.1)

