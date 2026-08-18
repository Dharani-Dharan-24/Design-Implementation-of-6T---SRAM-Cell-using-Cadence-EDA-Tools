# Ex No: 04 - Design & Implementation of 6T SRAM Cell Using Cadence EDA Tools

## Aim
The aim is to design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools and verify its functionality through transient analysis simulation.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
   - Open the Cadence Virtuoso tool and set up the working library.
   - Create a new schematic cell view for the 6T SRAM cell design.

### 2. Schematic Design:
   - Select NMOS and PMOS transistors from the library.
   - Construct the 6T SRAM cell with two cross-coupled inverters and access transistors.
   - Connect the wordline (WL), bitlines (BL, BLB), and power supply connections.

### 3. Simulation:
   - Check the design for errors and proceed with simulation.
   - Launch the Analog Design Environment (ADE).
   - Perform transient analysis to verify read and write operations.
   - Set up input stimulus and analyze the output waveform.

## Circuit Diagram

<img width="579" height="442" alt="WhatsApp Image 2026-08-08 at 10 31 23 AM" src="https://github.com/user-attachments/assets/79739195-97b3-42e7-bd29-914e5ede6748" />




## 6T SRAM Truth Table

![Screenshot 2025-03-24 123041](https://github.com/user-attachments/assets/29a8a036-d65d-4a25-ba18-3f1f0e358576)


## Schematic Diagram

#### 1. Schematic of 6T SRAM Cell:

   <img width="940" height="466" alt="WhatsApp Image 2026-08-08 at 10 31 23 AM (1)" src="https://github.com/user-attachments/assets/280ceda0-487a-4a64-82c9-6fee8ac7c53d" />



   <img width="940" height="296" alt="WhatsApp Image 2026-08-08 at 10 31 25 AM" src="https://github.com/user-attachments/assets/cab12f60-7c31-48a1-bf8b-6f2420da4b4b" />



## Output
#### 1. Transient Analysis Output:

   ![Screenshot 2025-03-24 121615](https://github.com/user-attachments/assets/2805525e-1f0d-4ef8-b131-79a3153b7127)

   <img width="940" height="386" alt="WhatsApp Image 2026-08-08 at 10 31 24 AM" src="https://github.com/user-attachments/assets/4ab58fd0-77f3-45ee-99d4-c5a4350026d2" />



## Results:
1. Successfully designed the 6T SRAM cell schematic using Cadence EDA tools.
2. Performed transient analysis, verifying the read and write operations of the SRAM cell.
3. Observed correct switching behavior in response to control signals.


