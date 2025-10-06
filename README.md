
## API adibideak   


# 1. Zer da Open Data eta zeintzuk dira bere ezaugarriak

**Open Data** (Datu Irekiak) administrazioek, erakundeek edo enpresek datuak **modu libre eta eskuragarrian** argitaratzea da, edonork **erabili, berrerabili eta berriz banatu** ahal izan ditzan.

## Datu irekiaren ezaugarri nagusiak

- **Publikoki eskuragarriak:**  
  Edozein pertsonak sarbidea izan behar du, murrizketa bidegabe edo oztoporik gabe.

- **Doakoak edo kostu txikikoak:**  
  Sarbideak eta berrerabilerak ez lukete ordainketa esanguratsurik ekarri behar.

- **Formatu ireki eta makina bidez irakurgarrietan:**  
  Adibidez: CSV, JSON, XML, RDF, SDMX  
  (ez PDF edo jabetzako formatu itxiak, hala nola `.xls`).

- **Metadatu argiak dituztenak:**  
  Datuak ongi deskribatuta: jatorria, eguneratze-data, edukia, lizentziak, etab.

- **Lizentzia irekiak dituztenak:**  
  Besteek erabili, berrerabili eta konbinatu ahal izan ditzaten.  
  Adibidez: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), [CC0](https://creativecommons.org/publicdomain/zero/1.0/).

- **Berrerabilgarriak:**  
  Beste pertsonek edo erakundeek aplikazioak, txostenak, bistaratzeak edo zerbitzu berriak sor ditzaten ahalbidetu behar dute.

- **Eguneratuak eta kalitatezkoak:**  
  Datuak eguneratuta, koherente eta fidagarri mantendu behar dira.

- **Ez-diskriminatzaileak:**  
  Ez da beharrezkoa erregistratzea edo baldintza berezirik betetzea sarbidea izateko.

---

# 2. Europar Batasuneko araudia

Europar Batasuna aitzindaria izan da **datu irekiaren** eta **sektore publikoko informazioaren berrerabileraren (PSI)** arloan.

## 2019/1024 (EB) Zuzentaraua

**Europako Parlamentuaren eta Kontseiluaren 2019/1024 (EB) Zuzentaraua**  
Sektore publikoko informazioaren **datu irekiak eta berrerabilera** arautzen ditu (*Open Data Directive* izenez ezagutzen dena).

- 2003/98/EE Zuzentaraua (PSI Directive) eta 2013/37/UE berrikuspena ordezkatzen ditu.  
- Erakunde publikoek datuak **formatu ireki eta makina bidez irakurgarrietan** argitaratu behar dituzte, **berrerabilera-lizentzia argiekin**.  
- “**Balio handiko datu multzoak**” (*High Value Datasets*) kategoria ezartzen du: doan, formatu irekietan eta **API bidez** eskuragarri egon behar dute.  
- Ohiko arloak: geoespaziala, Lurraren behaketa, meteorologia, estatistika, mugikortasuna, enpresak, eta abar.

---

# 3. Espainiako araudia

Espainiak zuzentaraua bere arau-esparru nazionalean txertatu du.

## Lege eta dekretu nagusiak

- **37/2007 Legea, azaroaren 16koa:**  
  Sektore publikoko informazioaren berrerabilerari buruzkoa (*Ley PSI*).  
  Zuzentaraua 2003/98/EE transposatu zuen, eta informazio publikoa berrerabiltzeko eskubidea eta baldintzak arautzen ditu.

- **1495/2011 Errege Dekretua:**  
  Legea garatzen du eta **Estatuko Datu Irekiaren Ataria** sortzen du → [datos.gob.es](https://datos.gob.es)

- **203/2021 Errege Dekretua:**  
  (*Eskema Nazional de Interoperabilidad*)  
  Formatu ireki, metadatu eta irisgarritasunaren inguruko betekizunak indartzen ditu.

### Eguneratze prozesuan

Espainia bere araudia **2019/1024 (EB) Zuzentarauaren** arabera egokitzen ari da, bereziki **balio handiko datu multzoei** dagokienez (ikus: **2023/138 (EB) Betearazpen Erregelamendua**).

---

# 4. Euskal Autonomia Erkidegoko araudia eta politikak

Euskal Autonomia Erkidegoak bere marko propioa garatu du, estatuko eta europar esparruen barruan.

## Aipamen nagusiak

- **108/2012 Dekretua:**  
  Euskal Autonomia Erkidegoko Administrazio Orokorrean sektore publikoko informazioaren berrerabilerari buruzkoa.

- **Open Data Euskadi ataria:**  
  [https://opendata.euskadi.eus](https://opendata.euskadi.eus)  
  Eusko Jaurlaritzak kudeatzen du, eta Espainian aitzindaria izan zen (2010ean abiatua).

- **Irekia – Gobernu Irekiaren Estrategia:**  
  Gardentasuna, herritarren parte-hartzea eta datuen berrerabilera integratzen ditu.

- **Interoperabilitate eta Segurtasun Eskema Nazionaletan (ENI eta ENS)** oinarritzen da.

- # 5. Open Data eta APIen arteko harremana

## 5.1 Oinarrizko erlazioa

- **Open Data** politika edo printzipioa da: informazio publikoa eskuragarri eta berrerabilgarri izan dadila.  
- **APIak** tresna teknikoak dira: datu horietara automatikoki sartzea, kontsultatzea eta eguneratzea ahalbidetzen dute.

> Esanda labur: **Open Data “zer” den azaltzen du, eta APIek “nola” egiten den.**

---

## 5.2 Zergatik dira APIak hain garrantzitsuak?

### a) Automatizazioa eta berrerabilera
Aplikazioek edo webguneek datuak zuzenean eskuratu ditzakete:
```bash
GET https://opendata.euskadi.eus/api/dataset/empleo?year=2024

b) Eguneratze jarraitua

Fitxategi estatikoekin alderatuta, API bidez datuak beti eguneratuak daude.

c) Kontsulta selektiboak

API bidez soilik behar duzun zatia eska dezakezu
(adib. "2024ko garraio-datuak Gipuzkoan").

d) Interoperabilitatea

Estándar irekiak erabiltzen dituzte (REST, JSON, XML, SDMX, RDF…),
eta horrek sistema ezberdinen arteko bateragarritasuna bermatzen du.

e) Gardentasuna eta trazabilitatea

Dokumentatutako sarbideak eta bertsioak eskaintzen dira, gobernantza hobetuz.

## 5.3 Araudia eta APIak

Lege europar eta espainiarrek ez dute APIen erabilera derrigorrezkoa egiten, baina gomendatzen dute datu irekiak eskaintzeko modurik onena bezala.

2019/1024 (EB) Zuzentaraua – 6. artikulua

“Balio handiko datu multzoak” formatu irekietan eta API bidez jarri behar dira eskuragarri, ahal denean deskarga masiboa ere eskainiz.

203/2021 Errege Dekretua (Espainia)

Interoperabilitatearen Eskema Nazionala (ENI) ezartzen du eta REST APIak praktika on gisa gomendatzen ditu.

## 6 Adibide praktikoak

📘  Eurostat API SDMX eta API STATISTICS :
 irudi honetan egin klik  [![Ireki Colab-en](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/uxue-sudupe/API-adibideak/blob/main/code_examples/eu/API_Eurostat_eu.ipynb)  
(Google-ko kontu bat beharko duzu)

📘  INE API:
 irudi honetan egin klik  [![Ireki Colab-en](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/uxue-sudupe/API-adibideak/blob/main/code_examples/eu/API_INE_eu.ipynb)  
(Google-ko kontu bat beharko duzu)

📘  Open Data Euskadi API:
 irudi honetan egin klik  [![Ireki Colab-en](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/uxue-sudupe/API-adibideak/blob/main/code_examples/eu/API_Opendata_Euskadi_eu.ipynb)  
(Google-ko kontu bat beharko duzu)








