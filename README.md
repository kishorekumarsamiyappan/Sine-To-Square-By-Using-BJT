

# Sine to Square Wave Converter and Amplifier
---

This project implements a circuit to convert a sine wave into a square wave, then amplify the output using a BJT amplifier. This is useful in digital signal processing, clock generation, and audio applications.

---

## 🚀 Features

- Zero-crossing detection using op-amp comparator
- BJT common-emitter amplifier
- Clean, low-distortion square wave output
- Ideal for PWM, clock signals, and signal conditioning

---

## 🛠️ Circuit Overview

- **Comparator Stage**
  - LM358 op-amp configured as a comparator
- **BJT Amplifier Stage**
  - 2N2222/BC547 common-emitter amplifier

---

## 📐 Block Diagram

  ![Flow Chart Whiteboard in Red Blue Basic Style](https://github.com/user-attachments/assets/cd7bfe9a-7aa8-4327-a10d-13343a7fdb4b)
  
---

## 📊 Results

- Input: 5Vpp sine wave at 1kHz
- Comparator output: 0–12V square wave
- Amplifier output: ~15Vpp square wave
- Clean waveform, sharp transitions, suitable for digital logic

---

## 🎞️ Simulation Clip

Below is a short clip of the simulated waveform transitions:

  [Upoading sine-to-square-bjt.mp4…](https://github.com/user-attachments/assets/a42fbcdf-98db-46c6-8ca9-1da4caf179a9)

---

## 📁 Files

- `EC FINAL.pdf` : Project report
- `EC Output.pdf` : Output screenshots
- `sim_demo.gif` : Simulation animation

---

## 📜 License

MIT License

---

> *Made with ❤️ by Kishore Kumar K, Kishore Kumar R, and Kishore Kumar S.*
