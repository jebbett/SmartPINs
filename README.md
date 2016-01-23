# SmartPINs

## Summary

For use with SmartTiles - Use momentary switches / tiles to provide a method of PIN entry to disable your security system, in the absence of PIN entry existing within SmartTiles at present.

## Security Notice

PLEASE NOTE:
- PINs are stored in plain text
- You should not use your bank or phone PIN!
- Stored PINs can be read from the app (although your security can probably be bypassed here too)
- Stored PINs san be read from IDE

However most criminals breaking in to your house are unlikely to be the most intelligent of beings to bypass this and it’s strongly suggested that the smart things App is not installed on the device you are using to present SmartTiles. 

## Installation Instructions

### 1. Install the SmartApp

Log in to IDE, create new SmartApp from code, save and publish.

### 2. Create Momentary Switches

a. In IDE go to My Devices > + New Device 
b. Enter the Name (This will appear in SmartTiles)
c. Enter Device Network ID – you can just make this up, but must be unique (I used PIN# replacing # with the button number)
d. Select Type “Momentary Button Tile”
e. Populate location & hub
f. Press create
g. Repeat for each switch (If you use the back button in your browser, all of the settings remain filled so you can just amend name and ID each time to save time)

### 3. Configure the SmartApp

a. Add the switches you have created to the assigned slots in the app, you don’t have to use all numbers if you just want a 4 digit number pad, Enter and Cancel are also optional and will work without.
b. Configure the triggers and PIN(s) – You can specify 2 PINs to trigger two switches or routines.

### 4. Configure SmartTiles

a. Add the switches as “Momentary Switches” to your desired SmartTiles Dash.

![](https://raw.githubusercontent.com/jebbett/SmartPINs/master/Resources/PINPad.PNG)

 
