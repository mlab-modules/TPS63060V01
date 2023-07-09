# MLAB TPS63060V01A Module

The MLAB TPS63060V01A module is based on [TPS63060](https://www.ti.com/lit/ds/symlink/tps63060.pdf?HQS=TI-null-null-digikeymode-df-pf-null-wwe&ts=1614085886440) integrated circuit from Texas Instruments. This circuit is a synchronous step-down (buck-boost) converter, capable of regulating the output voltage whether the input voltage is either higher or lower than the output voltage.

![TPS63060V01A](/doc/img/TPS63060V01A_top_small.jpg)

### TPS63060
The TPS63060 is a highly efficient, fully integrated, synchronous buck-boost converter designed for a wide range of applications. This circuit has an internal switching transistor, which allows it to achieve high efficiency at low loads.

The TPS63060 operates in automatic PFM/PWM switching mode, switching between PFM (Pulse Frequency Modulation) mode at low loads for efficiency optimization, and PWM (Pulse Width Modulation) mode at higher loads for better voltage regulation.


### Basic Parameters:
- Input voltage: 2.5 V to 12 V
- Output voltage: 2.5 V to 8 V
- Maximum current for internal transistor: 2 A
- Output voltage selectable at 3.3 V or 5 V (by jumper placement)
- Pin for converter activation: EN
- Pin for power saving mode and synchronization: PS/SYNC

Users can choose between an output voltage of 3.3 V or 5 V using a jumper setting.

A significant feature of the module is the ability to activate and deactivate the converter via the EN (enable input) pin. This is especially useful in applications where power is supplied by batteries, and there is a need to protect them from deep discharge.

A unique feature of the module is also the presence of the PS/SYNC pin, labeled as SN. This allows the power saving mode of the converter to be activated if the current draw is less than 100 mA. This pin can also be used to synchronize the converter with an external clock signal.


## Possible Applications
Due to its range of input and output voltages and the ability to regulate, this module is suitable for various applications. It can be used to power low voltage devices from higher voltage batteries or vice versa. Its versatility makes it suitable for a wide range of devices from mobile devices to IoT applications to industrial systems. The power saving mode and the ability to activate/deactivate the converter also support its use in devices where power consumption efficiency is important.


For more detailed information on the functionality of the TPS63060 circuit, we recommend studying its [technical datasheet](https://www.ti.com/lit/ds/symlink/tps63060.pdf?HQS=TI-null-null-digikeymode-df-pf-null-wwe&ts=1614085886440). If you have any further questions, feel free to contact us via email or [Github discuss page](https://github.com/orgs/MLAB-project/discussions) for more information and resources.
