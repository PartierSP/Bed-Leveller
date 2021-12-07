# Bed Leveller

## The 3D Printer Assistant

This project is designed assist the user with manually tramming (levelling) their 3D printer's bed with it's print head.

In order to achieve proper adhesion and quality prints, it is of upmost importance that a 3D printer's bed is actually trammed to it's print head. When this is done properly, the printer will know how high the print head is above the print bed no matter where over the bed the head is told to go. This distance can vary depending on Z-stop location, bed temperature, bed warping, Z backlash, crashes, and changing build surfaces to name a few. Thus its required to check the machine's tram fairly often. When ever I start to get adhesion issues, this is the first thing I check.

To properly check the tram, it is required to simulate printing environment as much as possible. This means we need the bed to be heated to proper print temperature, and to have the machine move the head itself. Depending on the MDI/Jog controls on the printer, this may be difficult to do. This is where Bed Leveller comes in. It is designed to control the printer and move to pre defined locations in order to assist in the tramming process.
