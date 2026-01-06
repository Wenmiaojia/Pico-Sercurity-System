# Pico-Security-System
A raspberry Pi Pico W based sercurity system with a physical mechanism
## Hardware set up
- **Microcontroller:** Raspberry Pi Pico W
- **Display:** 1602 LCD (Parallel Mode)
- **Lock:** SM-S2309S Servo Motor
- **Input:** 3x4 Matrix Keypad (Mechanical Switches)
- ## Pin Mapping
| Component | Function | Pico Pin |
| :--- | :--- | :--- |
| LCD | RS, E, D4-D7 | GP16, GP17, GP18, GP19, GP20, GP21 |
| Servo | PWM Signal | GP22 |
| Power | VCC (5V) | VBUS (Pin 40) |

## Required Components
- 10k Potentiometer (for LCD Contrast)
- 100uF Electrolytic Capacitor (for Motor Stability)
### 3D PCB Render
![3D Render](3D%20render%20of%20the%20PCB.png)

### Schematic Diagram
![Schematic](Schematics%20image.png)

### PCB Layout and Routing
![PCB Design](PCB%20design%20images.png)
- 
