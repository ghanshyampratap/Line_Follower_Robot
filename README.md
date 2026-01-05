#  Line Follower Robot

Welcome to our **Line Follower Robot** project!  
This compact and efficient bot is designed to **automatically follow a designated path** using intelligent sensing and control systems. It was developed in **March 2023** as a foundational robotics project with real-world applications.

---

##  Project Overview

This Line Following Bot is built using:
- **IR Sensors** for surface detection
- **Arduino Uno** for control logic
- **Motor Driver (L298N)** for motor control
- **Gear Motors & Wheels** for movement

⚙️ Ideal for use cases like **automated luggage transport** in pharmacies, warehouses, or factories, ensuring efficiency and ease of use.

---

##  How It Works

The core concept is based on **light reflection**:

- **White surfaces reflect** infrared light  
- **Black surfaces absorb** it

###  Here's the logic:

| Surface Type | IR Sensor Output | Arduino Input | Action |
|--------------|------------------|----------------|--------|
| White        | Reflected        | HIGH (1)       | Continue Straight |
| Black        | Absorbed         | LOW (0)        | Turn / Correct Path |

- The **IR transmitter** sends IR rays downward.
- On white, light reflects and is detected by the receiver.
- On black, no reflection is detected, so the Arduino adjusts the motors accordingly.

---

##  Components Used

- Arduino Uno
- IR Sensors (x2 or x3)
- L298N Motor Driver
- BO Motors (Gear Motors)
- Wheels & Chassis
- Battery Pack
- Jumper Wires
- Switch

---

##  Future Scope

- PID-based precision path following
- Obstacle avoidance integration
- Zig-zag or grid-following algorithms

---

##  Images & Videos

🎥 [Watch the Line Follower Robot in Action!](https://youtube.com/shorts/68DSFqbzl2I?feature=share)

---

##  Contributing

Have suggestions or improvements? Feel free to fork and raise a PR!


