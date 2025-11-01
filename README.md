# Ardino Pushbutton Led Control
A simple Arduino project demonstrating LED control using a pushbutton input.

## 🎯 Introduction / Objective
This project demonstrates the **basic concept of digital input and output** using an Arduino.  
When the pushbutton is pressed, the LED turns **ON**, and when released, the LED turns **OFF**.  
It’s a simple yet fundamental project to understand **how Arduino reads input signals and controls output devices**.

---

## ⚙️ Components Used
| Component | Quantity | Description |
|------------|-----------|-------------|
| Arduino UNO | 1 | Microcontroller board used to run the code |
| Breadboard | 1 | For connecting the circuit without soldering |
| LED (any color) | 1 | Visual output indicator |
| Pushbutton | 1 | Input device to control the LED |
| Resistor 220Ω| 1 | Limits current to the LED |
| Resistor 10kΩ | 1 | Used as a pull-down resistor for the button |
| Jumper Wires | As needed | For making connections |

> 💡 **Note:** In my prototype, I used a 10 kΩ resistor for the LED because I didn’t have a 220 Ω one available.  
> The LED still worked but was very dim. Recommended value: **220 Ω**.


## 🔌 Circuit Diagram / Wiring

**Connections:**
- **Digital Pin 13** → **Resistor (220Ω)** → **LED Anode (+)**  
- **LED Cathode (–)** → **GND**  
- **Pushbutton one side** → **+5V**  
- **Pushbutton other side** → **Digital Pin 2**  
- **10kΩ resistor** between **Pin 2** and **GND** (pull-down resistor)

## 🔌 Circuit Diagram / Wiring

### Breadboard View
![Breadboard View](images/breadbordview.png)

### Schematic View
![Schematic Diagram](images/schematic.png)

## How It Works


