# 🚦 Modern Traffic Light using 555 Timer IC

## 🧠 Objective
To design and simulate a **Modern Traffic Light Circuit** using **two 555 Timer ICs**, mimicking real-world traffic signal operations with basic electronic components.

---

## 🧰 Components Used

- 2 × 555 Timer ICs  
- 1 × Red LED  
- 1 × Yellow LED  
- 1 × Green LED  
- Resistors:  
  - 100kΩ  
  - 68kΩ  
  - 3 × 330Ω  
- Capacitors: 2 × 100µF  
- Breadboard & connecting wires  
- 9V Power Supply

---

## 🔁 Working Principle

- **IC1** controls the Red and Green LEDs, alternating them based on timing set using resistors and capacitors connected to Pins 6 and 7.
- **IC2** is responsible for blinking the Yellow LED briefly between transitions, representing caution.
- The cycle follows this pattern:
  - T1: Red ON
  - T2: Yellow ON
  - T3: Green ON
  - T4: Yellow ON

---

## ⏱ Timing Table

| Time Slot | LED State     | Signal Description  |
|-----------|---------------|---------------------|
| T1        | Red ON        | Stop                |
| T2        | Yellow ON     | Transition Warning  |
| T3        | Green ON      | Go                  |
| T4        | Yellow ON     | Transition Warning  |

---

## 🏭 Real-Time Application

- Can be scaled for real-world traffic signal automation.
- Educational tool to understand timing and control in electronics.
- Basis for smart traffic systems using microcontrollers.

---

## ✅ Conclusion

This project demonstrates a simple yet effective use of **555 Timer ICs** to build a basic traffic light system. It shows how simple analog components can be combined to mimic real-world digital systems and applications.


