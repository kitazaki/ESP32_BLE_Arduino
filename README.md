# ESP32_BLE_Arduino

pBLEScan->setAdvertisedDeviceCallbacks(new MyAdvertisedDeviceCallbacks(), false);  
↓  
pBLEScan->setAdvertisedDeviceCallbacks(new MyAdvertisedDeviceCallbacks(), true);  // duplicate packet

<img src="BLE_Duplicate_Packet.png">
