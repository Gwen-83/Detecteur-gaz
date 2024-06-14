# Detecteur-gaz
Projet détecteur de fuite de gaz dans un domicile

Ce projet d'étude a pour but de développer un détecteur de fuite de gaz dans un domicile.

Compatibilités du programme:
- Arduino uno (support de développement)
- Arduino Mega
- Arduino Leonardo
Sur Arduino Nano et Micro, il faudra enlever des capteurs et modifier certaines lignes de codes.

Afin d'utiliser le détecteur, il faut télécharger les bibliothèques suivantes:
- https://github.com/Seeed-Studio/Grove_LCD_RGB_Backlight
- https://github.com/labay11/MQ-2-sensor-library
- https://www.arduino.cc/reference/en/libraries/sparkfun-sgp30-arduino-library/ (version 1.0.5)
- https://github.com/Seeed-Studio/Grove_Air_quality_Sensor
- Servo.h (directement sur IDE Arduino)
- Wire.h (directement sur IDE Arduino)
- SoftwareSerial.h (directement sur IDE Arduino)

Ce détecteur est conçu pour une surveillance complète des conditions de l’air intérieur mais n'est pas conçu pour être une alerte fiable.
Il réagit à un large éventail de gaz nocifs tels que le monoxyde de carbone, le dioxyde de carbone, les TVOC, le butane, le méthane, le propane et les fumées de cuisson.
En raison du mécanisme de mesure, ce détecteur ne peut pas produire de données spécifiques pour décrire quantitativement les concentrations des gaz cibles.
Mais il reste suffisamment compétent pour être utilisé dans des applications qui nécessitent uniquement des résultats qualitatifs.

Ce projet a été fait par Bruno Anaïs, Drouet Gwénaël, Hommage Maléna.
