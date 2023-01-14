ABB Robo Challenge 2022
Project: YuMI Palletizing
This project aims to implement an application in which the YuMI robot performs the palletizing process. The robot is located in a working environment that includes a ramp with boxes that need to be packed on a pallet, as well as three different box sizes. Additionally, there is a pallet on which the corresponding boxes must be arranged, a place to test the boxes for the presence of metal, and a place to store boxes in which metal presence is detected.

Pallet Dimensions
The dimensions of the pallet on which the corresponding boxes should be arranged are (W × D) = (100 × 200mm). 5 boxes of each type are available.

User Input
The user has the option to choose whether they want to pack one, two or all three types of boxes in the pallet using the Teach Pendant. To realize this functionality it is necessary to use built-in functions TPReadFK, TPReadNum and TPWrite.

Box Types and Dimensions
Table 1 contains a list of boxes with their dimensions:


| Type of box	Dimensions (H×W×D)| (H×W×D)       |
| -------------                 |:-------------:| 
| 1 - Yellow                    | 40 ×40 × 20mm |
| 2 - Green                     | 40 ×40 × 30mm | 
|  3 - Red                      | 40 ×40 × 40mm | 





