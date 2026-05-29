# Atari NTSC/PAL Antic switch board

<img style="width:40%" src=images/board-top.png>	<img style="width:40%" src=images/board-back.png> (prototype)

Uses two '245 transceivers and holds reset on either Antic to disable them; isolating the control signals may not be necessary but doing it just in case.
Too many wires and two dip-40 chips for me to reliably test on cheap breadboards, so designed a theoretical circuit for a prototype pcb.

2026-5-17 - Untested prototype design
2026-5-28 - Boards recieved from PCBWay, confirmed not working, signal directions through bus tranciever need reworking due to my uncertainty of the i/o of the control lines for Antic.
