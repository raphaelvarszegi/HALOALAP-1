**1. DNS (Körzeti Névkezelő Rendszer) Leírása:**

* **Definíció:**
  - A DNS (Domain Name System) egy hierarchikus rendszer, amely a számítógépek és eszközök IP-címekhez való tartozását név alapján biztosítja.

* **Működés:**
  - Fordítja a könnyen megjegyezhető domain neveket IP-címekké, így lehetővé téve az internetes erőforrások azonosítását.

* **Hierarchikus Rendszer:**
  - Az internetes névtereket (domaineket) hierarchiában rendezi el, kezdve az abszolút gyökérdomain-től (".") egészen a specifikus szerverekig.

**2. Domain Név Szerverek Működése:**

* **Domain Név Szerverek:**
  - Olyan szerverek, amelyek kezelik a domain nevek és az azokhoz tartozó IP-címek lekérdezéseit.

* **Kapcsolat Közöttük:**
  - A DNS rendszerben hierarchikus szerverek találhatók, és egy kéréstől függően az információ fentről lefelé vagy alulról felfelé terjed.

**3. Domain Neves Azonosítóhoz Tartozó IP Cím Megállapításának Menete:**

1. **Host (Eszköz) Kérés:**
   - Az eszköz a domain nevet tartalmazó kérést küld a helyi DNS szervernek.

2. **Helyi DNS Keresés:**
   - A helyi DNS szerver megpróbálja megállapítani az IP-címet a saját cache-ben. Ha nincs találat, továbbítja a kérést a gyökér DNS szervernek.

3. **Gyökér DNS Szerver:**
   - A gyökér DNS szerver irányítja a kérést a megfelelő toplevel domain (TLD) szerver felé.

4. **TLD DNS Szerver:**
   - A TLD szerver azonosítja az illeszkedő domain név szerverét.

5. **Domain Név Szerver:**
   - A domain név szerver visszaküldi az IP-címet a helyi DNS szervernek, amely továbbítja azt az eredeti eszköznek.

6. **Cachelt Adatok Frissítése:**
   - A helyi DNS szerver frissíti a cache-ét, így a későbbi hasonló kéréseknél nincs szükség az újra lekérdezésre.
   
**4. Hálózati Védelem Lehetséges Esetei:**

* **Tűzfal:**
  - A tűzfal védelmet nyújt a nem kívánt hozzáférési kísérletekkel és szűri a hálózatra érkező adatokat.

* **Proxy (Proxi):**
  - A proxi olyan közvetítő szerver, amely átvizsgálja és szűri az internetes forgalmat, védelmet nyújtva a hálózatnak.

**5. Biztonsági Protokollok:**

* **SSL/TLS (Secure Sockets Layer/Transport Layer Security):**
  - A biztonságos adatkapcsolatok kialakítására szolgáló protokollok, például webes böngészés esetén.

* **IPSec (Internet Protocol Security):**
  - Az IPSec biztonsági protokoll az IP szinten kódolja és védi az adatokat.

* **SSH (Secure Shell):**
  - A távoli hozzáférés biztonságos protokollja, amely titkosított kapcsolatot hoz létre a kliens és a szerver között.
