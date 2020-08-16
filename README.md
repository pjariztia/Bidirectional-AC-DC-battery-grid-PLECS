# Bidirectional-AC-DC-battery-grid-PLECS

## Abstract
In recent years on the electric market has been in constant changes and one of
the main ones is the increasing of unconventional renewable energy (ERNC). ERNC has
changed radically the behavior in the electric market due to the low marginal cost of producing
energy that in many cases like solar or wind the marginal cost it is almost negligible in
compare to conventional energy source. The low marginal cost makes the prices in the system
fluctuate with a great amplitude during the day and this variations on the price makes a great
opportunity business: energy storage.

This project consists of the design on a bidirectional power system that allow to charge a
battery when the energy price is low and then discharge the battery selling that storage energy
to the market when the price is high. This opportunity makes the owner of the system to
be capable of saving money on the electric bill or even make it profitable if the system it is
large-scale, efficient and connected to electric bar that has enough price fluctuation.

## Typical Aplications
* Energy Storage and injection to grid in mid to large Scale.
* Electric Cars charger and convenient energy injection pool.

## Structure
* Consist on a single phase grid 220V conect with a LCL filter to a Full-Bridge inverter syncronice with PLL technique and VOC. Then, the DC-Link 400V is connected to a Dual Active Bridge (DAB) with a HF Transformer to 12V battery. All parameters are editable to a particular application.

## notes
* The file you need is [IDB_main](https://github.com/pjariztia/Bidirectional-AC-DC-battery-grid-PLECS/blob/master/IDB_main_V1.plecs)
* Is not neccesary the "bloques PLECS" folder. There are some custom blocks for implementations.

## Implementation
PLECS or simulink can easily export C code trough to CodeComposer or directly with PLECS software. I recommend implementation with TI C2000. More info : [TI C2000](https://youtu.be/OOQp85FsogM)

## Requirements
This file is in [PLECS](https://www.plexim.com/home) software standalone or blockset simulink. Also can be easily implemented on simulink.

## CONTRIBUTING
See [CONTRIBUTING.md](https://github.com/papercups-io/papercups/blob/master/CONTRIBUTING.md)

Enjoy! pjariztia@uc.cl
