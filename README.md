## Skript CarDelivery na QBCore Framework. ##

- Začněte misi pro dodávku auta, ukradněte auto, dojeďte s ním na místo určení a vydělávejte.

## Funkce ##

- Výplata na základě stavu vozidla (motor, karoserie, pozice)
- Velmi konfigurovatelné
- Cooldown mezi každou přijatou prací
- Možná policejní honička, když je auto odcizeno
- Systém hodnocení s lepšími auty, čím více xp získáte
- Chat příkazy pro kontrolu aktuální úrovně
- Možnosti úpravy hodnosti správce
- Oznámení o vyšší a nižší úrovni
- Vozidla smazaná více bez problémů
- **NOVINKA** Nyní používá qb-target a polyzone

## Požadavky ##

- [QbCore framework](https://github.com/qbcore-framework)
  - Polyzone - Pokud nemáte v základní knihovně, nebo chcete lepší upravitelnou verzy tak zde je odkaz na stažení. ( https://drive.google.com/file/d/1HERgTQ0oxughilSp0qo7QnTZjuhE5cSt/view?usp=share_link )
  - QB-Target - Pokud nemáte v základní knihovně, nebo chcete lepší upravitelnou verzy tak zde je odkaz na stažení. ( https://drive.google.com/file/d/1TWXZ_ZVgRTQUMYrfiOYdCR4fiSOj2qK4/view?usp=share_link )

## Založit ##

1. Stáhněte nebo naklonujte toto úložiště ve složce zdrojů
2. Odstraňte z názvu složky část "-main".
3. Přidejte řádek do souboru server.cfg -> Cardelivery
4. Přidejte řádek dovnitř [qb] -> qb-core -> server -> player.lua

``` Lua
   PlayerData.metadata['cardeliveryxp'] = PlayerData.metadata['cardeliveryxp'] nebo 0
```

5. Pokud váš server běží, nezapomeňte jej restartovat nebo provést **/refresh** a také **/start Cardelivery**

![Zadejte tento řádek](https://i.imgur.com/hae5hLd.png)

## Pokyny ##

- Chcete-li zahájit práci, přejděte na místo zobrazené na mapě níže.

![Mapa](https://i.imgur.com/4xeQvGS.png)

- Jakmile tam budete, jděte vedle NPC a pomocí třetího oka (levý alt) zahajte práci. Obdržíte zprávu o vozidle, které potřebujete ukrást.

![Místo zahájení práce](https://i.imgur.com/b4coTdR.png)

- Následujte cíl, pomocí libovolného zámku otevřete auto a v případě potřeby zapněte hotwire.
- Jeďte do cíle. Pozor, pokud je auto zničeno, úloha **selže**
- Jakmile dorazíte do cíle, zastavte auto uvnitř cíle na mini mapě. Práce skončí a dostanete zaplaceno v závislosti na ujeté vzdálenosti a stavu vozu.

## Informace o konfiguraci a překladu ##

[Přejděte na stránku wiki pro podrobné vysvětlení každé proměnné](https://github.com/00MoDas00/Cardelivery-QBCORE/wiki)

## Podpora ##

- Chcete mě podpořit, nebo s něčím pomoci? 
- Můžete tak učinit prostřednictvím Discordu kde ti pomůžu, nebo pokud mě budeš chtít podpořit, zašlu jak to je možné -> [Discord](MoDas#6969)
