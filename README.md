# Clean Sweep

A remix of the [Sweep](https://github.com/davidphilipbarr/Sweep) (based on the original [Ferris](https://github.com/pierrechevalier83/ferris)) that has a tweaked shape and aims to have a cleaner looking design (in particular the layout of the traces).

There are 8 total variations, with each possible combination of the following options:
- Face up or face down mcu (uses pro micro or clone with same pinout)
- Straight or rounded traces
- Traces primarily on the front or back of the pcb

All designs include just the left half and are reversible, but keep in mind that reversing the pcb also means the traces will be on the opposite side and the mcu will have to be flipped over, so if you wanted to have both a left and right side with front traces and a face down mcu, then you'd need to make both the face down mcu / back traces version and a face up mcu / front traces version (that you would then flip over to use for the right half).
