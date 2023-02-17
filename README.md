# Arduino Projesi Grobak.Net

## JWS-namaz vakitleri

NodeMCU veya ESP8266, LED Panel P10, RTC DS3231 ve BUZZER kullanarak namaz vakitleri çizelgesi

### Özellikler

- Büyük Saat
- Namaz vakitleri 5 defa ve Tanbih İmsak
- Alarm Ezan namaz vakitleri ve Tanbih İmsak
- Tarihli
- Sıcaklık
- Iqomah Geri sayım
- Üst sıradaki küçük saat ve alt sıradaki malului Wifi kaydırma metnini güncelle

### Donanım

100% Test Ana Kurulu için Epson TM-T88IV TM-T88IV TM-T88IV TM-T88V Yazıcı yazıcı parçaları. 0
- https://tokopedia.com/elektronmartcom/controller-jws-murottal-quad-multi-panel-wifi-mp3-jam-jadwal-sholat
- https://www.bukalapak.com/p/elektronik/elektronik-lainnya/315l4pa-jual-controller-jws-murottal-quad-multi-panel-wifi-mp3-jam-jadwal-sholat-led-masjid

LED Panel P10
- https://www.tokopedia.com/elektronmartcom/led-display-panel-p10-smd-outdoor-green-hijau
- https://www.bukalapak.com/p/elektronik/komponen-elektronik/2qkxq35-jual-led-display-panel-p10-smd-outdoor-green-hijau


JWS KİTİ
- https://tokopedia.com/elektronmartcom/jws-kit-controller-led-p10-hub12-mp3-murottal-jadwal-sholat-digital
- https://www.bukalapak.com/p/elektronik/media-player-set-top-box/36buedq-jual-jws-kit-controller-led-p10-hub12-mp3-murottal-jadwal-sholat-digital


Sadece PCB
- https://tokopedia.com/elektronmartcom/pcb-jws-nodemcu-board-2-0-elektronmart-led-p10-arduino
- https://www.bukalapak.com/p/elektronik/komponen-elektronik/2aiovn2-jual-pcb-jws-nodemcu-board-2-0-elektronmart-led-p10-arduino



### DMD LED P10 Panelindeki pim

/ DMD P10 / GPIO / NODEMCU | 
| ------- | ---- | ------- |
| A / GPIO16 / D0 |                                                 
| B / GPIO12 / D6 |                                                  
/ CLK / GPIO14 / D5 |                           
/ SCK / GPIO0 / D3 |                           
/ R / GPIO13 / D7 |
/ HAYIR / GPIO15 / D8 |
| GND / GND / GND |

### RTC DS3231 üzerindeki Pın

| DS3231 / NODEMCU |
| ------ | ------- |
/ SCL / D1 (GPIO 5) |
/ SDA / D2 (GPIO 4) |
/ VCC / 3V |
| GND / GND |

### Zil Sesini Aç

/ Zil / NODEMCU |
| ------ | ------- |
| + / RX (GPIO 3) /
/ - /GND |

### Harici Kütüphane
- DMDESP : https://github.com/busel7/DMDESP
- Dua zamanı: https://github.com/asmaklad/Arduino-Prayer-Times
- RTC DS3231 : https://github.com/Makuna/Rtc
- ArduinoJson V6 : https://github.com/bblanchon/ArduinoJson
- F1km_sayısı : https://github.com/wardi1971/F1kM_Hisab

Araçlar : 
- Bitmap ve yazı tipi tasarımı: http://dotmatrixtool.com
- LittleFS Yükleyici: https://github.com/earlephilhower/arduino-esp8266littlefs-plugin/releases

        
### Not : 
- LED P10'a 5V harici Güce ihtiyacınız var.
- Yanıp Sönerken (yükleme programı) pimi geçici olarak zil sesine çıkarın.

> telefon: bonny@grobak.net - www.grobak.net
