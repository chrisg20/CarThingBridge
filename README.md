# CarThingBridge
A compact connector board for the Spotify Car Thing and Raspberry Pi Zero, for use with [Nocturne](https://github.com/usenocturne/nocturne-image).

3D printed mount on Printables [here](https://www.printables.com/model/1098732-car-thing-pi-bridge).

<img width="500" alt="Screenshot 2024-12-04 at 3 33 04 PM" src="https://github.com/user-attachments/assets/b6781614-9ddb-4c03-b561-87ace9c2db6d">
<img width="500" alt="Screenshot 2024-12-04 at 3 33 04 PM" src="https://github.com/user-attachments/assets/a7247fd7-2eed-4263-aca0-68755e4b5f4a">

# Ordering Instructions
I no longer sell the boards due to lower demand, high tariffs, etc. 

If you want one, it is worth asking on the Nocturne Discord server to see if other users have extra boards that they would be willing to give or sell to you. 

Server: https://discord.gg/GTP9AawHPt

To order boards yourself, follow these steps:

**Order PCB Only (Manual Assembly)**

Manual assembly should only be attempted if you are experienced in soldering very small (0603) components.

* Download the ZIP archive: https://github.com/chrisg20/CarThingBridge/PCB/production/.
* Visit https://JLCPCB.com and click Order Now.
* Upload Bridge_v1.zip from the PCB/production/ directory.
* VERY IMPORTANT! Set PCB Layers to 2 and Thickness to 0.8mm — this is required for the straddle-mounted USB-C connector.
* Order components from Digi-Key, Mouser, etc.
* Required Components (per PCB):
  * CX60-24S-UNIT (x1)
  * CX90M-16P (x1)
  * SSSS811101 (x1)
  * ZX60-B-5S(31) (x2)
  * 0603WAF5101T5E (x3)

**Order PCB with Assembly**

* Enable PCB Assembly during order setup.
* On the Bill of Materials page:
* Upload bom.csv from PCB/production/.
* Upload positions.csv from PCB/production/.
* Review the component placement preview to ensure it looks correct.

You will receive the a notification to pay an additional ~$50 for a fixture required for the USB-C connector (C5338340).

# Instructions

Print the mount and install 4 M2.5x3mm inserts into the holes. Place adhesive strips into the slots and attach to the car thing so that the Nocturne logo bar lines up with the left edge of the Car Thing as shown in the image below.

<img width="380" alt="Screenshot 2024-12-04 at 3 33 04 PM" src="https://github.com/user-attachments/assets/effa9ac9-5d73-49a0-9ed0-851f4376d52b">

Connect the Raspberry Pi to the bridge and the bridge to the Car Thing. Secure the Raspberry Pi to the mount with 4 M2.5x4mm screws. Ensure the small switch is set to ON (away from the Raspberry Pi) as shown.

<img width="380" alt="Screenshot 2024-12-04 at 3 33 04 PM" src="https://github.com/user-attachments/assets/d034b633-fbca-43ef-a63b-6654b9a20c5e">

