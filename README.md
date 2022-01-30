# unoffical-openlara-oculus-quest2-airlink-test
Almost 100% of the code comes from the amazing project: https://github.com/XProger/OpenLara

This unofficial project is some very subtle mods to openlara code to make it more palatable to use with oculus quest 2 hardware using air link utility.
I just want to add a few twiddly bits to make it work a bit more nicely on the quest 2 in airlink

Notes:
The intention is to run the pc version of openlara and access it on an oculus over airlink. The pc mouse x,y should control look controls this is intended to come from the head tracker in the oculus.

The project is intended to be compiled using visual studio 2017, you will need sdk 10.0.22000.0 and will need to somehow link files KHR/khrplatform.h, and also GL/glext.h as they are not part of this sdk
