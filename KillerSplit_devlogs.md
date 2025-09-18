# KillerSplit

## Project Overview

**Started:** August 25, 2025  
**Finished:** Sep 18, 2025  
**Total Logs:** 17  
**Time Invested:** 19 hours 39 minutes  
**GitHub:** [https://github.com/MrKillerShaunBa/KillerSplit](https://github.com/MrKillerShaunBa/KillerSplit)  

### Description

Making a wireless ergonomic split keyboard

![Project Cover](http://groundplane.hackclub.com/default_cover.png)

## Table of Contents

1. [Made my own ergo layout (2025-08-28)](#made-my-own-ergo-layout-2025-08-28)
2. [Making the Schematic (2025-08-28)](#making-the-schematic-2025-08-28)
3. [Doing PCB routing (2025-09-01)](#doing-pcb-routing-2025-09-01)
4. [Finished routing (2025-09-01)](#finished-routing-2025-09-01)
5. [Updated PCB (2025-09-02)](#updated-pcb-2025-09-02)
6. [Right Half (2025-09-02)](#right-half-2025-09-02)
7. [Making it a Low Profile Keyboard (2025-09-07)](#making-it-a-low-profile-keyboard-2025-09-07)
8. [Made the PCB (again) (2025-09-07)](#made-the-pcb-(again)-2025-09-07)
9. [Made the Right PCB (2025-09-07)](#made-the-right-pcb-2025-09-07)
10. [Plate (2025-09-10)](#plate-2025-09-10)
11. [Plate (2025-09-10)](#plate-2025-09-10)
12. [Making the case (2025-09-13)](#making-the-case-2025-09-13)
13. [Finished left side case! (2025-09-14)](#finished-left-side-case!-2025-09-14)
14. [Made the right side Plate (2025-09-17)](#made-the-right-side-plate-2025-09-17)
15. [Finished the right case (2025-09-17)](#finished-the-right-case-2025-09-17)
16. [Made the firmware (2025-09-18)](#made-the-firmware-2025-09-18)
17. [Finished it finally (2025-09-18)](#finished-it-finally-2025-09-18)

## Development Logs

### Made my own ergo layout - August 28, 2025 <a id="made-my-own-ergo-layout-2025-08-28"></a>

**Time Spent:** 1h 0m  

#### What I Did

I used https://keyboard-layout-editor.com/ to make a corne-ish layout. Then read more about ergo layouts and came upon ZSA voyager whose thumb area design interested me. So I made a fusion between them- A voyager but without number row but a third thumb key or A corne with a better thumb area design.

#### Issues Faced

Reaching a final design after watching a lot of videos

#### Next Steps

Make a pcb

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/e25cc27d6498ea66e655a871d9c8c99c8f4cf111_tmpg2yl6nby.png)

---

### Making the Schematic - August 28, 2025 <a id="making-the-schematic-2025-08-28"></a>

**Time Spent:** 1h 0m  

#### What I Did

Added all the switches, diodes, pro micro controller (same as nice nano).
Connected the switches in the required matrix.
Added button and slide switch for reset and power on/off resp.
Made connectors for battery and oled screen and wired them.  

#### Issues Faced

Faced a bit of issue on how to wire the OLED screen with the board since there were no designated SDA and SCK pins.

#### Next Steps

Making the PCB

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/b3336675ed3a7b2a78cc2938d7540b3b00a7b37a_tmpttplr42j.png)

---

### Doing PCB routing - September 01, 2025 <a id="doing-pcb-routing-2025-09-01"></a>

**Time Spent:** 45m  

#### What I Did

Finished assigning footprints to the components and placed all the keys using the kbplacer plugin. Since the foot print for one of the slide switch I am planning to use wasn't available in the library, I had to edit the current one to match the hole distances. 

#### Issues Faced

Finding correct footprints of the components.

#### Next Steps

Finishinf routing

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/f04793a100c68491155345be658d7300c9c0007d_tmpu5vsn2e0.png)

---

### Finished routing - September 01, 2025 <a id="finished-routing-2025-09-01"></a>

**Time Spent:** 30m  

#### What I Did

Completed the routing of the board and finalized the placement of all the components.

#### Issues Faced

Nothing as such. Routing is one of my favourite things to do.

#### Next Steps

Case and Firmware

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/39d53bed423b78bfa338ada95b6097b191d066f6_tmpo6xe8_zs.png)

---

### Updated PCB - September 02, 2025 <a id="updated-pcb-2025-09-02"></a>

**Time Spent:** 30m  

#### What I Did

I have updated the PCB outline and added 3d models of the components.

#### Issues Faced

Finding 3d models of some components

#### Next Steps

Case

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/2dc990d90a2f1aa0f4c679fcd740c67af9eda1d6_tmp9hk2f0vi.jpg)

---

### Right Half - September 02, 2025 <a id="right-half-2025-09-02"></a>

**Time Spent:** 30m  

#### What I Did

Flipped everything once and then flipped each component again to get the right half of the keyboard. Deleted all tracks and vias. Will make them again.

#### Issues Faced

The point according to which the components are flipped are not at their centre. Hence, they need rearranging after flipping.

#### Next Steps

Connecting the components together.

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/2e4318c929e107b9d74e80893321da241adccff5_tmp5s56ecu1.png)

---

### Making it a Low Profile Keyboard - September 07, 2025 <a id="making-it-a-low-profile-keyboard-2025-09-07"></a>

**Time Spent:** 45m  

#### What I Did

Just saw the grant amount change. Now I can make it low profile since I have a relative coming from the US who can bring the components for me.
Researched about low profile switches and components and came across typeractive which had all the components at reasonable prices.

#### Issues Faced

None

#### Next Steps

Changing the PCB to fit low profile switches

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/b0fc01762a407a337a5103d7a75912a53679378a_tmpmnhcdwnj.png)

---

### Made the PCB (again) - September 07, 2025 <a id="made-the-pcb-(again)-2025-09-07"></a>

**Time Spent:** 1h 30m  

#### What I Did

Changed the footprint for the switches, slide switch, button and batttery connector to match the current ones I am planning to buy. 
Had to redo the wiring  and board outline since the footprint of Choc and MX switches are different.

#### Issues Faced

Doing everything again ;-;

#### Next Steps

Make the right side pcb.

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/c59688a25ab0aa63258c3f13bae60d417d29c8ac_tmpkq1d0edl.png)

---

### Made the Right PCB - September 07, 2025 <a id="made-the-right-pcb-2025-09-07"></a>

**Time Spent:** 1h 0m  

#### What I Did

Filpped the left side and routed the pcb to make the right side PCB. 

#### Issues Faced

More difficult to route than the left side.

#### Next Steps

Make the case.

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/bcc7aeccc03ac645d4ffe4a34cb9dba79721a2f3_tmpj28xdej3.png)

---

### Plate - September 10, 2025 <a id="plate-2025-09-10"></a>

**Time Spent:** 2h 31m  

#### What I Did

trusted ai03's plate generator but didnt work. Tried for a long to to align with my outline, but no, the thumb buttons won't align. Then exported the edge cuts from KiCAD thinking that my outline in Onshape might be incorrect. Again, wont align correctly. Finally adjusted User.Eco03 layer in kicad to match the 14mmX14mm size of choc keys. 
Exported the user layer and edge cuts in one DXF file and then made a plate using it.


#### Issues Faced

Too Many

#### Next Steps

Making notches for the keys and adding fillets to the key squares. Then making the plate.

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/f766ce59a8fbc139532703956f542cb38c8b42d2_tmpoqizlxfc.png)

---

### Plate - September 10, 2025 <a id="plate-2025-09-10"></a>

**Time Spent:** 2h 31m  

#### What I Did

trusted ai03's plate generator but didnt work. Tried for a long to to align with my outline, but no, the thumb buttons won't align. Then exported the edge cuts from KiCAD thinking that my outline in Onshape might be incorrect. Again, wont align correctly. Finally adjusted User.Eco03 layer in kicad to match the 14mmX14mm size of choc keys. 
Exported the user layer and edge cuts in one DXF file and then made a plate using it.


#### Issues Faced

Too Many

#### Next Steps

Making notches for the keys and adding fillets to the key squares. Then making the plate.

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/f766ce59a8fbc139532703956f542cb38c8b42d2_tmpq_307m3w.png)

---

### Making the case - September 13, 2025 <a id="making-the-case-2025-09-13"></a>

**Time Spent:** 2h 0m  

#### What I Did

Added notches in the switch cutouts so that the choc switches clip right in.
Made the backplate for the case. Still considering if I should add walls or leave it like this.

#### Issues Faced

Making holes at the correct points

#### Next Steps

Finishinf the case

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/f5a2a3cf02718025557b2e96e68ebe6f92969a60_tmpzep3kio7.png)

---

### Finished left side case! - September 14, 2025 <a id="finished-left-side-case!-2025-09-14"></a>

**Time Spent:** 2h 0m  

#### What I Did

Made the wall for the case, finalized the height, added fillets and holes for charging and on/off buttons.

#### Issues Faced

Using Fusion and Onshape at the same time to finalize the placement of the holes. Was unable to import the 3d file of the PCB into onshape so I exported the case from Onshape, imported it in Fusion then measured where the holes need to go.

#### Next Steps

Make the right side case. Hopefully it wont take this long.

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/0a6bd025b908a205c0d25d9600969cff23a6ea02_tmpowgcetr9.png)

---

### Made the right side Plate - September 17, 2025 <a id="made-the-right-side-plate-2025-09-17"></a>

**Time Spent:** 30m  

#### What I Did

Made the right side plate. I know I could mirror the left side but decided against it, just to be sure. I exported edge.cuts and user.eco1 for board and switch outlines. Imported it in onshape and then built the plate.

#### Issues Faced

None, I knew what to do.

#### Next Steps

Make the case

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/bffb9dda3abd3d5696fb961bbb02827befa822d1_tmpgzo4cwo5.png)

---

### Finished the right case - September 17, 2025 <a id="finished-the-right-case-2025-09-17"></a>

**Time Spent:** 1h 0m  

#### What I Did

Using the same steps, I made the right side case case. Took a lot less time than before.

#### Issues Faced

None

#### Next Steps

Make the firmware

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/7d45b0ac185360a31101549dd6b673afb7bd5022_tmpsftv8c4n.png)

---

### Made the firmware - September 18, 2025 <a id="made-the-firmware-2025-09-18"></a>

**Time Spent:** 40m  

#### What I Did

Got an online repository for Corne keyboard ZMK firmware. I forked that and edited the code to add the displays and the pin mapping according to my schematic. The keys are essentially the same between the standard Corne and mine.
Link- https://github.com/MrKillerShaunBa/zmk-config-killersplit

#### Issues Faced

Nothing as such

#### Next Steps

Compile everything in a single repo

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/e71960cf7f7e4737ed50a13cc4ddfcea2ebc70e4_tmpsrxk0dgv.png)

---

### Finished it finally - September 18, 2025 <a id="finished-it-finally-2025-09-18"></a>

**Time Spent:** 57m  

#### What I Did

Compiled everything into a single Github Repo. Imported 3D files from Kicad to created assembled views. Finalized the BOM. Clicked screenshots for documentation.

#### Issues Faced

None

#### Next Steps

None, yaaay

#### Media

![Log Media](https://hc-cdn.hel1.your-objectstorage.com/s/v3/c3a3018954576da3a7f81fbc7dd0e53ae3cb5c26_tmpm8ls86hy.png)

---



*Exported from Grounded Tracker on 2025-09-18 21:55:09*
