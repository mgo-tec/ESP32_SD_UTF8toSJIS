# ESP32_SD_UTF8toSJIS

これは Arduino core for the ESP32 ( ESP-WROOM-32 )の Arduino IDE ライブラリです。  
Version 1.21 
  
SPI接続 ( VSPI接続 )の micro SD カードから読み込むためのものです。  
UTF8 to Shift_JIS 変換テーブルファイル "Utf8Sjis.tbl" を予めSDカードにコピーしておく必要があります。  
UTF-8コードのString文字列をShift_JIS文字列コードに変換できます。  
変換テーブルファイルURL--> https://github.com/mgo-tec/UTF8_to_Shift_JIS  
  
JIS第一水準、第二水準、１３区、半角カナが変換可能  
  
【更新履歴】  
(1.21)  
2017/8/1 以降、Arduino core for ESP32 が大幅アップデートされたことに伴い、Serial.beginクラスが２重使用できなくなりました。  
よって、SD_Shinonome_Init3F関数などの Serial.begin関数をコメントアウトしました。  
  
(1.2)  
細かいところを少々修正。  
  
(1.1)  
ファイルハンドル名 _UtoS を外部のソースから参照できるようにしました。  
サンプルスケッチを参照してください。  
同時に開くファイル数を節約できます。  
  
(1.0)  
ESP32 用リリース  
  
参照ブログ https://www.mgo-tec.com  
  
The MIT license  
Copyright (c) 2017 Mgo-tec  