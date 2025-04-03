# Potentiostat-HOPE-Final-Project
HOPE Final Project -- Potentiostat for applying cyclic voltammetry to electrolyte

TO-DO LIST:
- Figure out microcontroller and ADC/DAC connections; ensure that ADC/DAC has 12- to 16-bit resolution
- Use voltage regulator and associated circuit components for microcontroller
- Find best values for resistors
- Generate BOM
- Maybe simulate on LTspice??

NOTES (REFER TO POLARSTAT PAPER AS NECESSARY):
- Blocks A, B, D, and E: uses OPA2277 high-precision operational amplifiers
- Block C: uses TL074 transimpedance amplifier
- Blocks F, G, and H: uses INA128 instrumentational amplifiers
- Block C uses a TL074 Transimpedance Amplifier (TIA). It is cost-effective, but it is not the best option (a really good one would be ~$40)
- May need to fix Rg resistor values based on how much the voltage in the electrodes varies
