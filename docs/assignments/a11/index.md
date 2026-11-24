# A11 – Motor Selection

## Objective

Select motors and couplers for the two-lead-screw tensile tester designed in A10 and design a bracket to mount each motor to the frame. The drive system must move the crosshead at 1–50 mm/min and provide enough torque to apply a 2 kN tensile load with a safety factor of 4.

## Analyze

### Motor Selection

I selected two 60 W Oriental Motor brushless DC gearmotors, one for each lead screw. Using the screw lead of 0.100 in/rev from A10, I calculated that each screw must turn at 0.394–19.69 rpm to move the crosshead at 1–50 mm/min. Each gearmotor provides 8.2 N·m of rated torque, which exceeds the required 5.64 N·m per screw. The required torque includes the safety factor of 4.

![Motor selection reference](ST.jpeg)

![Motor speed and torque calculations](H1.jpeg)

[Oriental Motor gearmotor, gearhead, and driver](https://catalog.orientalmotor.com/en-us/item/blv-r-series-brushless-dc-motor-speed-control/shop-blv-r-series-brushless-dc-motors/blmr460shk-gfv-gfv4g50-blvd-krd)

### Motor Mount Bracket

I designed an 8 mm thick aluminum plate in SolidWorks to mount each motor to the top of the frame. I used the motor’s four-hole mounting pattern, added four separate holes for the frame bolts, and included a center opening to align the motor shaft with the lead screw. I checked the bearing stress at the bolt holes and selected the 8 mm plate for stiffness and thread engagement in the tapped motor holes.

![Motor mount bearing stress calculations](H2.jpeg)

![SolidWorks model of the motor mount bracket](C1.jpeg)

[Download the motor mount bracket CAD file (SolidWorks)](<MotorMount(1).SLDPRT>)

### Coupler Selection

I selected two NBK MJC-40CS-WH-10-15 flexible jaw couplings. Each coupling connects a 15 mm motor shaft to the 10 mm machined end of a lead screw. Its 10 N·m torque rating exceeds the 5.64 N·m design torque per screw.

![Coupler selection and torque verification](H3.jpeg)
