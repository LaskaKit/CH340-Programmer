![CH340 programmer](https://github.com/LaskaKit/CH340-Programmer/blob/main/img/CH340_programmer1.jpg)

# Univerzální programátor s USB-UART převodníkem CH340 určený k nahrávání firmware (nejen) do vývojových stavebnic LaskaKit. 

Hledáteli jednoduchý a levný programátor - USB-UART převodník - který můžete použít s vaší či naší deskou s ESP32, ESP8266 nebo ESP-C3, pak byste neměli přehlédnout právě tento. Tento převodník však můžete použít i pro desky jako je Arduino Mini, Mini Pro a to díky přepínači mezi 5V a 3.3V napájením, který na programátoru máme.

Programátor je založen na známém a odzkoušeném čipu CH340C. Na desce je také přepínač, kterým volíte jak napětí na pinu VCC, tak logickou úroveň sběrnice. Přepínač můžete přepnout buď na 5V či 3.3V. 

![CH340 programmer](https://github.com/LaskaKit/CH340-Programmer/blob/main/img/CH340_programmer2.jpg)

S naším programátorem se také vyhnete neustálemu problému s hledáním vhodného kabelu. Buď použijete kabel s microUSB konektorem nebo USB-C - prostě to, co máte po ruce.

CH340 programátor je pinout stejný jako mají naše vývojové desky programovatelné v Arduino IDE. Můžete jej ale použít i samostatně s vaší deskou či deskou jiného výrobce. 

Programátor má tři indikační LED - první signalizuje připojené napájení, druhá komunikaci na RX a třetí komunikaci na TX lince UART sběrnice. 

Maximální výstupní proud při přepnutí 3.3V výstupu je 500mA, což je dostatečný proud pro napájení nejrůznějších desek od Arduino Uno až po desky s ESP32 či ESP8266.

Kromě UART sběrnice a napájení jsou na konektoru k dispozici i piny DTR a RTS, ty se běžně používají pro přepnutí Wi-Fi a Bluetooth modulů ESP32 a ESP8266 do bootloader módu.

Instalaci ovladačů pro čip CH340 jsem popsali v tomto článku https://blog.laskarduino.cz/instalace-ovladace-prevodniku-usb-na-uart-ch340/ 

Github CH340 programátoru naleznete na https://github.com/LaskaKit/CH340-Programmer

K zakoupení je na naší stránce https://www.laskarduino.cz/laskakit-ch340-programmer-usb-c--microusb--uart/ 
