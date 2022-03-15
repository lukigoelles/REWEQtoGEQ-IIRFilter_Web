# REWEQtoGEQ-IIRFilter Web

## Manual
1. Measure the Room Impulse Response in REW [1].
2. Use the EQ-tool to perform the filter task of REW. Use "Generic" as preset. This process yields the parameters center frequency, gain and quality of various parametric filters.
3. Export these filter parameters as txt file. (File, Export, Export filter settings as text).
4. Execute *index.html* in a browser. 
5. The script will use biquad filters [2] to generate an impulse response that can be used as equalizer with mcfx_convolver. A table is also generated that contains the gains of a third-octave GEQ.

## References
[1] [Room Equalization Wizard](https://www.roomeqwizard.com/) <br>
[2] Udo Zoelzer: Digital Audio Signal Processing
