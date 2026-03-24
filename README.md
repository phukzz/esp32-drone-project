# esp32-drone-project

## 📌 Overview

This project documents the assembly and testing of an ESP32-based drone using the B-CUBE ESP32-S2 Drone V2.0 kit.

The goal is to understand:

* Drone hardware assembly
* Motor control and polarity
* Flight testing and debugging

---

## 🧩 Hardware Used

* B-CUBE ESP32-S2 Drone V2.0 kit
* 1S LiPo Battery (3.7V)

---

## ⚙️ Assembly Process

Detailed steps are in: docs/assembly.md

---

## 🔌 Wiring & Motor Configuration

* M1 & M3: Green motors (Red + Blue)
* M2 & M4: Blue motors (White + Black)

Full wiring guide: docs/wiring.md

---

## 🧪 Testing

* Motor testing via WiFi interface (192.168.4.1)
* IMU sensor validation
* Flight test results

More details: docs/testing.md

---

## 🚀 Results

* Drone successfully assembled
* Motors tested and calibrated
* First successful flight achieved

---

## ⚠️ Challenges

* Motor polarity confusion
* WiFi connection setup
* Battery voltage issues

---

## 📚 What I Learned

* Drone motor control (CW vs CCW)
* ESP32 WiFi-based communication
* Soldering and hardware debugging

---

## 🔗 References

* Espressif documentation: https://docs.espressif.com/projects/espressif-esp-drone/en/latest/gettingstarted.html#pc-cfclient-guide
