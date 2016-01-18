# led-stripe-py-esp8266
Mit dieser kleinen Python-Library sollte es erleichtet werden, die LED-Stripe (https://wiki.c3d2.de/LED-Stripe) im HQ des C3D2 zu programmieren. Ich habe jedoch eine esp8266-Variante dieses Stripes gebaut, welche auch im Code gewisse Anpassungen (z.B. RGB statt BRG für ws2812b). So läuft dieser Code nun auch mit https://defendtheplanet.net/2016/01/16/controlling-ws2812b-with-an-esp8266-by-open-pixel-control-protocol/

Den Code für den ESP8266 gibt es hier: https://github.com/PaulPetring/esp8266-ws2812b-open-pixel-control.

Bitte nicht vergessen, Stripe und Controller verwenden bei voller Leuchtkraft verschiedene Spannungen. Der Datenkanal braucht allerdings nicht geshiftet werden und funktioniert auch so.

Danke an den usprünglichen Autor Elias Gürlich
 





