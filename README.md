# Breadboarding-RGB-LED-for-4V-and-5V

## The target

The target is to get a module for bread breadboarding to use a RGB LED for 4,2 and 5V.
Why 4,2V and not 4V? 4,2V is the end-of-charge voltage of a li ion a battery pack.

## The Hardware

The RGB is a [LL-509RGBC2E-006](https://github.com/InTheCar/Breadboarding-RGB-Led-for-4V-and-5V/blob/main/Data%20Sheets/LL-509RGBC2E-006.pdf). The used resistors are 0,6W resistors.
- 1x RGB LED LL-509RGBC2E-006
- 1x PBA
- 2x resistor 56 Ohm
- 1x resistor 149 Ohm

## Calculation of the resistors

![5V resistor calculation](https://github.com/InTheCar/Breadboarding-RGB-Led-for-4V-and-5V/blob/main/used%20pictures/calculation%20for%205V.png "5V calculation")
For 5V I found some resistors in my box:

For the LED green and blue -> 56 Ohm




![4,2V resistor calculation](https://github.com/InTheCar/Breadboarding-RGB-Led-for-4V-and-5V/blob/main/used%20pictures/calculation%20for%204.2V.png "4,2V calculation")
Here it's a little bit complecated. The voltage of the  battery pack will go down. We have to use resistos which are small as possible.

For the LED green and blue -> 10 Ohm

For the LED red -> 110 Ohm

## The circuit

