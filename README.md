# 📡 Arduino Radar – Vizuelizacija u Pythonu

## 📖 Opis projekta
Ovaj projekat prikazuje rad jednostavnog radarskog sistema baziranog na Arduino platformi.
Sistem koristi ultrazvučni senzor i servo motor za skeniranje okoline, dok se rezultati prikazuju u realnom vremenu pomoću Python aplikacije.

## 🧩 Funkcionalnosti
Rotacija senzora pomoću servo motora
Merenje distance pomoću ultrazvučnog senzora
Slanje podataka preko serijske komunikacije
Vizuelizacija u obliku radara (Python)

## 🧠 Podela zadataka

### 🔧 Hardverski deo (Arduino)
Povezivanje senzora i servo motora
Arduino kod za upravljanje uređajima
Slanje podataka u formatu: ugao,distanca

### 💻 Softverski deo (Python)
Čitanje serijskih podataka
Obrada i prikaz u realnom vremenu
Vizuelizacija pomoću matplotlib biblioteke

## 👥 Članovi tima
| Ime i prezime | Broj indeksa | Uloga u projektu |
|--------------|--------------|------------------|
| Dimitrije Jovanović  | RN 137/2023    | Python aplikacija i vizuelizacija |
| Filip Matijević  | RN 53/2019    | xxxxx |
| Jelisaveta Tepavčević  | RN 7/2023    | xxxxx |

## 🔌 Korišćene komponente
Arduino Uno
Ultrazvučni senzor (HC-SR04)
Servo motor
USB kabl
Python 3

## ▶ Pokretanje projekta
1. Povezati Arduino sa računarom  
2. Uploadovati kod iz `arduino_radar.ino`  
3. Proveriti serijski port u Arduino IDE  
4. Pokrenuti `radar_serial.py`  
5. Posmatrati radar vizuelizaciju  

## 📁 Struktura projekta
arduino_radar/
│
├── arduino_radar/
│   └── arduino_radar.ino
│
├── radar_serial.py
├── radar_sim.py
└── README.md
