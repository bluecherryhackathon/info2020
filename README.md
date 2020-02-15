
# BlueCherry Hackathon 2020
## Opdracht

Elke groep heeft dezelfde ESP32 azure IoT kit. Jullie opdracht is een een IoT (Internet-of-Things) product te ontwikkelen. Het product bestaat dus uit een stuk software voor de hardware module en een software component welke op jullie computer draait. 

Jullie mogen vrij kiezen welke ontwikkeltools jullie gebruiken voor deze opdracht. Op het einde van de hackathon presenteren jullie het product voor de jury.

Voorbeelden:
 - Een IoT connected wekkerradio
 - Een slimme kattenbak

Creatief en inventief zijn is dus key om te slagen voor deze challenge. De vereisten om te gebruiken zijn:
  - Het MQTT protocol
  - De voorziene hardware (je mag wel kiezen welke sensoren en in/outputs je gebruikt)

## Nuttige informatie
### MQTT server
Wij zullen voor de hackathon de HiveMQ MQTT broker gebruiken welke beschikbaar is op volgend adres:
```
MQTT over TCP (voor de hardware)
Host: broker.hivemq.com  
Port: 1883  

MQTT over websockets:
URL: ws://broker.hivemq.com/mqtt:8000
```

### Hardware
Elke groep kreeg een ESP32 Azure IoT kit, dit bordje is voorzien van verschillende inputs en outputs. Zo zijn er meerdere sensoren, een scherm, een drukknop, LED lampjes, een buzzer, .... aanwezig. Alle gegevens over dit bordje vind je in de datasheet welke ook in deze repository zit.

### Software
Jullie zijn vrij om gelijk welke software te gebruiken die jullie graag willen. Wij hebben alvast enkele voorbeelden geplaatst in onze 'examples repository'. We gaan er van uit dat jullie de hardware met behulop van de Arduino IDE zullen programmeren. Deze moet je eerst installeren samen met de ESP32 Arduino toolchain.

[https://www.arduino.cc/en/main/software](https://l.messenger.com/l.php?u=https%3A%2F%2Fwww.arduino.cc%2Fen%2Fmain%2Fsoftware&h=AT25aBfW1z3Xke9tRJEf-5mU72NGCc5Ch7y77SkWSVs4JpwWPwSZb8sGzx031rHfFzQ5mT4FAA25hZyZw0VeOLK7RC5BgjyGa5odZf0NYIO0MJ68vKIxXZJXJ9Q2RO6To7Jz5g)  
  
Install ESP32 board support into your Arduino IDE.  
* Start Arduino and open Preferences window.  
* Enter esp32 package URL [https://dl.espressif.com/dl/package_esp32_index.json](https://dl.espressif.com/dl/package_esp32_index.json) into Additional Board Manager URLs field.
* Open Boards Manager from Tools > Board menu and install esp32 platform.  
* Select your esp32 board from Tools > Board menu after installation
* Selecteer als ontwikkelboard de ESP32 Wrover en als upload speed 921600 kiezen.

### Voor OSX moet je speciale driver software installeren
[https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers](https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers)

