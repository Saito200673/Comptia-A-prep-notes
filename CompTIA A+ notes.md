Troubleshooting theory![[IMG_1723.jpeg]]

Hard drives (fast but not fast as ssd) and ssd’s store data(programs) and the cpu access these to get an copy of the program when it wants to run it 

This gets stored in ram temporarily to make the process faster (when running an program it gets stored in ram for faster access than ssd and hard drives) but it’s expensive compared to these

And when an file wants to be saved its copied from ram to the storage devices(since running an program happens on ram)

Anything with an cpu,ram,storage and an operating system is called an computer 

CPU is an very high performance calculator

Man in the box analogy for explaining the working of the CPU

Machine language is the language used by CPU’s  which uses binary(0,1)

1=on and 0=off 

The the different patterns of 1’s and 0’s are called programs and the ppl who make these are programmers 
 
8 bits=1 byte 

There’s also registers in the CPU’s which does processing 

Clock (which tells the CPU to do something )

Clock speed=the no. of cycle tasks per second 

Core= no of lanes of data can flow back and forth 

Arm chip=Advanced Risk Machine 
Which uses reduced set of instructions for higher processing speeds (RISC) used it raspberry pi and arduino

APU’S=Accelerated Processing Units are cpu with graphics card built in (igpu)

**CPU ARCHITECTURES**
x86 is 32bits which has an 32bit memory lane or data bus(max ram=4gig)
x64 is 64bits which has an 64bit memory lane or data bus (max ram=16 exabytes)
x86-64 64bit primary but also 32bit supported 
IA-32(intel crappy way of 32bit sys)

**CPU generations and naming **


![[Pasted image 20241124102000.png]]
![[Pasted image 20241124102106.png]]

Thermal paste is used to increase the surface area between the cpu and the heat sink by filling the gaps in the surface of the heatsink 

Applying thermal paste in pea size generally good 

**Ram**
Has different speeds and capacity 
Measured in mhz(speed)
There are single sided (256mb,1gig,4gig…)and double sided ram(512,2gig,8gig)
Different types of ram
1.sdram(synchronous dynamic random access memory )
2.ddr(double data rate ram )
3.ddr2,ddr3…,ddr5

EEC(error checking code) or parity
Used in rams to correct corrupted data
Usually an extra chip in the ram 
Used mostly in server which has high importance for data  

**VIRTUAL MEMORY **
Virtual memory uses the mass storage of the computer as ram 
But in turn it makes
![[Pasted image 20241124173126.png]]
![[Pasted image 20241124180811.png]]

The bios is on an chip in the motherboard and it’s called an firmware since it’s burned into the chip

The bios(basic input output system) has 
1.CMOS (which makes the bios nonvolatile )
2.POST (power on self test)
3.programable code which provides an interface to talk to the components of the computer without booting into the pc 

**POST**
power on self test 
1.Used to check if all the components in the motherboard are working as intended and gives an beep to say that it’s functioning correctly it’s done by an speaker in the mobo
2.has different beep codes for different issues in the mobo 
3.can also use an post card to check for issues which displays the errors in the form of hexadecimal (in 2 digits)
4.its used when there are more issues going on with the post that it can’t use the speaker in the mobo and also the display 

**UEFI**(unified extensible firmware interface)
It’s the modern version of bios 
Has extra features compared to the 16bit bios
1.Can be used to overclock the cpu
2.Keep passwd for booting devices
3.And password for booting into an os
4.Enabling or disabling I/o devices

**CMOS**(complimentary metal oxide semiconductor )![[Pasted image 20241125135151.png]]
**Motherboards**
The different types of mobos you can find in an system are 
1.ATX(12x9.6 inches )
2.mATX(9.6x9.6inches)
3.ITX
4.mini-ITX

**CHIPSETS**
In older mobos there were chips which were installed just for a particular process (for mouse,keyboard,monitor….)
Later as technology improved 
Many of these process were integrated into two chips
Since these performed different tasks these were called chipsets
1.the north bridge(present in the north side of the mobo)
2.the south bridge (present in the south side of the mobo)

**PSU**
1.Although it’s called power supply it doesn’t produce electricity but instead it step downs the voltage
2.it converts AC to DC
One PSU differs from another by having different wattage it can give and also by efficiency 
It’s rated according to its efficiency 
PSU originally had 20 pin but later 4 extra pins were added to deliver extra power 
You can use ATX12V extension to do it 
Yellow connectors provide 12v
Red 5v 
Orange 3.3v
Some of the other connectors in an psu are :
1.pcie 
2.SATA
3.Molex
![[Pasted image 20241128191229.png]]
There are two types of PSU 
1.where the wires from the psu are soldered to it 
2.modular(the wires are detachable from the psu)


