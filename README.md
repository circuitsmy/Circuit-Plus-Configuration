## CIRCUITS PLUS :  ESP32 – CONFIGURATION

For your information, the Circuits Plus board has embedded ESP32 chips which are called System on Chip (SoC) that enable the board to connect to the Wi-Fi and Bluetooth. So, before we start using the ESP32 mode, we need to install the ESP32 Package Board.

  ![circuit plus](https://user-images.githubusercontent.com/60383798/109613628-61a7bf80-7b6c-11eb-9412-456e704d92fe.png)


1. Install the ESP32 library.  *Go to File-> Preferences*

![preference](https://user-images.githubusercontent.com/60383798/109612718-1e991c80-7b6b-11eb-9595-ad0fad73a013.png)

2. Enter https://dl.espressif.com/dl/package_esp32_index.json into the “Additional Board Manager URLs” field as shown in the figure below. Then, click the “OK” button:

![setup](https://user-images.githubusercontent.com/60383798/109612768-31abec80-7b6b-11eb-96c9-58678d34d3e0.png)

3. Install the ESP32 library. *Go to Tools -> Manage Library*

4. Arduino’s Library Manager will appear, then type “ ESP32 ” in the provided search space.

![lib](https://user-images.githubusercontent.com/60383798/109612871-51431500-7b6b-11eb-941b-b5241723a265.png)

5. Install the ESP32 library

6. Check the installation, open the Boards Manager. *Go to Tools -> Board -> Boards Manager ->  ESP32 Arduino -> ESP32 Dev Module* 

![board](https://user-images.githubusercontent.com/60383798/109612902-6029c780-7b6b-11eb-91d5-e755e3943628.png)

Installation is successful if you manage to found the  board.

7. Connect the Circuits IO board to your PC. Make sure that you have set switch mode to ESP32 first.

8. Next we have to configure the port for the ESP32. *Go to Tools -> Port*

9. Select the Port (if you don’t see the COM Port in your Arduino IDE, you need to install the CH34X Driver.

![ports](https://user-images.githubusercontent.com/60383798/109613007-8bacb200-7b6b-11eb-9458-298ca83a23d7.png)

Install CH34X from here : 

10. If you can see the available port then you have finished the ESP32 configuration. Next part we will test the connection of ESP32 with Wi-Fi.

![com](https://user-images.githubusercontent.com/60383798/109613113-af6ff800-7b6b-11eb-9674-b0f4bedda0cf.png)



