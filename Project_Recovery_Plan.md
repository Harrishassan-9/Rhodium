# Project Recovery Plan & Detailed Installation Timeline
**Project:** SOTA Residential Tower (Rhodium)
**Date:** December 25, 2025
**Target Completion:** December 2026

## 1. Project Overview & Architecture
**Structure:**
*   **Basement 1 & 2:** Parking, MEP Plant Rooms.
*   **Floors 1–6:** Residential Units (Studio, 1-Bed, 2-Bed).
*   **Floor 7:** Amenities/Recreation (Gym, Pool, Lounge).
*   **Floors 8–22:** Residential Units.
*   **Top Floor:** 2 Luxury Penthouses.

**Current Status (Baseline - Dec 2025):**
*   **Grey Structure:** 100% Complete.
*   **Exterior Finishing:** 100% Complete.
*   **Flooring:** Tile laying completed up to 6th Floor.
*   **Procurement:** All selections finalized & approved. Kitchens ordered.
*   **Active Works:** Lifts (In Progress), Door/Window frames (In Progress).

**Core Objective:**
Shift form procurement/structural focus to a strict, logistics-heavy **Installation & Commissioning** schedule to meet the December 2026 deadline (12 Months remaining).

---

## 2. The "SOTA" Granular Checklist (Installation Only)

### A. Information Technology & Smart Automation (Living/Dining/Bedrooms)
*   [ ] **Home Automation Panels:** Install & terminate CAT6/KNX control panels (e.g., Crestron/Control4/Lutron).
*   [ ] **Smart Curtains:** Install motorized curtain tracks (recessed in pelmets) and terminate power/data.
*   [ ] **Invisible Audio:** Install plaster-over wall speakers or ceiling speakers (Sonos/Bose) before final paint.
*   [ ] **Media Walls:** Install structural support for floating heavy-duty TV mounts.
*   [ ] **Climate Control:** Install linear slot diffusers (alignment with lighting plan is critical).
*   [ ] **WIFI Access Points:** Ceiling mount installation & PoE termination in central corridors/living areas.

### B. High-End Bathrooms
*   [ ] **Concealed Cisterns:** Final plumbing connection, pressure testing, and boxing-in (Geberit or similar).
*   [ ] **Niche Construction:** Waterproofing and tiling of shower niches with pre-wired LED strip channels.
*   [ ] **Rain Showers:** Ceiling mounting of flush rain-heads; check for level and equal pressure.
*   [ ] **Line Drains:** Installation of linear infinity drains; gradient verification.
*   [ ] **Vanity Lighting:** Installation of under-vanity LED motion sensors.
*   [ ] **Mirror Systems:** Install heated demister pads behind mirrors; clear silicone sealing.
*   [ ] **Glass Enclosures:** Floor-to-ceiling toughened glass installation; acoustic & water sealing.
*   [ ] **Stone Countertops:** Mitered edge alignment and sealing.

### C. Kitchens & Joinery
*   [ ] **Carcass Installation:** Leveling and fixing of kitchen cabinet carcasses.
*   [ ] **Island Installation:** Plumbing and electrical feed pull-throughs for islands.
*   [ ] **Stone Splashbacks:** Book-matched stone installation (measure twice, cut once).
*   [ ] **Appliance Integration:** Flush mounting of ovens/microwaves; clearance checks for ventilation.
*   [ ] **Under-Cabinet Lighting:** Routering channels for invisble LED strip installation.

### D. Bedrooms
*   [ ] **Wardrobe Assembly:** Internal carcass erection, installing soft-close drawer runners.
*   [ ] **Wardrobe Lighting:** Door-sensor activation switches and internal LED strips.
*   [ ] **Reading Lights:** Hardwiring of articulating bedside reading lamps.
*   [ ] **Acoustic Seals:** installation of drop-down acoustic seals on apartment entry doors.
*   [ ] **Headboard Panels:** Mounting of upholstered or veneer massive headboard panels.

### E. Common Areas & Amenities (Floor 7)
*   [ ] **Pool Equipment:** Sand filter installation, dosing pump calibration, heat pump syncing.
*   [ ] **Gym Flooring:** Impact acoustic underlay + rubberized high-performance flooring.
*   [ ] **Spa/Sauna:** Vapor barrier installation, cedar wood cladding, heater commissioning.
*   [ ] **Lounge:** Joinery for reception desk, feature lighting installation (chandeliers).

### F. Building Systems (MEP) & Basement
*   [ ] **HVAC Plant:** Outdoor VRF unit rigging (Roof/Mechanical floors), copper pipe vacuum testing.
*   [ ] **Generators:** ATS (Automatic Transfer Switch) syncing and load bank testing.
*   [ ] **Fire Alarm:** Smoke detector head installation, loop testing, interface with access control.
*   [ ] **Lifts:** Guide rail alignment, cabin assembly, call button wiring, safety gear testing.
*   [ ] **BMS:** Building Management System sensor calibration (CO2 sensors in parking, temp sensors in corridors).

---

## 3. Visual Project Timelines (Gantt Charts)

We have broken down the visualizations into three critical views:
1.  **Macro Timeline:** The high-level phasing for the entire building.
2.  **MEP Systems:** Detailed timeline for HVAC, Electrical, and Plumbing.
3.  **Interior Fit-out:** The aesthetic completion sequence.

### A. Macro Project Schedule (Jan - Dec 2026)
*Overview of the consolidated phases for the entire tower.*

