#                                                                     ![hecker](https://github.com/user-attachments/assets/a9919445-ef0e-4691-8d77-8e351f288909)



                                                                                  

Hey there! Meet **Hecker**, an under development frimware for the ESP32 WROOM, with a nod to that sly "Hecker" cat meme. I built this to dig deep into WiFi and Bluetooth Low Energy (BLE) stuff, packing in a bunch of tools for poking around networks and devices. You can control it all through a sharp web interface with a cat vibe or, if you’re feeling fancy, an optional OLED screen.

## Features

- **WiFi Tricks**:
  - **Deauthentication**: Kick devices off WiFi to see how networks handle it.
  - **Scanning**: Check out what WiFi networks are floating around nearby.
  - **Handshake Capture**: Grab WiFi handshakes for some legit security research.
  - **MAC Spoofing**: Pretend to be another device to slip onto a network.
  - **Beacon Spam**: Flood the air with fake WiFi signals, just to mess around.
  - **Evil Portal**: Set up a fake login page to test how people react.
  - **Evil Twin**: Copy a network to dig into its weak spots.

- **Network Device Fun**:
  - **Printer Play**: Send a “Hecker” note to any printer on the network.
  - **Smart TV Tweak**: Try to queue up something on TVs connected to the same WiFi.
  - **Camera Check**: Spot cameras hanging out on the network.

- **BLE Stuff**:
  - **Scanning**: Find Bluetooth devices lurking nearby.
  - **Advertising**: Make the ESP32 show up on Androids and iPhones.
  - **Injection**: Send test data to Bluetooth devices that are open to it.

- **Control Options**:
  - **Web Interface**: Run everything from a browser with a cool cat-themed dashboard.
  - **OLED Display (Optional)**: Use a 0.96-inch screen and three buttons for local control.
