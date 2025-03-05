# T-Deck-BR
Installing a version of Meshtastic's Fancy UI firmware for the LYLIGO T-Deck

**First of all, dear reader, I want to make it clear that the information shared here and the provided files are authentic and it is not mine Project. I just compiled it. However, this in no way diminishes the value of the project.** I firmly believe that the more people use and engage with [Meshtastic](https://github.com/meshtastic/firmware) and, off course, [device-ui](https://github.com/meshtastic/device-ui), the more it will evolve into a comprehensive platform.  

What I share here is simply my personal experience—just a report of what happened to me. Perhaps someone else is facing the same situation, and this might serve as a possible solution.

---

### **Step-by-Step: Installing Fancy UI Firmware on the T-Deck Plus S3**

1. **Initial Attempt with Precompiled Version**  

   - The only precompiled version available was **2.5.3**.  
   - Followed the standard installation steps, but the device wouldn't boot properly.  

2. **Compiling the Latest Version**  

   - Downloaded the source code for **version 2.5.22**.  
   - Compiled the firmware from source.  
   - Uploaded it to the **T-Deck** using [esp.huhn.me](https://esp.huhn.me), placing the files in the correct memory addresses.  
   - Despite this, the device still failed to boot.  

3. **Switching to M5Stick-Launcher**  

   - Installed **M5Stick-Launcher** via [bmorcelli.github.io/M5Stick-Launcher](https://bmorcelli.github.io/M5Stick-Launcher/).  
   - Selected only the **T-Deck** option. And wait to process finish.  

4. **Enabling Wi-Fi and Uploading the Firmware**  

   - Enabled and connected to **Wi-Fi** on the **T-Deck** via the **WUI** in the **Launcher**.  
   - Accessed the device’s web interface from a computer. The IP will be displayed along with the credentials.  
   - Open **Google Chrome**, enter the **T-Deck's IP address**, and once the page loads, select the **OTA update** option.  
   - Choose the file **firmware.bin**, wait for the upload to complete, then click **"Start Update"** and wait for the process to finish.  
   - After that, select **firmware.factory.bin**, upload it, and wait for the process to complete.  

5. **Finalizing Installation**  

   - Once the upload is finished, click the **Reboot** button.  
   - The device should restart successfully with **Meshtastic Fancy UI 2.5.22** fully installed.  
---

## Screenshots

### T-Deck Running Meshtastic Fancy UI

![T-Deck boot Screen](https://github.com/psdurco/T-Deck-BR/blob/main/imgs/boot.jpeg?raw=true)
![T-Deck Home Screen](https://github.com/psdurco/T-Deck-BR/blob/main/imgs/home.jpeg?raw=true)
![T-Deck Mesh Detector Screen](https://github.com/psdurco/T-Deck-BR/blob/main/imgs/mesh-detector.jpeg?raw=true)