```mermaid
gantt
    title Master Project Schedule - SOTA Tower
    dateFormat  YYYY-MM-DD
    axisFormat  %b %Y
    
    section Preliminaries
    Lifts Installation (Active)       :active, lift1, 2025-12-01, 2026-03-15
    Site Mobilization (Interiors)     :mob1, 2026-01-01, 2026-01-14
    
    section MEP Phase (Floors 8-22)
    MEP 2nd Fix (Rough-in)            :crit, mep2, 2026-01-15, 2026-03-30
    HVAC Piping Pressure Tests        :crit, hvac_test, after mep2, 10d
    
    section Interior Civil Works
    False Ceiling Framing             :ceil1, 2026-02-15, 2026-04-15
    Screeding & Levelling             :screed, 2026-03-15, 2026-05-15
    Flooring (Stone/Wood/Tile)        :floor, after screed, 90d
    
    section Joinery & Finishes
    Fitted Joinery (Kitchens/Robes)   :join, 2026-06-01, 2026-08-31
    Painting (1st Coat)               :paint1, 2026-07-01, 2026-09-15
    MEP 3rd Fix (Lights/Switches)     :mep3, 2026-08-01, 2026-10-15
    Final Finishes (Wallpaper/Paint)  :fin, 2026-09-15, 2026-10-30
    
    section Handover
    Testing & Commissioning           :tcc, 2026-10-01, 2026-11-30
    Snagging & De-snagging            :snag, 2026-11-15, 2026-12-20
    Project Handover                  :milestone, 2026-12-31, 0d
```

### B. MEP Specific Timeline (HVAC, Electrical, Plumbing)
*Detailed breakdown of the crucial mechanical systems.*

```mermaid
gantt
    title MEP Systems Timeline (Detail)
    dateFormat  YYYY-MM-DD
    axisFormat  %b
    
    section HVAC (AC)
    Outdoor Unit Rigging (Roof)       :hvac1, 2026-01-10, 2026-02-10
    Copper Piping Risers              :hvac2, 2026-01-15, 2026-03-01
    Ducting Installation (F8-F22)     :hvac3, 2026-02-01, 2026-04-01
    Slot Diffuser Alignment           :hvac4, 2026-04-15, 2026-05-30
    System Gas Charging               :hvac5, 2026-09-01, 2026-09-30
    Air Balancing & Comm.             :hvac6, 2026-10-01, 2026-11-15
    
    section Electrical & Smart
    Containment & Tray Work           :elec1, 2026-01-05, 2026-02-28
    Wiring Pulling (Automation)       :elec2, 2026-02-01, 2026-03-30
    DB Dressing & Termination         :elec3, 2026-04-01, 2026-06-01
    Switch/Socket Install             :elec4, 2026-08-15, 2026-10-01
    Program Smart Panels              :elec5, 2026-10-15, 2026-11-30
    
    section Plumbing
    Vertical Stacks Final Conn.       :plumb1, 2026-01-10, 2026-02-28
    Concealed Cistern Install         :plumb2, 2026-02-01, 2026-03-15
    Pressure Testing (Water)          :crit, plumb3, 2026-03-15, 2026-03-30
    Sanitary Ware (Sinks/Toilets)     :plumb4, 2026-09-01, 2026-10-15
```

### C. Interior Fit-Out & Amenities Timeline
*Sequence for aesthetics, amenities, and penthouses.*

```mermaid
gantt
    title Interiors, Penthouses, & Amenities (Floor 7)
    dateFormat  YYYY-MM-DD
    axisFormat  %b
    
    section Typical Units (F8-F22)
    Ceiling Closure (Gypsum)          :int1, 2026-04-01, 2026-05-30
    Tiling (Bathrooms)                :int2, 2026-04-15, 2026-06-15
    Flooring (Living/Bed)             :int3, 2026-05-01, 2026-07-15
    Kitchen Install                   :int4, 2026-06-15, 2026-08-15
    Wardrobe Install                  :int5, 2026-07-01, 2026-09-01
    
    section Amenities (Floor 7)
    Pool Shell & Waterproofing        :amen1, 2026-03-01, 2026-04-30
    Gym/Lounge Flooring               :amen2, 2026-06-01, 2026-07-30
    Equipment Install                 :amen3, 2026-08-01, 2026-09-15
    Furniture Install                 :amen4, 2026-10-01, 2026-10-30
    
    section Penthouses (Top Floor)
    PH Special Design/Procure         :ph1, 2026-01-01, 2026-03-30
    PH MEP & Framing                  :ph2, 2026-04-01, 2026-06-30
    PH High-End Finishes              :ph3, 2026-07-01, 2026-10-30
    PH White Glove Clean              :ph4, 2026-11-01, 2026-11-30
```

---

## 4. Logic & Critical Dependencies (Rules of Engagement)

1.  **The "Dusty vs. Clean" Rule:**
    *   No "Clean" trades (Painting, Siliconing, Switch-plate install) allowed on a floor until "Dusty" trades (Tile cutting, Gypsum sanding) are 100% demobilized and vacuumed from that floor.

2.  **The Vertical Logistics Rule:**
    *   Lifts are priority for **Materials** up to 8AM-9AM.
    *   Lifts are priority for **Labor** 8AM-9AM.
    *   Trash removal occurs **Post-5PM** only to avoid clogging vertical transport during working hours.

3.  **MEP Sequencing:**
    *   Pressure tests (Water/Gas/Refrigerant) must be witnessed and signed off **BEFORE** any wall or ceiling is closed. No exceptions.
    *   Floor boxes requiring cut-outs must be defined **BEFORE** flooring starts.

4.  **Joinery Protection:**
    *   Kitchen stone benchtops installed immediately after cabinets.
    *   Once installed, ALL joinery must be wrapped in heavy-duty cardboard protection until Snagging Phase.