![[Pasted image 20241125171442.png]]
**MASS STORAGE MEDIA**
1.HDD(hard disk drives)
Contains moving parts
Slower compared to ssd
But there isn’t much data degradation over time 
Used to store big chunks of data 
The smallest unit is sectors
2.SSD(solid state drives) 
Faster than hdd
Doesn’t contain moving parts 
Data degrades much faster than hdd
Used to store os for faster booting times 
The smallest unit is blocks 
3.optical media (5.25 inches)
The smallest unit is tracks

**LBA(logical block addressing)**
Allocation of storage 
Used to assign data to the smallest units in the storage media when an data is stored 

Different methods used to express storage 
Kilo=1000(base 10)
Kibi=1024()

Different form factors for storage media 

1. 5.25 inches
2. 3.5 inches 
3. 2.5 inches
4. 1.8 inches 
5. M.2



![[Pasted image 20241127071822.png]]
![[Pasted image 20241127072732.png]]
![[Pasted image 20241127160323.png]]
![[Pasted image 20241127162703.png]]
![[Pasted image 20241127195842.png]]
Hardware RAID is done by connecting hardware controller to the mobo or by just using the pre-existing controller in the mobo itself by using another system setup similar to bios but just for RAID

Software RAID is done by using OS in win you can do this by disk management or by using storage spaces

**USB STANDARDS**
USB A (in thumb drives laptops …)
USB B(in scanners)
USB MINI B(cameras and scanners)
USB MICRO B (used in charging phones)
USB 3.0 MICRO B
USB C 

![[Pasted image 20241201133156.png]]If there’s an white piece of plastic in the USB A it’s ver 1.1
Black ver 2.0
Blue ver 3.0 or 3.0 gen 1
Teal ver 3.1
Orange,red or yellow is used for changing 

Every mobo has an USB controller which makes the devices to work when plugged in 
Which gets cmds are downstream connectors (A connector )
Which gives out cmds are upstream connectors(B connector)

Max no.of usb ports possible in an mobo is 127

**THUNDERBOLT AND LIGHTNING PORTS**
THUNDERBOLT HAS 4 DIFF VER.
thunderbolt 1 (two channels 10 gbps X 2) it’s mini display port 
Thunderbolt 2 (20gbps) it’s mini display port
Thunderbolt 3 Thunderb(40 gbps) it’s usb c 

Thunderbolt ports are used for data transfer,display ports,charging 

LIGHTNING PORTS
similar to thunderbolt but it’s proprietary to apple devices
But nowadays it’s moved towards usb-c
macOS also started supporting usb-c

**OPTICAL MEDIA**
THREE TYPES OF OPTICAL MEDIA
DVD’S (digital video/versatile disk)
CD’S (compact disks)
BLUE RAYS

![[Pasted image 20241202183332.png]]![[Pasted image 20241202184423.png]]

**SCANNERS AND READERS**

![[Pasted image 20241202185205.png]]

**PERIPHERALS**
![[Pasted image 20241202185554.png]]

**PCI (peripheral component interconnect)**
Used to plug in expansion cards nic’s etc
There also PCIE (E-express ) for faster speeds ![[Pasted image 20241202193531.png]]
![[Pasted image 20241205070111.png]]
![[Pasted image 20241205070559.png]]
Since CCFL needs AC power to work 
COMPONENTS OF AN MONITOR
1.PANEL
2.BACKLIGHT (unless it’s an oled)
3.SLOT FOR POWER SUPPLY AND VIDEO CARD
4.CONVERTERS FROM AC TO DC
5.INVERTERS (only on ccfl monitors)

In monitors the 2 things to look out for are 
1.resolution 
2.response time (the time an pixel takes to go from black to white and back to black )

Frame buffering: when cpu handles the pixel assignment on the monitor 

Nowadays GPUs does the job of assigning pixels but it does a whole lotta fast 

There are also gpus built in the cpu called APU 

The types of connectors in an gpu are
1.VGA
2.DVI-digital visual interface 
3.HDMI-high definition multimedia interface `has two versions hdmi and mini hdmi`  4.DISPLAY PORT(dedicated connector for display) `same as hdmi has both display and mini display port`
Two types of dvi connectors 
1.DVI-I (both analog and digital signals are accepted )
2.DVI-D (only digital signals )

![[Pasted image 20241212133234.png]]

**Aspect ratios and resolutions **

The first aspect ratio which came to monitors were 4:3
VGA-640X480

SVGA-800X600

SXGA-1280X1024

UXGA-1600x1200

The 5:6 aspect ratio

WSXGA-1440x900

WUXGA-1920x1200


![[Pasted image 20241212135003.png]]
![[Pasted image 20241212135038.png]]


![[Pasted image 20241212135759.png]]

There are two types of projectors 
1.bulb based (bulbs are expensive to swap )
2.LED based 

