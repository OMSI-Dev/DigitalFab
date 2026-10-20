<img src = "/Debugging/ref-images/MOSFETS.png" width="650" alt="MOSFETS diagram">

# Debugging Reverse Voltage Protection P-Channel and N-Channel Mosfets

Using `Continuity` and `Voltage` settings on your multimeter to test connections on a `P-Mosfet` or `N-Mosfet`, reference the diagram above. 

## N-Channel
<img src = "/Debugging/ref-images/N-MOSFET.png" width="650" alt="MOSFETS diagram">

###	Measure between	Healthy reading	Faulty reading (what it means)
| # | Measure between | Healthy reading | Faulty reading (meaning) |
|---|---|---|---|
| 1 | Q5 **drain to source** | Open (OL) one way. About 0.4 to 0.7 V the other way in diode mode (body diode). | ~0 Ω both ways: Q5 failed short or has a solder bridge. |
| 2 | Q5 **gate to source** | Open or very high (OL) both ways. | Near 0 Ω: gate shorted to ground. |
| 3 | **LED_DATA side of R5 to Q5 gate** | About 10K (value of R5). | Open: R5 or trace broken. ~0 Ω: R5 bridged. |
| 4 | Q5 **drain to GND** | Open (OL) or very high. | ~0 Ω: LED return path permanently grounded, so LED stays lit. |
| 5 | Q5 **drain to X1-1** (LED terminal) | ~0 Ω (just a trace). | Open: broken trace or bad solder joint. |
| 6 | Q5 **gate to GND** | Open or very high (no gate pull-down in schematic). | ~0 Ω: gate stuck at ground. |
