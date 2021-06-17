# Protokoll

## Zeitplan
| Datum | Meilenstein |
| :-----------: | :-----------: |
| 04.03.2021    | Alle können aufs Repo zugreifen |
| 11.03.2021    | Kamera funktioniert|
| 15.04.2021    | OpenCV installiert|
| 29.04.2021    | FaceID funktioniert|
| 06.05.2021    | neue SD-Karte- kompletter Neustart|
| 27.05.2021    | vorläufiger Server aufgesetzt <br> Fehler beim Update: kompletter Neustart <br> OpenCV Packages installiert <br> FaceID funktioniert|
| 13.06.2021    | Server wird nun mit Template Daten aufgesetzt <br> Server funktioniert|
| 17.06.2021    | Python updaten <br>|

## 04.03
- Kamera Setup https://www.youtube.com/watch?v=bpzGN35oaJ4 , https://www.pyimagesearch.com/2015/03/30/accessing-the-raspberry-pi-camera-with-opencv-and-python/
- Kamera Komponenten nachgeschlagen
     - https://www.ulrischa.de/raspberry-noir-ndvi-webcam-teil-1-blaue-folie-und-der-ndvi/
     - https://www.amazon.com/Lens-Adjustment-Tool-Raspberry-Camera/dp/B07BZL49K7
## 15.04
- OpenCV Packages installiert 
     - https://cbrell.de/blog/opencv-mit-dem-raspberry-pi-ein-einstieg/ 
- FaceID erkennt Gesichter
## 06.05
- Fehler: kompletter Neustart des Projektes
## 27.05
- OpenCV Packages installiert 
     - https://cbrell.de/blog/opencv-mit-dem-raspberry-pi-ein-einstieg/ 
     - Verwendete Befehle: sudo raspi-config
     - ![image](https://user-images.githubusercontent.com/71823685/119818208-358fa680-beef-11eb-8d3a-05f9b517bd3f.png)

- Probleme beim starten der Kamera
 ![image](https://user-images.githubusercontent.com/71823685/119817449-4b509c00-beee-11eb-966e-a4aa179f632c.png)
- Kamera mit FaceID funktioniert
     - ![image](https://user-images.githubusercontent.com/71823685/119818435-7b4c6f00-beef-11eb-9711-f4fb3ab20a95.png)
## 11.06
- Probleme bei Gesichtserkennung und bei der Installation von NodeJS
## 13.06
- Server aufgesetzt 
- Lösungen für Probleme werden gesucht


#### SW
- OpenCV: https://opencv.org/
- Java Framework: highChart oder chartJS
- NodeJS: https://nodejs.org/en/download/
- verwendeter python Code: https://edufs.edu.htl-leonding.ac.at/moodle/mod/resource/view.php?id=122356
- NodeJS Installation
     - https://tutorials-raspberrypi.de/raspberry-pi-nodejs-webserver-installieren-gpios-steuern
- NodeJS Deinstallation
     - https://im-coder.com/deinstallieren-sie-nodejs-npm-und-node-vollstaendig-in-ubuntu-14-04.html

#### HW
- Raspberry PI
- Raspberry PI Webcam https://at.rs-online.com/web/p/raspberry-pi-kameras/9132664/
- Raspberry PI IR Cam https://at.rs-online.com/web/p/raspberry-pi-kameras/9132673/

### Server + Code (temporäre Daten)
- Website
- ![Website](https://user-images.githubusercontent.com/77103768/121804790-5cb4da80-cc48-11eb-8ee7-6080edb82af5.png)
- HTML: 
- ![index.html](https://user-images.githubusercontent.com/77103768/121804662-ce405900-cc47-11eb-8dab-9daa5317976a.png)
- serverJS.js:
- ![serverJS.js](https://user-images.githubusercontent.com/77103768/121804680-f039db80-cc47-11eb-9974-14c08cdf074c.png)
- sendJS.js:
- ![sendJS.js](https://user-images.githubusercontent.com/77103768/121804724-10699a80-cc48-11eb-810a-6bc4bb81c38a.png)
