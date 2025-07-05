| title                  | author     | description                                               | created_at |
|------------------------|------------|-----------------------------------------------------------|------------|
| Glide build jounral    | adarshdg   | fixed-wing fpv aircraft                                   | 2025-07-05 |

Total Time Spent So Far: 50 Hours

# Glide FPV Design Log

**project type**: fixed-wing fpv aircraft  
**current phase**: design + planning  
**total hours spent**: 50 hours  

## Overview Table

| Date       | Entry Title                      | Hours Spent |
|------------|----------------------------------|-------------|
| June 3     | the idea hits                    | 1 hr        |
| June 4     | wing it                          | 2 hrs       |
| June 5     | onshape setup                    | 3 hrs       |
| June 6     | playing with airfoils            | 3.5 hrs     |
| June 7     | fuse logic                       | 3 hrs       |
| June 8     | wings go modular                 | 2.5 hrs     |
| June 9     | parts that click                 | 2 hrs       |
| June 10    | everything needs a mount         | 3 hrs       |
| June 11    | layout check                     | 2 hrs       |
| June 12    | fuselage fine-tuning             | 2 hrs       |
| June 13    | battery plate + cable routing    | 2 hrs       |
| June 14    | tail section & control surfaces  | 2 hrs       |
| June 15    | canopy and hatch designs         | 2.5 hrs     |
| June 16    | BOM cleanup and cost estimates   | 3 hrs       |
| June 17    | render prep and doc screenshots  | 2 hrs       |

---

## June 3: the idea hits
Was thinking about starting a new long-term build and fixed-wing FPV seemed like the move. Didn’t want to just buy a kit. I wanted to build something from scratch. Got inspired by a couple of balsa-style builds and figured I’d go with a V-tail configuration just to make it weird. Spent the day watching build videos and noting down what materials I’d need. The name “Glide” kinda just came to me it felt right. Made a fresh folder called `Glide_FPV` and dumped in every screenshot and airfoil chart I could find. Already obsessed.

