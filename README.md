# SilentEnder3v2
My take on silencing an Ender 3 V2

## Steps To Silence

### 1. Replacing fans
First you need a decent hotend-mount and fan duct. [BantaMount](https://bantam.design/mount)
For MOBO I [Remixed](https://www.thingiverse.com/thing:4685274) my own version of cover with no support required.
PSU: I went with [this](https://www.thingiverse.com/thing:4546724) cover. (Again: barely any support, just print it axial, on the edge)

Then I choose these Fans:
* Hotend and Partcooling Fan: [Multicomp MC002684](https://hu.farnell.com/multicomp/mc002684/axial-fan-40mm-5vdc-7cfm-20-6dba/dp/3050784)
* PSU and MOBO Fan: [ SilentiumPC Zephyr 92](https://www.silentiumpc.com/en/product/zephyr-92/)

#### Hotend and Part Cooling
Replacing these changed the ~84dB noise to ~50dB.
> **Note:** You will need to use 24V->5V DC-DC stepdown converter for these fans. I used [these](https://www.hestore.hu/prod_getfile.php?id=11935).

## Other Upgrades

###Cable management
* Rotate your Z motor to make the connector pointing to the center. This removes stress from the cables.
* Pull your X gantry cables to the left side instead of the back. This creates extra sapce, and relieves the cables from unnecessary stress. 

### External Spool Holder
TODO.

### Heatsinks
TODO.

### Octoprint
TODO.

### Dual Z axis
I have added a second Z rod for improvements stablility on the X gantry. This removes Z wobbling and reduces the need for releveling the bed.

##Future upgrades
1. MOBO replacement
2. Stepper drivers in non legacy mode
