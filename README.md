📡 Arduino Radar Visualization (Python + Arduino)
📌 Opis projekta

Ovaj projekat predstavlja radarski sistem za detekciju prepreka, realizovan pomoću:

Arduino Uno

dodajte ovde ako treba jos nesto?

?

Python aplikacije za vizuelizaciju

Sistem funkcioniše tako što servo motor rotira senzor u opsegu od 0° do 180°, meri udaljenost prepreka i šalje podatke računaru putem serijske komunikacije, gde se oni prikazuju u vidu radarske vizualizacije.

👥 Članovi tima
Ime i prezime	Broj indeksa	Deo projekta
Dimitrije Jovanovic	137/2023	Python aplikacija, vizuelizacija
Ime Prezime	20xx/xxxx	?
Ime Prezime	20xx/xxxx	?

🧠 Podela zadataka
🔧 Hardverski deo (Arduino)

Povezivanje:

Arduino Uno

Ultrazvučni senzor (HC-SR04)

Servo motor

Pisanje Arduino koda:

Upravljanje servo motorom

Očitavanje distance

Slanje podataka u formatu:

ugao,distanca

💻 Softverski deo (Python)

Čitanje podataka sa serijskog porta

Obrada podataka

Prikaz u realnom vremenu

Vizuelizacija u obliku radara (polar plot)

🔌 Povezivanje komponenti
Ultrazvučni senzor (HC-SR04)
Pin senzora	Arduino
VCC	5V
GND	GND
TRIG	D8
ECHO	D7
Servo motor
Servo	Arduino
Signal	D9
VCC	5V
GND	GND
