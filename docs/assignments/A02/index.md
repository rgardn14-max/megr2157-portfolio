# A2 – Truss Stress Analysis 
 
## Objective 

The objective of this assignment was to design a lightweight planar truss and analyze the forces acting through the structure. The truss needed to support two applied loads while using identical cross-sectional geometry for every member and identical pins at the connections. The goal was to use statics and stress calculations to determine a safe member size and pin size while keeping the overall structure lightweight.

For my design, I used a load of P = 20 kN, with the required dimensions of a = 0.4 m and b = 0.3 m. The truss members were designed using steel, while the connecting pins were designed using hardened tool steel. Safety factors were included in both calculations to make sure the final design could safely support the expected forces.


## Analyze 

![Part 2 truss design, FBD, and method of joints](images/IMG_2356.jpeg)

![Part 2 method of joints and final internal forces](images/IMG_2357.jpeg)

### Part 2 — Truss Design and Internal Forces

For this part, I designed a simple truss using the required dimensions of a = 0.4 m and b = 0.3 m, with a load of P = 20 kN applied at joints C and D. I first created a free-body diagram of the entire truss to calculate the reactions at supports A and B. I then used the method of joints, applying ΣFx = 0 and ΣFy = 0 at each joint to determine whether each truss member was in tension or compression and to find the force carried by each member.

My calculations showed that the largest internal member force was approximately 16.02 kN, occurring in members CE and DE. Finding the maximum internal force allows me to find the minimum cross-sectional area required for all members. I also identified member CD as a zero-force member, which was unexpected.


![Part 3 cross-sectional area and truss weight calculations](images/IMG_2360.jpeg)

### Part 3 — Cross-Sectional Area and Truss Weight

After finding the internal member forces, I used the maximum force of 16.02 kN to determine the minimum cross-sectional area required for the truss members. Using the material yield strength and the required factor of safety of 3.5, I applied the allowable-stress relationship:

Amin = Fmax(F.S.) / σy

This resulted in a calculated minimum area of approximately 162.6 mm², so the actual member geometry should have at least this much cross-sectional area. I decided to go with a slightly larger cross-sectional area of 196 mm² for an even 14 mm × 14 mm square truss member. I did this because I was having issues with the odd decimal values in my calculations and later in my CAD model.

I then calculated the lengths of all seven truss members and added them together to estimate the total amount of steel used. Using the selected cross-sectional area, total member length, and steel density, I estimated the truss mass and converted it into weight. This hand calculation gives me a value that I can later compare with the mass/weight predicted by my CAD model to check whether my analytical design and CAD geometry agree.


![Part 4 pin design calculations](images/IMG_2361.jpeg)

### Part 4 — Connecting Pin Design

For the final hand-calculation portion, I designed the connecting pins using hardened tool steel with a yield shear strength of 170 ksi, a density of 0.278 lb/in³, and the required factor of safety of 4. I drew a free-body diagram of the critical pin and treated the connection as single shear, using the largest expected shear force to make sure all of the identical pins would be strong enough.

Using the shear-stress relationship:

Amin = Vmax(F.S.) / τy

I calculated the minimum required pin area to be approximately 0.100 in². I then selected a 3/8-in diameter pin, which provides an area greater than the calculated minimum, and estimated the combined weight of all five pins to be approximately 0.0967 lb. Using identical pins simplifies the final CAD design and ensures that every connection is designed for the worst-case loading condition.


## Decide 

_Which geometry did you select, and why? This is your first open design choice in the course — defend it._

I selected a simple truss consisting of five joints and seven members, with three joints across the top and two across the bottom. The geometry uses triangular sections because triangles provide a simple and strong way to transfer loads.

I chose this geometry because it satisfies the dimensional and loading requirements while keeping the number of members relatively low. The symmetry and simple geometry also made it easier to analyze using the method of joints and later reproduce accurately in CAD. One interesting result of the analysis was that member CD carried zero force under the specified loading condition.


## Communicate 

This assignment helped me understand how the geometry of a truss affects the forces carried by individual members. Instead of simply choosing member sizes, I first had to determine how the external loads traveled through the structure. The method of joints made it possible to identify which members were in tension, which were in compression, and which carried no force.

Another important lesson was understanding the purpose of a factor of safety. The calculated member and pin sizes were not based only on the exact expected loads. The factors of safety increased the required strength of the components and provided additional protection against yielding or shear failure.

The design process also showed the relationship between hand calculations and CAD. My hand calculations provide an analytical prediction of the required member sizes and overall weight, while the CAD model provides another way to check the geometry and predicted mass of the finished design. Comparing these values will help identify any differences caused by the actual geometry of the connections, pins, and members.

Overall, the process went from selecting a truss geometry, creating free-body diagrams, calculating reactions and internal forces, sizing the members, designing the pins, and finally creating the CAD model. This gave me a better understanding of how statics, material properties, safety factors, and CAD all work together during an engineering design process.


### CAD Files

The completed CAD files for my truss can be downloaded here:

[Download Truss CAD Files](YOUR-CAD-FILE-LINK-HERE
