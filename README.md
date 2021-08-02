# SolidWorks for Capstone Project
## Goal
Our Capstone project requires a enclosure that can hold all nesseary components. 
The design has multiple floors where each floors can be assembled by M5 Screws.
Floor1: Battery
Floor2: mangOH Yellow IoT Board, PMS(Power Management System) Circuit
Floor3: Raspberry Pi 4B, USB to UART bridge
## Design Features
* Modular design: Modular(Multiple Floor) design get several benefits. 
1. Raspberry Pi's heat doesn't effect mangOH: mangOH Yellow utilizes temperature sensor. However, Raspberry Pi's chips easily get heated up and can affect to the temperature sensor. 
To minimize the effect, the modular design that seperates mangOH and Pi has chosen and designed.
2. Detachable 1st floor: 1st floor contains the battery pack. If a user is happy without the emergency battery and just using the power source from a wall power outlet, 
the user can simply detach the 1st floor. 
3. Compack size: by adapting the modular desgin, rather than having a one floor that is 30cm by 30cm, this design has the base of 14.3cm by 19cm.
4. Better cable managements.

<p align="middle">
  <img src="Images/Isometric View.jpg"  width="610" />
  <img src="Images/Exploded View.jpg" width="340" /> 
</p>

