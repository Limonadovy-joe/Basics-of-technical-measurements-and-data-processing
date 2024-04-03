# Basics-of-technical-measurements-and-data-processing

- [Design and preparation of measurements](#design-and-preparation-of-measurements)
- [Kalibrace](#kalibrace)
- [Adjustace](#adjustace)
- [Presnost a preciznost](#presnost-a-preciznost)
- [Třída přesnosti](#třída-přesnosti)
- [Chyby měření](#chyby-měření)
- [Teorie náhodných chyb](#teorie-náhodných-chyb)
- [Notes](#notes)

- **Metrology** is the scientific study of measurement, and also by creating measurement methods and investigating the relationship between the measured and the actual value of the quantity(veliciny). 
- Units are usually realized by an **etalon (standard).**
- The Czech Metrological Institute ensures the **uniformity and accuracy** of gauges and measurements in all fields of scientific, technical and economic activity

- One of the objectives of the **measurement is to arrive(dospet) at the formulation of physical laws.** By measuring, on the contrary, we verify the validity of the physical laws to which we are subject arrived at in a theoretical way.
- Most often, however, we measure the physical properties of various objects (e.g. the mass or temperature) and the **relationship of certain properties (e.g. the dependence of electrical resistance on the temperature of a resistor).**



## Design and preparation of measurements
**The physical measurement process consists of three working stages:**
1. **Preparation of measurements**
  - The experimenter must first study the necessary theory of the investigated phenomenon and choose a suitable method
  - Before the actual measurement, it is also necessary to consider **what external factors can affect the measurement (e.g. the location of the devices must be subordinated to this),** it is also necessary to know the local laboratory conditions – **temperature, pressure, humidity, possibly
disturbing magnetic field, thermal, light or radioactive background.**
  - As part of the preparation, it is also desirable to carry out(provest) a theoretical analysis of the measurement accuracy and to adapt the own measuring procedure and measuring devices to it.
  - It is also advisable to realize in time **what systematic(soustavny) errors the measurement will be burdened(zatizeno) with** (whether
due to the instruments(nastroju) or method used).

2. **Own measurements**
  - před detailním měřením je vhodné vykonat zhruba celé měření, abychom např. věděli, v jakých rozsazích hodnot veličin budeme měřit, zda nevznikají
**zřetelné extrémy (rezonanční maximum <sup>[1](#notes)</sup>).** Tomu je třeba přizpůsobit rozsahy přístrojů a jejich citlivost - **KALIBRACE**
  - Zjistíme-li při zápisu výsledků měření, že některá hodnota nápadně vybočuje z řady jiných hodnot téže veličiny, **může to mít dvě příčiny. Buď jde
o hrubou chybu anebo např. o nějaký (třeba i neočekávaný) rezonanční jev.**
  - K měření této hodnoty se proto vrátíme a detailně proměříme **i okolí měnící se veličiny.** Případně pro kontrolu použijeme i jiný přístroj. Jde-li o hrubou chybu při měření (chybné čtení), **hodnotu vyloučíme, aby nám po zpracovánídat měření zbytečně nezkreslovala výsledek a jeho přesnost.**


3. **Measurement data processing(zpracovani)**
  - Jelikož v případě (náhodných) chyb měření jde o náhodné veličiny, bude vhodné – před vlastními postupy zpracování dat měření – stručně uvést základní poznatky o teorii **náhodných chyb, jak je zpracovala matematická statistika.**
  - Matematické disciplíny, jako **teorie pravděpodobnosti, matematická statistika, teorie chyb** dávají experimentální fyzice významný nástroj a např. ji umožňují, aby jen z několika měření veličiny určila její **nejpravděpodobnější hodnotu** včetně determinované přesnosti.
  - Podobně **regresní analýza**, využívající matematickou **metodu nejmenších čtverců**, umožňuje na základě dat měření stanovit **nejpravděpodobnější průběh zkoumané závislosti fyzikálních veličin.**  **Regresní analýza umožňuje modelovat a popsat vztah mezi měřenými veličinami. To umožňuje identifikovat, zda a jak jedna proměnná ovlivňuje druhou.**

## Kalibrace
- je soubor úkonů, kterými se za **specifikovaných podmínek stanoví vztah mezi hodnotami veličin**, které jsou indikovány měřicím systémem a odpovídajícími hodnotami, které jsou realizovány **etalony (standardy).**
- V některých případech se za kalibraci považuje i i n**adjustace výstupních hodnot měřícího systému** tak, aby odpovídaly hodnotám etalonů s definovanou přesností.
- **Například kalibrací teploměru se stanoví chyba, se kterou teploměr měří,** a adjustací (například pomocí kalibračních konstant) se teploměr nastaví tak, aby indikoval skutečnou hodnotu teploty v daném bodě.
- při provádění kalibrace měřícího zařízení se zjišťuje, **jakou chybou zařízení měří v porovnání s kalibračním standardem nebo referenčním standardem.**


## Adjustace
- Celkově lze říci, že kalibrace je obecnějším pojmem, **který zahrnuje proces určení přesnosti měření**, **zatímco adjustace se zaměřuje spíše na konkrétní úpravy nebo změny měřícího zařízení.**


## Presnost a preciznost
- **Presnost**
  - accurancy
  - je souhrnný pojem charakterizující **míru odchylek měření (chyb měření)** od **referenční, standartizovane hodnoty** (tj. hodnoty, která je pokládána za „správnou“)
  - skutecna hodnota merene vel / namerenena hodnota
  - **Pokud je poměr větší než jedna, měření je nadhodnocené**
  - **Pokud je poměr menší než jedna, měření je podhodnocené** -  pokud teploměr v místnosti zobrazuje teplotu o několik stupňů nižší než skutečná teplota, je to příklad podhodnoceného měření. To může být způsobeno například umístěním teploměru v chladnější části místnosti, nedostatečnou expozicí k teplotnímu gradientu,
- **Pravdivost**
  - trueness
  -  že průměr velkého počtu měření nebo zkoušek se blíží skutečné hodnotě měřené veličiny
  -  **jedná se o systematickou chybu(soustavna - je dána přesností (nedokonalostí) měřicího přístroje a měřicí metody), o míru statistického zkreslení**
- **Preciznost**
  - precision
  - se týká **těsnosti shody mezi výsledky měření**; **jedná se o míru rozptylu. <sup>[2](#notes)</sup>**
  - **„preciznost“ (malý rozptyl měření => opakovatelnost nebo reprodukovatelnost)**
 
## Třída přesnosti
-  **t. prenosti přístroje (zkratkou například TP 1,5) je hodnota daná výrobcem přístroje**, ověřená a certifikovaná zkušebnou, že změřené hodnoty udávané přístrojem spadají do **rozptylového intervalu ±X % kolem skutečné hodnoty.**
- **tolerančního rozpětí ±10%**
- 

## Chyby měření
- Podle příčin vzniku dělíme chyby na soustavné a náhodné.
  - **Soustavné chyby**
    - (nebo též systematické chyby) ovlivňují výsledek měření zcela určitým způsobem, **s jistou pravidelností**. Systematičnost této chyby
se projevuje tím, že měřené hodnoty veličiny jsou buď trvale **větší nebo menší, než je hodnota skutečná.**
    - Zdrojem soustavných chyb bývají i měřicí přístroje a měřicí etalony. Lze je vyloučit cejchováním anebo užitím korekčních křivek přístrojů nebo tabulek.
    - Kromě uvedených zdrojů soustavných chyb je dobré si uvědomit, že i samotný proces měření pomocí reálných přístrojů může ovlivňovat měřenou veličinu:
    - **teploměr má nenulovou tepelnou kapacitu, ampérmetr nenulový odpor, voltmetr konečný odpor**
  - **Náhodné chyby**
    -  se vyznačují tím, že působením velmi rozmanitých přesně nedefinovatelných vlivů se hodnoty určité veličiny, naměřené přibližně za stejných podmínek měření, se liší.
    -  Měření fyzikálních veličin představuje v důsledku působení náhodných chyb je **statistický proces s náhodnou proměnnou**
    -  Pravděpodobnou hodnotu měřené **fyzikální veličiny a její chyby tak lze určit statistickými metodami.**
    -  **Vliv náhodných chyb na výsledek měření klesá s počtem opakovaných měření.**

- **Absolutni chyba**
  - Hodnota x fyzikální veličiny zjištěná měřením (tj. **u skalární veličiny její veli-kost, u vektorové veličiny také její směr anebo velikost jejich složek**) se vždy
o něco liší od její skutečné hodnoty x0 (bohužel neznámé). Rozdíl hodnoty naměřené a skutečné se nazývá **skutečná chyba ε** (absolutní chyba): `ε = x − x0`.
  - Tato chyba má jednotku měřené veličiny
- **Relativní chyba**
  - http://fyzikalniolympiada.cz/texty/mereni.pdf
  - Podle **ČSN** 61557 může být relativní pracovní chyba měření maximálně 30%.

## Teorie náhodných chyb







## Notes
- **rezonanční maximum** - 
- **mira rozptylu** - fluktuace, variance nebo také disperze, která vyjadřuje **variabilitu rozdělení souboru náhodných hodnot kolem její střední hodnoty.**
- **amplituda** - rozkmit, výchylka, odchylka,  **maximální hodnota periodicky proměnné fyzikální veličiny**
