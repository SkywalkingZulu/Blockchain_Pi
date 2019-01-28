# Blockchain_Pi
Seting up Raspberry Pi with Blockchain connection

## Hardware setup
```
To set up the hardware, first of all, you have to buy some components. These components can be changed, if you want to research other values, e.g., light emission or distances of objects. In our case, we use the following components. You can find them around the internet. 
Hardware components and prices
- Raspberry Pi 3: 30 €
- Case: 10 €
- GPIO Breakout and Wires (Male-Male, Male-Female): 8 €
- Sensor SW-420: 1 €
- Sensor WCS1800: 7 €
- Sensor DHT11: 5 €
- DC Engine (optional): 5 €
- Battery pack (optional): 5 €
Total 71 €

If done, all components must be connected. Because of the many wires, it is the best to use a breakout board, e.g., a general-purpose input/output (GPIO) board. The GPIO layout incl. The layout is in the “Wireing” folder. 
You can see also a DC engine and a battery pack. These components are just for testing the current, vibration and temperature live. You can skip this if you want to use the model, e.g., just to measure environmental temperature and humidity.
After connecting everything, the raspberry can now be connected to power. All sensor lights/LEDs should be on. The LED from the vibration sensor is blinking, if there is some vibration.
```

## Software setup
The package is needed for running the **API**

**Mysql**

```
pip install mysqlclient

```

Install on the used version of python. For Python3
use:
```text
pip3 install mysqlclient
```

To run the server use

```
python API.py
python Update.py
```