The important thing while buying an projector are 
1.lumens
2.The type of projector (led or bulb)
3.min and max throw (the distance from which you can project stuff)

The troubles we run into while using an projector 
Pincushion 
Keystone

![[Pasted image 20241213162153.png]]
When bulbs overhear they shutdown own their own 


![[Pasted image 20241213164119.png]]

![[Pasted image 20241213170420.png]]

## Types of cables and connectors
10baseT- 10mbs baseband twisted pair 
G-gigabits

Coaxial cables 
 1.RG-59
 2.RG-58(was used it networking)
 3.RG-6
 Twisted pair cable
 Utp  and shielded twisted pair 

UTP has only 100m of connectivity before losing its signal power

RJ-11(TELEPHONES) 4 contacts
RJ-45(used in twisted pair)

 Fiber optics (uses lights instead of electricity like others)
 Has two modes single mode and multi mode
 Single mode(laser) has higher dist coverage 
 Multimode(leds )has less dist converage

Twisted pair has CAT ratings 
CAT 5(100mbps)
CAT 5E(1gbps)
CAT 6(1gbps for 100m and 10gbps for 55m)
CAT 6A(10gbps)

Plenum ratings (ability to resist fire)
PVC
Riser 
plenum 

This is an direct burial cable for networks 

![[Pasted image 20241214162210.png]]
Crimps also has an cat rating 

Cable testers are used to check 
1. Connectivity 
2. Wire mapping (if the wires are placed in the corrrect places on both sides)
When you wire one side as 568A and another as 568B it can be used an crossover cables which is used to connect two computers to transfer stuff 

![[Pasted image 20241214163531.png]]![[Pasted image 20241218164130.png]]

## **Structured cabling **

Structuring the placement of routers and its connections 
Keeping them in main distribution frames where the router is kept 
There are two types of Ethernet cables 
1.solid core cable
2.standard cable (twisted pair)
**The tests done to ensure good operation of the network **


1.Checks using the fox and the hound to see how to wires reach the destination through the walls to the wall outlet 
2.time domain reflectometer (TDR)  used to measure the length of the wire you’re using 
3.




IPv4 has a total of 4 billion addr 

Types of ipv4 addr 
1. Class A (12.x.x.x)  millions hosts
2. Class B (12.13.x.x) 65,534 hosts
3. Class C (12.13.14.x) 254 hosts(.0 & .255 are not used)
4. Class D 
5. Class E

Routers mostly use the .1 in the network 
Subnet masks are used to know that if we’re connecting to our local network or another local network 

To connect to other local networks we use routers 
And this is called default gateway 

You mostly don’t configure ip addr yourself cause of the presence of the DHCP (dynamic host configuration protocol )

Most of the times your router is your DHCP server 

When you DHCP server is down your device uses APIPA to get an ip addr and it is always of the format (169.254.x.x)

Using APIPA you can connect to devices in your local network but you can’t connect to the internet

Ipconfig/release is used to remove an ip addr associated with your device 
And ipconfig/renew is to get an new ip addr to your device 

You can also use the internet troubleshoot to get change your ip addr

And ip addr can also be configured manually in the settings 

## ipv6

Ipv6 addr has 8 groups separated by 7 :  

Adv of ipv6 has more no. Addrs 

How to write the ipv6 addr shorter 
Remove the leading zeros from the groups
When we have three groups filled with zeros we can just shrink it with ::

Minimum addr in an ipv6 environment is two 
Link local addr
Global unicast addr

![[Pasted image 20241219165652.png]]

## PORTS
 Ports range from 0-65535

There are both source and destination port 

Ports are used along with ip addr to find the particular application our computer is accessing 

The different types of ports are 

0-1023 well known ports (http,https)

1024-49151 registered ports (used in big applications )

49152-65535 ephemeral ports (which is used my our computer )


![[Pasted image 20241220162135.png]]

## TCP,UDP and ICMP

TCP is connection based (it checks if the all the packets are sent to receiver )

Most of the data we send to the internet is carried by TCP 

![[Pasted image 20241221073155.png]]

![[Pasted image 20241221074401.png]]
The predecessor to the DNS is an host file which is basically an file which consists of the MAC address and ip addresses of all the devices at that time it refreshes once an day 

![[Pasted image 20241223160941.png]]



### ROUTERS

Has routing cable is them which can be programmed through which it knows where to the send the packets it receive 

Has default gateway when it’s routing table doesn’t have the destination address of an packet it sends it through the default gateway 

There are different types of routers 
Router+switch 
Router+swtich+wap

## VLAN 

It’s used to separate a set of port is an switch. two act like they are different switches thus the name **VLAN**  but in reality they are present in an single switch but their traffic are separated 

Used when you want two separate networks but only have one switch 

This is only done in manageable switches as they are the only one who can receive an ip address 
