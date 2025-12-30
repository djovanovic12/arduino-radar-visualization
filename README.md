# Arduino Radar – Vizuelizacija u Pythonu

## Opis projekta
Ovaj projekat prikazuje rad jednostavnog radarskog sistema baziranog na Arduino platformi.
Sistem koristi ultrazvučni senzor i servo motor za skeniranje okoline, dok se rezultati prikazuju u realnom vremenu pomoću Python aplikacije.

## Funkcionalnosti
Rotacija senzora pomoću servo motora
Merenje distance pomoću ultrazvučnog senzora
Slanje podataka preko serijske komunikacije
Vizuelizacija u obliku radara (Python)

## Podela zadataka

### Hardverski deo (Arduino)
Povezivanje senzora i servo motora
Arduino kod za upravljanje uređajima
Slanje podataka u formatu: ugao,distanca

### Softverski deo (Python)
Čitanje serijskih podataka
Obrada i prikaz u realnom vremenu
Vizuelizacija pomoću matplotlib biblioteke

## Članovi tima
| Ime i prezime | Broj indeksa | Uloga u projektu |
|--------------|--------------|------------------|
| Dimitrije Jovanović  | RN 137/2023    | Python aplikacija i vizuelizacija |
| Filip Matijević  | RN 53/2019    | Istraživanje i adaptiranje Arduina za Python |
| Jelisaveta Tepavčević  | RN 7/2023    | Sklapanje Arduina i povezivanje senzora |

## Korišćene komponente
Arduino Uno
Ultrazvučni senzor (HC-SR04)
Servo motor
USB kabl
Python 3

## Pokretanje projekta
1. Povezati Arduino sa računarom  
2. Uploadovati kod iz `arduino_radar.ino`  
3. Proveriti serijski port u Arduino IDE  
4. Pokrenuti `radar_serial.py`  
5. Posmatrati radar vizuelizaciju  

## 🎥 Demonstracija rada sistema
- [Slika robota](https://drive.google.com/file/d/1MraulsgjDurmTQOjdV4mJprrjSNbUSZI/view?usp=sharing)

- [Video 1](https://drive.google.com/file/d/14OXwk00mVM_XMqj0nrh-VkUtTGmzQbUU/view?usp=sharing)
- [Video 2](https://drive.google.com/file/d/1OXna64JG_uhGVJ53yESJyuLX5oAypa4j/view?usp=sharing)
- [Video 3](https://drive.google.com/file/d/11c58CotUJq63cRjXeROMKPzh5b8_gLaZ/view?usp=sharing)
