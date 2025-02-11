# dbus-shelly-3em-smartmeter
Integrate Shelly 3EM and Shelly Pro 3EM smart meter into [Victron Energies Venus OS](https://github.com/victronenergy/venus)

There is an additional parameter in the config.ini
You have to define in [ONPREMISE]
- ShellyType=ShellyProEM for the Shelly Pro EM3 which needs digest authentication
- ShellyType=Shelly3EM for the old Shelly 3EM implemented by fabian-lauer

The other installation parameters stay the same.
Please refer to: https://github.com/fabian-lauer/dbus-shelly-3em-smartmeter/blob/main/README.md

If you do not have git installed do the following.
- Install the fabian-lauer version.
- Chnage directoy to /data/dbus-shelly-3em-smartmeter
  cd /data/dbus-shelly-3em-smartmeter
- Delete the old py scrip:
  rm dbus-shelly-3em-smartmeter.py
- Download this py script
  wget https://raw.githubusercontent.com/staub79/dbus-shelly-3em-smartmeter/main/dbus-shelly-3em-smartmeter.py
- Delete the old config.ini
  rm config.ini
- Download this config.ini
  wget https://raw.githubusercontent.com/staub79/dbus-shelly-3em-smartmeter/main/config.ini
- Update the information in config.ini for your setup
  nano config.ini

