# Polish Multi-Aspect Signals NewGRF

![Sample image](https://raw.githubusercontent.com/wiki/JGRennison/multi-aspect-signals-grf/sample-image.png)

### Features

* This GRF includes 3-aspect signal graphics (red, yellow, green) for the block signal, PBS and one-way PBS signal types.
* Custom signal styles: shunt, tall shunt, mechanical shunt, banner approach, path with a light strip (cosmetic), left and right side crossing signals (cosmetic), this is enabled by a GRF parameter (default off).
* Two different heights of PBS signal graphics are included. Use the GRF parameter to select which to use, or whether it depends on the available vertical clearance. Short PBS signals requires that block signals are using traditional graphics.

### Requirements

* This GRF requires a non-standard version of OpenTTD which supports the signal graphics and multi-aspect features such as [JGR's patchpack](https://github.com/JGRennison/OpenTTD-patches) v0.43.0 or later.
* Realistic braking must be enabled for multi-aspect signalling to be enabled.
* Custom signal styles require a non-standard version of OpenTTD which supports this feature such as [JGR's patchpack](https://github.com/JGRennison/OpenTTD-patches) v0.48.0 or later.
* Signal height depending on available vertical clearance requires a non-standard version of OpenTTD which supports this feature such as [JGR's patchpack](https://github.com/JGRennison/OpenTTD-patches) v0.53.0 or later.

### Things not included

* This GRF does not include semaphores or any type of pre-signal.

### More information

* This NewGRF is based on [JGRennison]'s [Multi aspect signals grf](https://github.com/JGRennison/multi-aspect-signals-grf)
* For more information on GRF parameters and the different signal types, see the [Wiki](https://github.com/JGRennison/multi-aspect-signals-grf/wiki).

### Development

* Compiling requires a forked verison of NML with additional features from [here](https://github.com/JGRennison/nml).
* For NewGRF development details of the signal graphics features used in this GRF see:
    * [NML specification additions](https://jgrennison.github.io/OpenTTD-patches/newgrf-additions-nml.html).
    * [NewGRF specification additions](https://jgrennison.github.io/OpenTTD-patches/newgrf-additions.html).

### License

* GNU GPL v2

### Credits

* Signal sprites were made by Patrylec
* Coding the NewGRF was made by 
* Special thanks to the OpenTTD Discord server and particularly [JGRennison] for helping us with the Set.
