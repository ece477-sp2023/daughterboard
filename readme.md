# Things to change for v3

-   mosfet rotation
-   bulk capacitor on 2.5V plane
-   bulk capacitors directly on all regulator outputs
-   ftdi analog power from 5V
-   1.1V slow start from 3vi, not 3v3

# want to have

-   crystal for fpga?
-   crystal for ftdi?
    -   only if needed
-   indicator LEDs?
    -   power
    -   usb

# make sure before starting v3

-   ftdi chip works
    -   if not, have easy way to program flash

# notes for v3

-   8 layer board might give more space on top
-   don't need 1v1 slow start connected to both 3v3 and 2v5, just use 3v3
-   look at regulator stock for 5->3, don't know if footprint chosen is common / available