**hours spent:** 1  
![Nacelle](https://github.com/user-attachments/assets/cee74f34-8734-4f74-b88a-1bed0fa0482c)


---

## June 4: wing it
Started sketching the main wing shape. I knew I wanted a mid-mounted wing with enough area to carry a camera, GPS, and battery without nose-diving. Spent most of the time choosing span and chord. The wing ended up slightly swept for stability. I also had to figure out how I was going to join the wings to the fuselage in a modular way. Took a detour learning about wing loading and Reynolds numbers. Realized I was overthinking but kept going anyway. Threw in some sketch constraints just to make future changes easier.

**hours spent:** 2  
![Wing 1](https://github.com/user-attachments/assets/2ec49ef9-8c73-4976-8780-c9f6d8a34d41)


---

## June 5: onshape setup
Decided to move the project from Fusion to Onshape because I could link parts and assemblies more easily. Started recreating the wing sketches and defined the airfoil profile I wanted to use. Added parametric controls to change wingspan and taper. Sketched the fuselage outline and put down mounting reference planes. Also started organizing parts into subassemblies so it wouldn’t become chaos later. Made an assembly file with placeholder geometry just to see how it’s all looking together. Set up version control and shared it with a friend for feedback.
![Fuselage 1](https://github.com/user-attachments/assets/061835a2-5868-4139-af6b-5f5b58c342ab)

**hours spent:** 3  

---

## June 6: playing with airfoils
Picked the GOE225 airfoil because it's simple to work with and already validated in RC designs. Modeled the profile in sketches and made a loft for the full wing. Adjusted thickness for better strength. I also worked on simulating CG shifts as weight gets added. Balanced the airfoil’s lift curve with stability, since I don’t want it to be twitchy in flight. Started plotting potential flap and aileron cutouts. I also added reference lines for dihedral, which I might use for better cruising. Long day but good progress.
![Ailerons](https://github.com/user-attachments/assets/5cf50498-7339-437d-9e56-fc4570dd8e21)

**hours spent:** 3.5  


---

## June 7: fuse logic
Focused on fuselage design. I knew I had to fit a 3S or 4S battery, flight controller, camera, GPS, and some wiring slack. Started with a boxy sketch but ended up sloping the nose for better aerodynamics. Added bulkheads and formers to define the structure. Also made sure the battery could be slid in and out without removing the wings. Thought about placing the VTX antenna and left some internal clearance for it. Still not sure about cooling, but I can cut vent holes later. Did a fit test by overlaying real parts in the CAD.
![Fuselage 3](https://github.com/user-attachments/assets/5c04cd7d-f03d-4489-9f63-2b4071739b40)

**hours spent:** 3  


---

## June 8: wings go modular
Redesigned the wings to be fully removable. Modeled spar connections and joinery points. Went for a double carbon rod pass-through design with locking ribs. Added slots for interlocking into the fuselage. Adjusted wing root thickness to make it strong at the join. Also left some space for internal wiring to route through the spar. Checked alignment across both sides using sketch constraints. Starting to feel real now. Exported some DXFs to test slot tolerance later.

![Wing 4](https://github.com/user-attachments/assets/9786bc74-eebd-4e8d-9bfd-212f38c688fa)

**hours spent:** 2.5  


---

## June 9: parts that click
Got into the groove of laser-cut construction. Modeled finger joints across all vertical walls and ribs. Played around with notched tabs and spine slots for the fuselage. Also built snap-fit connections that might hold without glue. Considered cut orientation to avoid warping. Started thinking about weight too, because too much ply will make it nose-heavy. Rebuilt some of the bulkheads to have mounting slots for electronics. Overall just worked on getting parts to actually connect cleanly.

**hours spent:** 2  
![Battery plate](https://github.com/user-attachments/assets/bb43fb6c-9601-4bae-a8f6-cb7ede456c35)


---

## June 10: everything needs a mount
Made mounts for the flight controller, GPS, ESC, camera, and power module. Designed each to be removable and added ventilation where needed. The GPS module needed clear line-of-sight so it sits on the top deck. ESC sits in a slot with airflow from a vent at the rear. The cam mount has a bit of tilt and fits into the nose form. Even added extra holes for zip ties. Mock-assembled everything in Onshape to make sure it wouldn’t clash with the airframe.
![Motor mount LR](https://github.com/user-attachments/assets/02548df9-6fce-404f-a365-e35864b250e7)

**hours spent:** 3  


---

## June 11: layout check
Opened the main Onshape assembly and started inserting all sub-parts. Checked how the CG balanced when the battery was in and made sure the wing and tail alignment was symmetrical. Moved some parts to avoid interference, especially the servo wires. The fuselage was slightly too narrow for the receiver, so I widened the middle shell. Also changed some hole sizes to fit M3 fasteners. After checking all clearances, exported screenshots for documentation and BOM planning.
![Wing 4](https://github.com/user-attachments/assets/8e7b0ef5-d2d3-474e-bb56-6f8d3c104e0c)

---

**hours spent:** 2
## June 12: fuselage fine-tuning
Went back to the fuselage after getting some CAD feedback. Adjusted the internal walls to reduce wasted space and re-routed a slot for the power cable. Also redesigned how the top and bottom shells align. Had to add notches for secure mounting with tabs. Then I added more curves to the sides to smooth out the profile. It’s way easier to print or cut when the geometry is consistent. Also checked the prop clearance again just to be safe.

**hours spent:** 2  
![Fuselage 2](https://github.com/user-attachments/assets/e39c6744-ca72-4877-84cb-96d6c2102121)


---

## June 13: battery plate + cable routing
Today was all about power. Designed a slide-in battery plate that locks into the fuselage rails. Added a strap guide and vent cutouts. Then routed cable paths from the battery bay to the ESC and flight controller. Checked all clearances for XT60 connectors. Modeled the cable loops to make sure nothing gets pinched. Also added dummy batteries into the model just to visualize the mass and how it would affect CG again. It fits, but tight.

**hours spent:** 2  
![Battery plate](https://github.com/user-attachments/assets/c21e9649-60e0-4f92-99dc-5ed9622c9574)


---

## June 14: tail section & control surfaces
Sketched and modeled the horizontal and vertical stabilizers. Did some math to get the surface area right for a V-tail. Made servo cutouts and holes for linkages. Re-aligned everything with the tail boom and added supports. Then went into the rudder and elevator shape. This part was annoying because of all the angles, but it’s looking good now. Created mirrored parts so the left and right side stay consistent.

**hours spent:** 2  
![Rudder LR](https://github.com/user-attachments/assets/36e1a1cb-7cab-4ff0-8d10-46f524f8216a)


---

## June 15: canopy and hatch designs
Focused on access points today. Made a full canopy cutout and hatch cover for top access. Added magnets for locking the hatch. Checked to make sure the canopy can fit wiring and allow camera clearance. Then cleaned up the forward section so it doesn’t interfere with airflow. Also thought about using velcro as backup closure. Took a few cross sections to see what’d fit inside and it's all finally clicking.

**hours spent:** 2.5  
![Canopy F](https://github.com/user-attachments/assets/50154e4e-d337-455e-a39b-681ad3fd73a7)


---

## June 16: BOM cleanup and cost estimates
Organized the bill of materials today. Broke things down into mechanical parts, electronics, and hardware. Added source links and price estimates. Had to recheck weights and double-confirm if I need aluminum or carbon spars. Also did a small weight budget estimate to keep things under control. Found out servos take more space than I expected, so might need to bump fuselage width slightly. Shared it all with a mentor to review.

**hours spent:** 3  
![Wing 3](https://github.com/user-attachments/assets/2ffa3a8a-9ad8-4ab5-b380-4af079e7d732)

---

## June 17: render prep and doc screenshots
Took a bunch of high-res screenshots of all the major assemblies and subparts. Cleaned up the CAD for rendering by hiding constraints and sketches. Labeled parts using callouts. Exported STEP and DXF files for fabrication. Checked file exports for errors and zipped the final folder. Ending the design phase for now until money shows up.

**hours spent:** 2  
![Fuselage 5](https://github.com/user-attachments/assets/68180676-70a3-4a88-9655-ddbd1ac95157)

![image](https://github.com/user-attachments/assets/74c2aefa-7a8a-4f6c-853d-a7fcd8631d6c)

