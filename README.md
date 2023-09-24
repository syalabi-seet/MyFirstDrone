# My First Drone

## Parts list
- F330 Frame
- Cube Orange with Cubepilot ADS-B carrier board
- 2208/17 1100kV motors
- 8045 propellers
- 4S 2250mAh LiPo battery
- 2S-3S 20A ESC
- Raspberry Pi 4 Model B 4GB RAM
- Here3 GPS
- RadioMaster Pocket RX
- RadioMaster Nano 2.4GHZ ELRS Module

## Setup
Setting up pyrealsense2 on Raspberry Pi OS 32-bit
```
# In local machine
scp setup.sh pi@raspberrypi.local:.
ssh pi@raspberrypi.local

# In remote machine
sh setup.sh
```

## Calculate Battery life
Battery lifespan $= \frac{Battery\ Capacity}{Rated\ Current}$