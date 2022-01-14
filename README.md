Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

# Multi-Channel Data Set
This Repository contains data from a measurement campaign in order to improve the proximity estimation. The basic idea is to improve the estimation by combining WiFi (IEEE 802.11 2.4 GHz and 5 GHz) signals with BLE signals. Parts of these data were collected during a [master thesis](https://github.com/elanfer/msc-thesis), others during regular research. The paper containing results was submitted to a IEEE conference and is currently under review. Measurement setup and details are described in detail in the thesis. A brief description will published in this repository soon.

## Devices
- Raspberry Pi 4b (Pi) (**Receiver** and sender)
- Apple iPhone 6S (iPhone) (Sender)
- OnePlus Nord N10 5G (OnePlus) (Sender)

## Environments
- Office room
- Bus
- Train 
- Outoors in an empty parking lot

## Settings
- Measurement section (Only one device sending at stable distance)
- Scenarios (All three senders active, from different positions/orientations, at stable distance)

## Data fields
distance: distance between sender and receiver in cm
rssiBLE: raw RSSI in dBm for the BLE advertisement
rssi24: raw RSSI in dBm for the IEEE 802.11 2.4GHz probe requests
freq24: Frequency in MHz for the IEEE 802.11 2.4GHz probe requests
rssi5: raw RSSI in dBm for the IEEE 802.11 5Hz probe requests
freq5: Frequency in MHz for the IEEE 802.11 5GHz probe requests
y: Distance classifcation into *very_close*, *close*, and *safe* (in accordance to GAEN proximity estimation)

## Citation 
tbf

## License
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].
