# Homelab

A little homelab I created to learn more things and automate some of my tasks. A full list of parts and guide is below ⬇

## Hardware

[Dell Optiplex 7050](https://www.dell.com/support/manuals/en-us/optiplex-7050-sff/optiplex-7050-desktop-sff-om/processor-specifications?guid=guid-8ca53ab2-a85d-42d5-9106-5214220306aa&lang=en-us)
  - I5-6500, 16gb Ram, 256gb SSD, 1tb HDD.
  - Hosts Wazuh and K3S.

2x Raspberry Pi 4, 4gb Ram, 1x Raspberry Pi 3 B+ 2gb Ram
  - Cooling: Pi 4: [Pimoroni Fan Shim](https://smile.amazon.com/Pimoroni-Fan-Shim-Raspberry-PI/dp/B07TTTCN8H/ref=sr_1_2?crid=LM5J4HI7ALMC&keywords=raspberry+pi+fan+shim&qid=1658377482&sprefix=raspberry+pi+fan+%2Caps%2C88&sr=8-2), PI 3: .....A stack of copper pennies 😅
  - [3D Printed Raspberry PI Stacked Case](STLs/raspberry_pi_3_stack_v1.stl)

[TRENDNet](https://www.trendnet.com/support/support-detail.asp?prod=515_TEG-S80G#specifications)
  - 8-Port Gigabit GREENnet Switch, connects to all the Pis, (except the 3 B+). Great for low power consumption.

## Software

[Raspbian OS Lite](https://www.raspberrypi.com/software/operating-systems/)
  - I use this on all my Pis, it's lighter than most compatible OS's and makes setup for applications easy.

[PI-Hole](https://pi-hole.net/)
  - No special config, just running this on the Raspberry Pi 3 B+.
