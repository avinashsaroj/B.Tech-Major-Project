# B.Tech-Major-Project
Smart energy Meter
# Introduction
Internet of Things has been a vast field for
inventions since it came into the world.
The most important part of this technology
is the ability to control electrical and
mechanical products without physically
even handling them. We just need a
wireless connection and that’s all.
The main objective of this project is to
automate the Energy Meters so that they
not only keep record of the energy being
used but also deliver the information about
the units used and the amount generated to
the customer
## Methodology

Microcontroller AT89S52 is the heart of
the system. It is used to control the relay
so as to enable the switching of the load .it
also supplies the power to the GSM
module so as to make a wireless
connection. It is also accepts the
commands from the push buttons so that
we can send the details to the user and we
can also we can increase the time period
for which billing is to be done

A 2X16 LCD has been provided so as to
monitor the readings and the usage of the
energy. Reading along with the number of
days and the amount generated is displayed on the display. The brightness of
the display can also be adjusted.


Optocoupler has been provided into the
system so as to avoid the failure of the
system due to overloading or due to the
short circuit. Isolation transformer is not
used as it adds unnecessary input
inductance to the system.
For sharing of the details 2 SIM cards are
used where one is used into the GSM
Module itself so that the details could be
sent and the other is used by the user to
read the message

## Process Description

A typical analog type energy meter is used
that operates on 230V 6A and the meter
constant of the energy meter is around
2300. Since the meter constant is very high
so we have used the microcontroller so the
it counts the number of blinks that the unit
LED makes and operate accordingly. In
order to smoothen the process and get the
reading as per the users choice we
programmed the controller to display 1unit
for every blink of the LED.


The supply from mains is given to the
meter and the output from the meter is
given to the power supply to get a constant
DC supply for the microcontroller and the
display. And the output from the meter is
also given to the relay so as to control the
on-off condition of the load
