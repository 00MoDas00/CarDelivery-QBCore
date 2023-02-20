# Skript CarDelivery na QBCore Framework.

Začněte misi pro dodávku auta, ukradněte auto, dojeďte s ním na místo určení a vydělávejte.
*Poznámka: Tato větev nebude aktualizována, pokud to nebude požadováno konkrétně pro tuto větev.
Všechny vytvořené problémy jsou výchozí pro novou větev.

## Funkce

- Výplata na základě stavu vozidla (motor, karoserie, úroveň)
- Velmi konfigurovatelné
- Cooldown mezi každou přijatou prací
- Vozidla se objeví buď zaparkovaná nebo projíždějící (brzy)
- Velmi základní systém hodností, zatím se nic nemění
- Možná policejní honička, když je auto odcizeno
- Systém hodnocení s lepšími auty, čím více xp získáte
- Chat příkazy pro kontrolu aktuální úrovně pomocí /deliveryxp
- Možnosti úpravy hodnosti správce pomocí /cardeliveryxp (volba) (číslo)
- Oznámení o vyšší a nižší úrovni

## Požadavky ## (Musí mít)

- QbCore framework(https://github.com/qbcore-framework)

## Založit

1. Stáhněte nebo naklonujte toto úložiště ve složce zdrojů
2. Odstraňte z názvu složky část "-main".
3. Přidejte řádek do souboru server.cfg -> **zajistěte hiype-cardelivery**
4. Přidejte řádek dovnitř [qb] -> qb-core -> server -> player.lua

``` Lua
   PlayerData.metadata['cardeliveryxp'] = PlayerData.metadata['cardeliveryxp'] nebo 0
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ukázkový obrázek naleznete ve spodní části této sekce.<br>

5. Pokud váš server běží, nezapomeňte jej restartovat nebo provést **/refresh** a také **/start hiype-cardelivery**

![Zadejte tento řádek](https://i.imgur.com/hae5hLd.png)

## Pokyny ##

Chcete-li zahájit práci, přejděte na místo zobrazené na mapě níže.

![Mapa](https://i.imgur.com/4xeQvGS.png)

Až tam budete, jděte vedle NPC a stisknutím klávesy E na klávesnici spusťte úlohu. Automaticky se zobrazí cíl.

![Místo zahájení práce](https://i.imgur.com/b4coTdR.png)

Následujte cíl, pomocí libovolného zámku otevřete auto a v případě potřeby zapněte hotwire.
Jeďte do cíle. Pozor, pokud je auto zničeno, úloha **selže**!
Jakmile dorazíte do cíle, zastavte auto uvnitř cíle na mini mapě. Práce skončí a dostanete zaplaceno v závislosti na ujeté vzdálenosti a stavu vozu.

## Podpora ##

Pokud mě chcete jakýmkoli způsobem podpořit, můžete tak učinit prostřednictvím tohoto odkazu -> [Streamelements donos](https://streamelements.com/hiype/tip)<br>
Tento odkaz vás přesměruje na darovací stránku Streamelements, která zobrazuje dar v mém streamu na youtube, pokud jsem živě<br>
P.S. Žiju jen zřídka a tohle bylo prostě jednodušší



