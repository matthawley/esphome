# Bambu Lab Switch

This device uses an ESP32 board to add additional functionality to your Bambu P1 series printer. It adds the functionality of using a temperature probe to give an near-accurate display of internal chamber temperature as well as controlling a relay switch to turn on/off your bento box.

## Hardware
* [ESP32 Module](https://www.amazon.com/gp/product/B08D5ZD528/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&th=1) - The main controller that is programmed and flashed.
* [DS18B20](https://www.amazon.com/HiLetgo-DS18B20-Temperature-Stainless-Waterproof/dp/B00M1PM55K) - The temperature probe used to report chamber temperature.
* [4.7K Ohm Resistor](https://www.amazon.com/Projects-10EP5124K70-4-7k-Resistors-Pack/dp/B0185FKBG4) - Connected between the DS18B20 Data (Yellow) and Power (Red) wire.
* [IoT Relay](https://www.amazon.com/gp/product/B00WV7GMA2) - Or, if you're more inclined, your own relay switch, which requires more electrical knowledge.
* [Momentary Push Button](https://www.amazon.com/gp/product/B083JWJPW5) - To manually toggle the bento box.
* [Bento Box](https://voxelpla.com/products/bento-box) - Or, you could [3d print](https://www.printables.com/model/272525-bentobox-v20-carbon-filter-for-bambu-lab-x1c-enclo) this yourself if you source all the hardware.
* [26 AWG Wire](https://www.amazon.com/gp/product/B0C9MB4DTY) - Smaller wire needed to fit through the small hole inside the back left of the P1S (along with the Bento Box wire).

## GPIO Pins
