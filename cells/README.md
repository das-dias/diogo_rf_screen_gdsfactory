# An alternative GDSFACTORY-based implementation of Guard-Ring, MOM-Capacitor and MIM-Capacitor PCells for IHP 130nm Open Source PDK

This repository contains the re-implementation of the Metal-Insulator-Metal (MIM) and RF-MIM capacitor PCells for the IHP 130nm PDK, using GDSFACTORY chip design library. 

Additionally, custom Group-Path based and Metal-Over-Metal (MOM) capacitor PCells were also implemented using the same library for added PDK functionality.

**Repository Contents**
* `design_data`: 
    - `factory` includes PCells factories for verification and testing of the implemented cells.
    - `gds` includes the generated layout
* `cells`:
    - `capacitors.py` Capacitor PCells implementation using GDSFACTORY
    - `passives.py` N-Plus and P-Plus Guard-Ring PCell implementation using GDSFACTORY. 