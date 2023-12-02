**1. Autonóm Hálózatok:**

* **Definíció:**
  - Olyan hálózati területek, amelyek önállóan kezelik az IP címzéseket és belső forgalmukat.

* **Szerep:**
  - Az autonóm hálózatok az önálló irányítást és konfigurációt teszik lehetővé, gyakran egy saját belső forgalomirányítási protokoll használatával.

**2. Belső és Külső Átjáró Protokoll (IGP/EGP) Fogalma:**

* **IGP (Interior Gateway Protocol):**
  - Az autonóm hálózatok belső forgalomirányításához használt protokoll, például az OSPF vagy RIP.

* **EGP (Exterior Gateway Protocol):**
  - Az autonóm hálózatok közötti forgalomirányításhoz használt protokoll, például a BGP.

**3. Forgalomirányítás az IP Hálózaton:**

* **RIP (Routing Information Protocol):**
  - Az egyik legegyszerűbb belső gateway protokoll, amely távolságvektor alapú és periodikusan frissíti a routertáblákat.

* **RIP 2:**
  - Az újabb változat a RIP protokollból, amely támogatja a CIDR-t és VLSM-et, valamint megbízhatóbb és biztonságosabb.

* **OSPF (Open Shortest Path First):**
  - Egy dinamikus belső gateway protokoll, amely link állapotokat használ az optimális útvonalak kiválasztásához.

**4. DHCP Protokoll:**

* **Definíció:**
  - Dinamikus Host Configuration Protocol, amely automatikusan hozzárendel IP címeket és más hálózati konfigurációs információkat eszközöknek a hálózaton.

* **Működés:**
  - Az eszköz indításakor a DHCP kérést küld a hálózatnak, és a DHCP szerver automatikusan hozzárendeli az elérhető IP címet.

**5. ARP és RARP Címfeloldási Protokoll:**

* **ARP (Address Resolution Protocol):**
  - A fizikai címet (MAC cím) feloldja a logikai IP címre a hálózaton belül.

* **RARP (Reverse Address Resolution Protocol):**
  - A logikai IP címet hozza összefüggésbe a fizikai címmel, általában boot folyamatok során alkalmazzák.
