# 220V AC to 5V DC Transformerless Power Supply

* **Input:** 220V AC, 50/60Hz
* **Output:** 5V DC
* **Output Current:** ~100–150mA
* **Type:** Capacitive Dropper, Non-Isolated
* **Regulator:** LM7805

## Components

* **C4 – 2.2µF:** Capacitive voltage/current dropper
* **R3 – 1MΩ:** Bleeder resistor
* **D1–D4 – 1N4007:** Bridge rectifier
* **C1 – 0.1µF:** Noise filtering
* **C2 – 1000µF:** DC smoothing
* **U1 – LM7805:** 5V voltage regulator
* **C3 – 470µF:** Output filtering
* **D7:** Power indicator LED

## Features

* Compact transformerless design
* Low-cost components
* Suitable for low-power loads
* Regulated 5V DC output

## ⚠️ Safety

* **Non-isolated circuit — dangerous mains voltage is present.**
* Do not touch the circuit while connected to 220V AC.
* Use an **X2-rated capacitor** for C4.
* Do not connect the output to USB, computers, or other user-accessible equipment.
* Use a proper isolated AC-DC supply when electrical isolation is required.

> **Warning:** Working with mains voltage can cause serious injury or death. Build and test only with proper knowledge and safety precautions.
