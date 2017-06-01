# This is the Arduino IDE & SD card library using the UTF8_to_Shift_JIS conversion table for the ESP8266.

これは Arduino core for the ESP32 ( ESP-WROOM-32 )の Arduino IDE ライブラリです。  
Version 1.0  
  
SPI接続 ( VSPI接続 )の micro SD カードから読み込むためのものです。  
UTF8 to Shift_JIS 変換テーブルファイル "Utf8Sjis.tbl" を予めSDカードにコピーしておく必要があります。  
UTF-8コードのString文字列をShift_JIS文字列コードに変換できます。  
変換テーブルファイルURL--> https://github.com/mgo-tec/UTF8_to_Shift_JIS  
  
JIS第一水準、第二水準、１３区、半角カナが変換可能  
  
【更新履歴】  
(1.0)  
ESP32 用リリース  
  
参照ブログ https://www.mgo-tec.com  
  
The MIT license  
Copyright (c) 2017 Mgo-tec  