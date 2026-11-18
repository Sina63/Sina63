# Hi, I’m Sina 👋

### I build things that move.

Mechanical design · Electronics · 3D printing · Python

I turn ideas into working prototypes, test them on the bench, and share what I learn along the way.

---

## ⚙️ DIY Motor Dynamometer Using Raspberry Pi

**Goal:** Find out how a DC motor performs under different loads and supply voltages, and identify where it delivers the most useful shaft power for the electricity it draws.

A dynamometer (dyno) applies a controlled load to a motor while it runs. In this build, the motor drives a generator, and a Raspberry Pi switches resistor loads in steps. Repeat the sweep at different supply voltages to compare how the motor behaves.

- **Measure:** shaft speed (RPM), motor voltage, current, and reaction force at each load setting.
- **Calculate:** torque from the reaction force, shaft power from torque and speed, and electrical input power from voltage and current.
- **Compare:** estimated efficiency (shaft power ÷ electrical input power) across loads, RPMs, and voltages. The dashboard shows live readings and saves each run.

**Example:** In a 6 V sweep, speed fell from about **5,040 to 3,830 RPM** while current rose from **0.48 to 1.90 A**. Torque and efficiency estimates are provisional until the torque measurement is independently verified.

**[Explore the project →](https://github.com/Sina63/raspberry-pi-motor-dyno/tree/main)**

## 🧵 DIY Carbon Fiber Winder Using Raspberry Pi

A DIY carbon fiber winding machine built on a budget of around $500.

**[Explore the project →](https://github.com/Sina63/500-dollar-carbon-fiber-winder)**

---

Build. Test. Improve. Repeat.

