# SolidWorks for Capstone Project

## Goal
Our Capstone project MUP(Monitoring Unoccuppied Property) requires an enclosure that can hold all nesseary components. 

## Design Specification
Size: 19cm x 12cm x 14.1cm 

1st floor height: 5.5cm

2nd floor height: 3.95cm 

3rd floor height: 4.65cm

Battery, mangOH Yellow, PMS, Raspberry Pi, USB to UART are just mock-up designs that won't be 3D printed. Only the enclosure is what I have desgined.

## Design Features
### Modular design: Multiple Floors
The design has multiple floors where each floors can be assembled by M5 screws.

Floor1: Battery

Floor2: mangOH Yellow IoT Board, PMS(Power Management System) Circuit

Floor3: Raspberry Pi 4B, USB to UART bridge

#### Modular design gets several benefits: 
1. Raspberry Pi's heat doesn't effect mangOH: mangOH Yellow has a temperature sensor. However, the Raspberry Pi's chips are easily heated up and can affect the temperature sensor. 
To minimize the effect, the modular design that seperates mangOH and Pi has chosen and designed.
2. Detachable 1st floor: 1st floor contains the battery pack. If an user is happy without the emergency battery and wants to use just the power from a wall power outlet, 
the user can simply detach the 1st floor. 
3. Compack size: by adapting the modular desgin, rather than having a one floor that is 30cm by 30cm, the design has the smaller dimension.
4. Better cable managements.

### Great Airflow 
Controlling temperature of each floor is nessary as the Raspberry Pi and the battery can be easily heated up, and can effect the temperature sensor of mangOH. To lower the temperature, each floor has multiple holes on its front and back. Through these holes, outside air can flows in and out easily. Also any of the hole can be used as a port that outside power supply cable can go through. In addition, on the 3rd floor where Raspberry Pi resides, an fan can be attached on the celling to cool down the Raspberry Pi even more. 

### Thin, Light Weight, yet Sturdy
The original design had a 1cm wall thickness, which required 790g of PLA filament to be printed. To reduce the cost for printing, the new design has made with the wall thickness of 2.5mm. Typically, a single thread is 200um. Therefore 2.5mm thichkness is made of 12.5 threads, which give strong support. All the side walls and the bottom/top floors have the thickness of 2.5mm. 

### Minimized the Support Material.
FDM printing requires 'support material' in areas where there's nothing underneath. My previous design, where oval vents are horizontal, requires supporting material for each vent. 

<p align="left">
  <img src="Images/Previous Vents Design.jpg"  width="300" />
  <em> [Vents design that requires support material] </em>
</p>

This support material can be eliminated by orienting the ovals upright. My new design has updated accordingly.
<p align="left">
  <img src="Images/Current Vents Design.jpg"  width="300" />
  <em> [Vents design that doesn't require support material] </em>
</p>

As I don't need to remove the support material after it printed, the desgin will have cleaner surface finish, and some reduction in the cost as well.

## Images
<p align="middle">
  <img src="Images/Isometric View.jpg"  width="400" />
</p>
<p align="middle">
  <img src="Images/Exploded View.jpg" width="400" /> 
</p>

# Final Product
You can see more images in 'image' file
<p align="middle">
  <img src="Images/Printed_Front.jpg"  width="400" />
</p>
<p align="middle">
  <img src="Images/Printed_Back.jpg" width="400" /> 
</p>

