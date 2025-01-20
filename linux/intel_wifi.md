If your WiFi is slow when using Bluetooth, try adding the following to /etc/modprobe.d/iwlwifi.conf and reboot:

options iwlwifi bt_coex_active=0 swcrypto=1 11n_disable=8
