# RTB_pattern_gen_adapter
Adapter PCB for RTB2k oscilloscope pattern generator output to BNC or pin header

Connectors used:
Molex 40-02-1602 for pushing onto RTB pattern gen outputs. Needs to be crimped/soldered onto thick single core wire to mount into the PCB.
RS Pro 546-4027 BNCs

Notes:
- An attempt was made to match the output impedance of the pattern gen (about 85 ohms from my measurements) to 50 ohms for a nice clean BNC output. This doesn't seem to have worked, with pretty ugly edges. Maybe more work on matching could help, but I haven't gotten far on it.
- A 3D printed enclosure was also and works well, files included (printing settings could have done with a tune-up though)
- See included photos for an example of each output type and enclosure (back of the BNC one looks messy - originally had a bunch of black hot-melt on it)
