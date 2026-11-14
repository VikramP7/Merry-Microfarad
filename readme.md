*<div align="right"> Vikram Procter | Nov 14, 2026 </div>*

# Merry Microfarad (TWNKL-100µ) - README

<img src="./pics/" width="100%" alt="Finished Project">

*Silent Night, Holy Night, Low Quiescent Current*

A Christmas ornament powered by Christmas spirit and photons. By harvesting energy from lights around, a small capacitor bank is charged enough to produce a twinkle by releasing the energy into some LEDs. Once the cap bank is drained again the cycle repeats charging the bank again till charged enough for the next twinkle.

**Contents:** [Project Overview](#project-overview) · [TWNKL-100µ Board](#twnkl-100µ-board) · [Custom Dev Board](#custom-dev-board)

---

## Project Overview
- General explaination
- Parts list (key parts)
- Its structure and shape
- Dev board vs real board

## TWNKL-100µ Board
- Solar cells: power outputs, currents, voltages, and their topology
- LEDS: type, potential model numbers, 
- Capacitor bank: current and power budget, size of cell based on solar capacity and led discharge requirements 
- Comparitor and disharge mosfet
- Counter Twinkle "animation"
- Dev board interface

## Custom Dev Board
- Which microcontroller
- If the microcontroller can't use its own ADC's external super-low-current adc's for cap bank voltage tracking
- Current-voltage curve tracer
- Cap charge twinkle testing
- Dev LEDs for testing current pulse amplitudes and widths
- Dev LEDs for usb power indication, debug, and display, maybe even a 7-seg if feeling crazy (but serial debug should be more than enough).
- Light sensor
- TWNKL-100µ board interface