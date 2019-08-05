
# Allmed Project
## 1st Assesment
### Verification Sensor P2
- Needed to be Selected and select it's place
### Main Problem Provided Through Osama
  - Vibration During Printing Because of the Length of the Bracket VS Print
### Main Problem Provided by Omar
-  Printer : Vibration during Printing Osama
-  Signals : 1 Signal From Archa to the printing at fixed speed  TO SSR
              1 Signal from Archa's in to Triggering to Beagle from sick sensor NPN
## Note : Software Should Use Falling Edge Not Rising Edge
-  no lens fixtations lens needed to be replaced
-  Arch Using track & trace On Program 3
-  WOD Of Camera , Inclination of Camera , Fish Eye
-  light Position : Normal Fixitation OF Lighting .  
- WiRing Digram : NO Wire Tags .
-  Raw Wiring Provided By Omar El Naghy
 #### Junction Box:
 - X1 N.c
 - X2 Limit Switch "Obselet"
 - X3 Reject verification
 - X4 Camera Sensor "Archa"
 - X5 Camera Encoder "Autonics"
 - X6 Light
 - X7 Machine Sensor "Printer Trigger Archa Fork Sensor  "
 - x8 Reject Valve
 - X9 pnumatic Sensors : Beagle Bone Separate
- X10 Not Connected


### Tools & Devices
- hand-held Scanner
- AVoMeter "Provided By naghy"
- Screw-drivers Electronic "Provided By Naghy"
- Allen Key Set "Provided By Naghy"
- Pair Of 10 MM Wrenchs "Provided By Naghy"
- KeyBoard in-site & Mouse needed
- Wifi Dongle "Provided By Naghy"
- Cartidges " 2 old Pairs From Omar "
### Site Results For 22th july
- 1st the focus was needed to be adjusted ==> done
- lens fixed Using Wire Tape ==> done
- WOD is good as it needs to focus only on the spot of printing
- Exposure Time Was 1500 which is to high so i reduced it to 550
- Wrinkle Problem needs to be adjusted
- double Trigger in case of Bottle in Fig A
- SN refuse even after Reading Data-Matrix After Contact hitham He told Me that this is because of the captured serial doesn't exist in camera qeue or because of double Trigger
- For now T&T System is good from the basic concept But needs the previuos adjustment to be ready for Validtation
- Hithams 1st Software Had abug that after Capture the image no ROI defined on the Image so It's Reject So I had To return to the old backup And Wait for Hithams new Software
## Tools Needed For 24th July
- CounterBit Stepped down
- Drill
- Allen-keys
- Soldering Iron
- Solder
### Site Results For 24 JULY
- Sliding Plate For Printer "Fixed"
- Reject Verification Senesor needs to be soldered to the plug 'fixitaion is iin process'
- 1st Error Happened Due To unclean Belt So I asked To clean the belt percetage for now 8 : 2 which means 20%
- ink used were P26 this Could be main issu of ink Difussing
- ink P0 is not Good
- after Returning to the P26 Print Start To be Good Again
- a slight shifting started to Appear After Checking i found that the Belt is Not Well Cleaned So I asked them to Clean It Again
- Cleaning For the 3rd Time Act AS main Problem
- the Error of diffusing ink Was Because of that the Label Was In Contact With the Slider So I tried Out to Adjust the Printer Again For Now It's Good Waiting the Cleaning To start a patch of 100 Bottle Continous  
- we started to use a fine Sand-paper To Clean the Belt as the Iso With the Iron Brush is Not Good
- Haitham Software Without Buffer Is Working Fine Till NOw NOthingh Appeared
- Last Run Worked Fine With a Percentage Of 84.4: 15.6 With actual Bottels Of 92 : 17
- For Now I'm Waiting the Second Patch TO Get from the Auto-clave So As To I Could Start the Second Run With ASAS Number Of Bottels
- working with the bottels at the very hot State "Just Recieved From the Auto ClaV"is not Good
- Now I Found A Asynchronization Between Arca & Zen Jet so I should Start To Work On
- the succseful Test That I ASsumed that the Diff. is 0.5M/min from arca to zen-jet so I set Arca at 20 M/min and Zen-jet 19.5 M/min With Belt Inverter On A set point of  34.1 Which Gave Me Accurate Position For about 75 Consecutive Good Bottels.
### Site Results For 4 Augest
  - RJV Sensor Has Fixed the Eye Porus Opened for the Sensor need To Be Bigger
  - triggering problem Because of the Encoder Double Checked the Wires To Make Sure No AC Wires alonge the encoder Wire
  - Arca Speed Decreased From 20m/min to 19m/min to overcome the wrinkels
  - Forget to decrease the speed in the printer "Needed to be done 1st thing tomorrow morning"
### Prepartions needed for 5 Aug
  - Getting Encoders From Omar el naghy
  - charge the Drill
  - Ask Haitham for Encoder ticks at Software
  - ask Haitham for RJV Revise RJV @ RT Firmware
### Plane For 5 Aug
- Retest the Encoder Used Yesterday
- if Encoder Fails Will Replace the encoder with new one with low Precsion Tiks 150 Tick
- if the low Precsion encoder fail will Replace Them With a Reajet Encoder With HIgh Precsion Ticks 5000 Tick "Not Recomended"
- working on getting the Camera As Close AS Possible from Arca So that i can decrease the Qeue "Will Decrease the Reject Percentage due to printing errors"
- test a consequtive  500 Bottle with no stops
- download the software taken from lotfy & Haitham and Don't forget to add "tick_mm" VARRCHAR(45) column in "rt_config" table in DB
### 5 Aug Results
  - encoder problem was it needed to attach to the belt more firm as contact point with the belt was not enough
  - printing and fedding synchronizzation after decreasing the belt speed was not good so i had to get back to the old speeds for the arca & Printer and raise the VFd Set point to 34.9 so the conveyor could catch the arca
  - other problem with the triggering was the roller underneath the arca wich is fixed to stainless bracket the smooth surface of the stainless help the screw and nut to be untighten by the mean of friction with bottle
  - Synchronization between printer and line and arca is mess
     An encoder should be setup on arca and connected to zenjet 
