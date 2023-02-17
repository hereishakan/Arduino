# Arduino Projesi Grobak.Net

## JWS - Jadwal Waktu Sholat

NodeMCU veya ESP8266, LED Panel P10, RTC DS3231 ve BUZZER'ı etkinleştirin

### FITUR

- Reçel Beşar
- Jadwal Sholat 5 Waktu dan Tanbih Imsak
- Alarm Adzan Waktu Solat dan Tanbih Imsak
- Tangal
- suhu
- Hitung Mundur Iqomah
- Jam Kecil barış ataları ve Update scroll teks malului Wifi pada baris bawah

### Donanım

Denetleyici JWS FullSet PCB ElektronMart JWSNodeMCUP10 Board v2.0
- https://tokopedia.com/elektronmartcom/controller-jws-murottal-quad-multi-panel-wifi-mp3-jam-jadwal-sholat
- https://www.bukalapak.com/p/elektronik/elektronik-lainnya/315l4pa-jual-controller-jws-murottal-quad-multi-panel-wifi-mp3-jam-jadwal-sholat-led-masjid

LED Paneli P10
- https://www.tokopedia.com/elektronmartcom/led-display-panel-p10-smd-outdoor-green-hijau
- https://www.bukalapak.com/p/elektronik/komponen-elektronik/2qkxq35-jual-led-display-panel-p10-smd-outdoor-green-hijau


JWS SETİ
- https://tokopedia.com/elektronmartcom/jws-kit-controller-led-p10-hub12-mp3-murottal-jadwal-sholat-digital
- https://www.bukalapak.com/p/elektronik/media-player-set-top-box/36buedq-jual-jws-kit-controller-led-p10-hub12-mp3-murottal-jadwal-sholat-digital


Yalnızca PCB
- https://tokopedia.com/elektronmartcom/pcb-jws-nodemcu-board-2-0-elektronmart-led-p10-arduino
- https://www.bukalapak.com/p/elektronik/komponen-elektronik/2aiovn2-jual-pcb-jws-nodemcu-board-2-0-elektronmart-led-p10-arduino



### DMD LED P10 Panelindeki Pin

| DMD P10 | GPIO | NODEMCU |
| ------- | ---- | ------- |
| bir | GPIO16 | D0 |
| B | GPIO12 | D6 |
| CLK | GPIO14 | D5 |
| SCK | GPIO0 | D3 |
| R | GPIO13 | D7 |
| HAYIR | GPIO15 | D8 |
| GND | GND | GND |

### RTC DS3231'deki Pin

| DS3231 | NODEMCU |
| ------ | ------- |
| SCL | D1 (GPIO 5) |
| SDA | D2 (GPIO 4) |
| VCC | 3V |
| GND | GND |

### Buzzer'daki Pin

| Zil | NODEMCU |
| ------ | ------- |
| + | RX (GPIO 3) |
| - | GND |

### Eksternal Kitaplık
- DMDESP : https://github.com/busel7/DMDESP
- Namaz Saati : https://github.com/asmaklad/Arduino-Prayer-Times
- RTC DS3231 : https://github.com/Makuna/Rtc
- ArduinoJson V6 : https://github.com/bblanchon/ArduinoJson
- F1kM_Hisab : https://github.com/wardi1971/F1kM_Hisab

Aletler :
- Bitmap ve yazı tipini belirleyin: http://dotmatrixtool.com
- LittleFS Yükleyici: https://github.com/earlephilhower/arduino-esp8266littlefs-plugin/releases

        
### Katatan :
- LED P10 için Perlu Power Eksternal 5V.
- Saat Yanıp Sönme (yükleme programı) zil sesini sabitlemek için kullanılır.

> e-posta: bonny@grobak.net - www.grobak.net
