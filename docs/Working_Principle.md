# Working Principle

The system uses four LDR sensors placed at the four corners of the solar panel.

The ESP32 continuously measures the light intensity received by each LDR.

It calculates:

- Left = Top Left + Bottom Left
- Right = Top Right + Bottom Right
- Top = Top Left + Top Right
- Bottom = Bottom Left + Bottom Right

If:

Left > Right

the horizontal motor rotates towards the left.

If:

Right > Left

the horizontal motor rotates towards the right.

Similarly,

Top > Bottom

moves the panel upward.

Bottom > Top

moves the panel downward.

When all four LDR values become nearly equal, the motors stop and the solar panel faces the maximum light intensity.
