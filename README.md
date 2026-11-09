
# PulsePad

PulsePad is an ultra-compact, open-source 4-key macropad powered by the **Seeed Studio XIAO RP2040** microcontroller.

I wanted to make a small macropad with four mechanical switches that could be used for shortcuts and other frequently used actions. I designed the PCB and schematic in KiCad and also worked on a 3D enclosure to fit the board.

The design uses the XIAO RP2040 as the main controller, with four mechanical switches connected to it. The idea is to keep everything compact without making the PCB or enclosure unnecessarily complicated.

## Features

- 4 mechanical switches
- Seeed Studio XIAO RP2040 microcontroller
- Custom PCB designed in KiCad
- Custom 3D enclosure
- Compact design
- Open-source hardware

# 3D Model

This is the overall 3D model of PulsePad, showing how the PCB, switches, keycaps, and enclosure fit together.

![3D model](https://github.com/user-attachments/assets/913311f5-1c7a-4a23-9f92-116b6e7109b0)

# 3D Front View of PCB

![Front 3D PCB](assects/front-3d-pcb2.PNG)

# 3D Back View of PCB

![Back 3D PCB](https://github.com/user-attachments/assets/55e56140-c485-4525-98f2-16c6e7a1c03d)

# PCB

The PCB contains the four mechanical switch positions and the footprint for the XIAO RP2040. I designed the layout in KiCad and arranged the components to keep the board as compact as possible.

![PCB](assects/front-pcb2.PNG)

# Schematics

The schematic shows the connections between the four mechanical switches and the XIAO RP2040.

![Schematics](https://github.com/user-attachments/assets/c4044104-b098-40e8-b052-fe3f63b9280d)

# How It Works

The XIAO RP2040 is responsible for reading the inputs from the four mechanical switches.

Each switch is connected to a GPIO pin on the microcontroller. When a key is pressed, the RP2040 can detect the input and the firmware can use it to trigger a keyboard shortcut or another assigned action.

The keys can be configured for different functions depending on how the firmware is set up.

# Enclosure

I also designed a 3D enclosure for the PCB. It is made to fit the board and switches while keeping the overall size small.

The enclosure can be 3D printed and modified if any adjustments to the design are needed.

# Design Files

The project includes the KiCad schematic and PCB design files, along with the 3D model of the board and enclosure.

These files can be used to inspect the design, make changes, or manufacture your own PulsePad.

## Acknowledgements

This project was designed using **KiCad EDA**. Thanks to the KiCad developers and the open-source community for making such a useful tool available for hardware design.

---

## License

This project is open-source. Feel free to modify, manufacture, and adapt it for your own personal use!

---

## Bill of Materials (BOM)

The following table contains the components required to build one PulsePad, along with their footprints, quantities, purchase links, and estimated prices.

## Bill of Materials (BOM)


### Main BOM


| **Item** | **Link** | **Quantity** | **Cost (USD)** | **Notes** |
|---|---|---:|---:|---|
| Seeed Studio XIAO RP2040 | [Robu.in](https://robu.in/product/seeed-studio-xiao-rp2040-v1-0/) | 2 | $13 | $6.5 each |
| Mechanical switches | [Amazon.in](https://www.amazon.in/dp/B0HJYNT2W7) | 1 pack | $7 | Pack of 40 |
| Gradient keycaps | [Amazon.in](https://www.amazon.in/dp/B0HGLWF4Q1) | 1 pack | $11 | 133-piece set |
| Custom PCB | [JLCPCB](https://jlcpcb.com/) | 5 | $12.00 | PCB fabrication |
| Enclosures | N/A | 5 | $0.00 | Self-printed |


### Cost Summary


| **Item** | **Cost (USD)** |
|---|---:|     
| XIAO RP2040 | $13 |
| Mechanical switches | $7 |
| Gradient keycaps | $11 |
| PCB fabrication | $12.00 |
| Enclosures | $0.00 |
| **Total** | **$43** |

