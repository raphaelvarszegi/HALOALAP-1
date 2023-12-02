**1. Szállítási Réteg Helye és Feladatai:**

* **Réteg Helye:**
  - Az OSI modell szerint a szállítási réteg a negyedik réteg, amely az adatok továbbítását és szállítását biztosítja a forrás és a cél között.

* **Feladatok:**
  - Az adatok megbontása kisebb egységekre, az átviteli hibaellenőrzés, a sávszélesség-vezérlés és az adatfolyam irányítása.

**2. TCP Protokoll Működése:**

* **Port Fogalma:**
  - Az azonosító, amely az adott alkalmazás vagy szolgáltatás számára rendelt kaput jelenti a szállítási rétegen belül.

* **TCP Fejléc:**
  - Tartalmazza az adatok sorszámát, a kimenő és bejövő ablakokat, ellenőrző összeget, illetve egyéb vezérlő információkat.

* **Összeköttetés Létesítése és Bontása:**
  - **Létesítés:** Két eszköz közötti megbízható kapcsolat kialakítása, ahol az eszközök megerősítik egymásnak a kapcsolatfelvételt.
  - **Bontás:** Az összeköttetés biztonságos lezárása a kapcsolat végén.

* **Átviteli Politika:**
  - Megbízható, sávszélesség-orientált kommunikációt biztosít, ahol a TCP felelős az adatok megbontásáért, sorrendezéséért és újraküldéséért.

* **Torlódáskezelés:**
  - Az eszközök közötti átvitel sebességét és a kapacitását figyelemmel kíséri, és szükség esetén visszatartja vagy korlátozza az adatok küldését a torlódások elkerülése érdekében.

**3. UDP Protokoll:**

* **Definíció:**
  - Az User Datagram Protocol egy könnyű sávszélesség-orientált protokoll, ami kevés ellenőrzést és kevés hibakezelést kínál.

* **Szerepe:**
  - Az UDP a gyors adatátvitelt preferálja a megbízhatóság előtt, például időkritikus alkalmazásokban.

**4. Néhány "Közismert Port" Száma:**

* **HTTP (HyperText Transfer Protocol):** Port 80
* **HTTPS (HTTP Secure):** Port 443
* **FTP (File Transfer Protocol):** Port 21
* **SMTP (Simple Mail Transfer Protocol):** Port 25
* **DNS (Domain Name System):** Port 53
* **SSH (Secure Shell):** Port 22
* **Telnet:** Port 23
* **POP3 (Post Office Protocol version 3):** Port 110
* **IMAP (Internet Message Access Protocol):** Port 143
* **SNMP (Simple Network Management Protocol):** Port 161
