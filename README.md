# TTGO-CW-Decoder
An attempt at getting the OZ1JHM CW decoder onto a TTGO ESP32

The [OZ1JHM CW Decoder](http://www.oz1jhm.dk/content/very-simpel-cw-decoder-easy-build) is a Goertzel based decoder for morse code that works very well (not as good as the Mk 1 ear but one of the better ones).
The decoder runs quite effectively on an arduino with a LCD display and has been modified by [Andy, MM0GYG](http://www.saltoun.uk/radio/goertzel.html) to include an on screen tuning aid that is very useful.
This tuning aid also appears on the QCX CW transceiver
Further to this [Jim Harvey](https://github.com/jmharvey1/STM32_CWDecoder) has also produced a variant for the STM32 Blue Pill.

This is just another variant of that. Just for the TTGO ESP32 board with 1.4" screen
