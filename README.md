# Dell Latitude E6400
<img src="https://i.imgur.com/pnwi67A.jpeg" width="500">

| Hardware  | |
| ------------- | ------------- |
| CPU  | Intel Core 2 Duo P8700 |
| RAM  | 8GB DDR2 |
| GPU  | NVIDIA Quadro NVS 160M  |
| Network  | Intel® Wi-Fi 6 AX200  |
| Storage  | Samsung SSD 870 EVO 500GB |
| OS  | macOS High Sierra 10.13.6 |
| Screen  | 14.2-inch (1440 x 900) | 
| Bootloader | OpenCore 0.9.8 | 

## Hardware compatibility

#### What works
- GPU acceleration and video codecs
- SSD
- Wi-Fi (itlwm)
- Trackpad (glitchy on some boots)
- Keyboard
- Internal Speakers
- Headphone Output (loud electrical noise from DAC, cannot be fixed in software)
- Internal microphone
- All USB ports
- Brightness (with keyboard brightness controls)
- Battery precentage, charging
- VGA Output
- Shutting Down

#### What does not work
- CPU power management (works on Clover)
- Sleep (lack of CPU PM)
- Restarting (lack of CPU PM)
- Bluetooth (No USB Lanes in mini-PCIe slot)
- DisplayPort (unsure why)

#### Untested
- Bluetooth Audio
- iMessage and iCloud
