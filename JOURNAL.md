---
title: "Atulu"
author: "sudarshandongare2010"
description: "A smart and aesthetic environment monitoring system with clock and with crazy taskbar   "
created_at: "2026-11-15"
---

# November 15: Maked the Preliminary component shortlist

I Starting Searching internet for components that i need like dev board displays and the othet sensors from along many 

Components Has been shortlisted 
ESP32-S3 N16R8 Development Board As main Dev Board and Main components Which has 16mb of flash + 8mb PSRAM which is more capable than the other esps
Bosch BME680 4-in-1 Environmental Sensor which can measure –40°C to 85°C which has just 1 second response time for the humidity
SENSIRION SCD41 , SCD41 is a C02 sensor to count c02 values it is little expensive but totlaly worth it
Waveshare ESP32-S3 4.3inch Capacitive Touch Display Development Board, 800×480, 5-point Touch, 32-bit LX7 Dual-core Processor


<img width="1753" height="727" alt="Screenshot 2026-11-15 152437" src="https://github.com/user-attachments/assets/f1c7ce88-e1ed-49a5-be35-01253fd6c064" />
<img width="1753" height="727" alt="Screenshot 2026-11-15 152437" src="https://github.com/user-attachments/assets/c789776a-dce9-4015-ad12-a64aa75eed90" />
<img width="1605" height="639" alt="Screenshot 2026-11-15 145901" src="https://github.com/user-attachments/assets/816bb18a-b320-4852-ad30-cadd8bf6ef92" />

<img width="1856" height="697" alt="image" src="https://github.com/user-attachments/assets/dd757fa1-0b8f-4b28-ab5b-0ed391189d17" />


**Total time spent: 1 hours**


# November 16: PCB for Atulu

My todays objective was to create a custom pcb for atulu 

so I gather the docummentation of bosch BME610 and SCD41 and gather electrical information and sprecification about them 

then start with schematic diagrams make the connection diagram of both sensors and Arrange I2C connection 3V3 connection and tried to trouble Bost the error and violations added essential capacitor resistors  


after this I started editing the pcb created footprints arranged components in board Completed manual copper-track routing using F.Cu and B.Cu. , Used vias to switch between copper layers.


than i done the  
Mechanical Design
Added four mounting holes
Selected 2.1 mm hole diameter
Aligned all four holes symmetrically
Final PCB dimensions 35 * 37 mm.

and finnaly got
Final Design and these results
Schematic = Completed
PCB layout=Completed
Copper routing= Completed 
DRC violations = 0
Mounting holes = 4
PCB dimensions
35 × 37 mm

after these all included the all sch diagrams pcb files in github repo


screen shot while buildong
<img width="685" height="411" alt="Screenshot 2026-11-16 131345" src="https://github.com/user-attachments/assets/e049ce8b-1944-48b0-954a-9091168cdaa4" />



<img width="1554" height="853" alt="Screenshot 2026-11-16 223915" src="https://github.com/user-attachments/assets/af230e3b-d6e6-4abb-ab08-c088dce8b397" />

<img width="1892" height="964" alt="Screenshot 2026-11-16 223935" src="https://github.com/user-attachments/assets/1856190e-588e-4d8a-a0ae-01d0f7139b4c" />

**Total time spent: 3 hours**


# November 17: Completed the Enclosure Design 

I started designing the case for you Atulu gather measurement information and then started designing in one shape 




<img width="1156" height="791" alt="Screenshot 2026-11-16 234423" src="https://github.com/user-attachments/assets/d428e606-6708-437b-bbf2-1c17d40fd18d" />
<img width="442" height="425" alt="Screenshot 2026-11-17 130712" src="https://github.com/user-attachments/assets/a1246b63-0f50-4d2a-9bb7-5cd5233ae658" />
<img width="618" height="661" alt="Screenshot 2026-11-17 134133" src="https://github.com/user-attachments/assets/01826b70-bd24-4b3d-bc2f-8c34113a5f02" />
<img width="817" height="491" alt="Screenshot 2026-11-17 134110" src="https://github.com/user-attachments/assets/95f2f410-34a3-4084-9c8c-525f5715601f" />
<img width="702" height="561" alt="Screenshot 2026-11-17 134117" src="https://github.com/user-attachments/assets/1a4e4357-4db8-416d-b0ad-62df344cc5d3" />
<img width="637" height="511" alt="Screenshot 2026-11-17 124841" src="https://github.com/user-attachments/assets/1b22b57a-b4cf-4901-a43c-3d9dff3f0ec5" />



**Total time spent: 1 hour 30 minute**
