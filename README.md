# Here you will find PCB Designs for your Own FlexLight

## Software used

We create all our PCB designs using EasyEDA to enable fast and easy ordering of PCBs from jlcpcb.
Just import the project files and tinker away.
For even easier ordering you can also just download the Gerber, BOM and CPL files that are available in the gerber directory of each PCB folder.


## PCB Designs available
### LED PCB:

![LED PCB](/led_pcb/PCB_Layout.png)

The led PCB holds 8 argb ws2813-mini LED's for illumination and is soldered to each one of the main PCBs via the 5 connecting plates in the lower middle.
it measures 140 x 5,4 in mm, we wanted to have this one as thin as possible to not add unneccesary thickness to the flexlight case.

The gerber files of this PCB are pre-panelized to hold 6 PCB's in one production run. This was needed for JLCPCB's SMT assembly since their minimum PCB size is 20mm x 20mm and our LED PCB width is just 5.4mm, that way if you order with the pre-made gerbers at jlcpcb you will end up with a minimum order of 30 LED PCBs which should be enough for 10 triangle shaped flexlight nodes


### Inteconnect PCB:

![Inteconnect PCB](/interconnect_pcb/PCB_Layout.png)

The Interconnect PCB is used to connect 2 nodes together, it is probably the most simple and most cheap PCB of our project, dosnt hold any components, just order and use.
We use 2 contacts for 24v and GND to be able to deliver up to 6A to the Flexlight array and power up to 60 nodes safely from a single power source.
