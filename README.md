## OFF: Dual-channel offset/voltage generator

Use it to generate a steady voltage, or to apply a DC offset to another signal (eg. you have a through-zero VCO but want to offset the signal such that the output is always positive). Both inputs are normalled together - there will always be a voltage present at the output, even if there is nothing connected to the input; this is ideal if you just need a variable voltage source. Otherwise, any input voltage will be offset, but note that clipping will occur if you exceed the maximum voltage handled by the op-amps (usually around +/-10V for TL-series chips)

If you're building the kit, note that the values of RV1/RV2, R8/R9 and R15/R16 will affect the range of voltages produced - by default, I provide 100k pots and resistors which will give a range of around +/-8V. This is more than enough for most people and probably as good as you're likely to get since the TL074/084 does not go rail-to-rail. Since the op-amp is a through-hole component you can replace it with something different if you like, providing it's pin-compatible with the TL0x4 series.
