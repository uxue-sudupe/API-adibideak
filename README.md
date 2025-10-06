 
# 🔓 Datu Irekiak eta APIak
 
Aurkezpen honek **datu irekiak** zer diren eta **APIek** datu irekien berrerabilera nola errazten duten azaldu nahi du,  
Europako eta Espainiako araudiari erreparatuz, eta **EAEko** (Euskal Autonomia Erkidegoa) testuinguruan kokatuta. 

Azpian, azalpen laburrak, esteka erabilgarriak eta adibide praktikoak aurkituko dituzu.

---

## 📚 Eduki-taula

1. [Zer dira Datu Irekiak?](#1-zer-dira-datu-irekiak-open-data)  
2. [Zer dira APIak? eta zergatik garrantzitsuak?](#2-eta-zer-dira-apiak)  
3. [Araudia: EB, Espainia eta EAE](#3-datu-irekiei-eta-apiei-buruzko-araudia)  
4. [Adibide praktikoak (Colab)](#4-adibide-praktikoak)  


---

## 1. Zer dira Datu irekiak (open data)

**Open Data** (datu irekiak) administrazioek, erakundeek edo enpresek datuak  
**modu libre eta eskuragarrian** argitaratzea da, edonork **erabili, berrerabili eta zabaldu** ahal izateko.

### Ezaugarri nagusiak

- **Publikoki eskuragarriak:**  
  Edonork sarbidea izan behar du, oztopo edo murrizketa bidegaberik gabe.

- **Doakoak edo kostu txikikoak:**  
  Sarbideak eta berrerabilerak ez lukete ordainketa esanguratsurik ekarri behar.

- **Formatu ireki eta makina bidez irakurgarrietan:**  
  Adib.: `CSV`, `JSON`, `XML`, `RDF`, `SDMX`  
  *(ez **PDF** edo jabetzako formatu itxiak, hala nola `.xls`)*.

- **Metadatu argiak:**  
  Jatorria, eguneratze-data, edukia, lizentziak, kalitate-adierazleak…

- **Lizentzia irekiak:**  
  Besteek erabili, berrerabili eta konbinatu ahal izan ditzaten.  
  Adib.: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), [CC0](https://creativecommons.org/publicdomain/zero/1.0/).

- **Berrerabilgarriak:**  
  Aplikazioak, txostenak, bistaratzeak edo zerbitzu berriak sortzeko baliagarriak.

- **Eguneratuak eta kalitatezkoak:**  
  Datuak eguneratuta, koherente eta fidagarri mantendu behar dira.

- **Ez-diskriminatzaileak:**  
  Ez da beharrezkoa erregistratzea edo baldintza berezirik betetzea sarbidea izateko.

> 💡 **Gomendioa:** formatu irekiak + metadatu onak + lizentzia argiak = berrerabilera erraza.

### Opendata atariak

- 🌍 **Europako Open Data ataria:**  
  [https://data.europa.eu](https://data.europa.eu)
- 🌐 **Open Data Euskadi ataria:**  
  [https://opendata.euskadi.eus](https://opendata.euskadi.eus)  

---

## 2. Eta zer dira APIak?

**APIak** (*Application Programming Interfaces*) datuetarako **sarbide programagarria** ematen duten **tresna teknikoak** dira.  
**Open Data** da politika/printzipioa (*zer*), eta **APIak** dira horretara heltzeko **modua** (*nola*):  
datuak automatikoki kontsultatu, eguneratu edo deskargatzeko bidea.

### Zergatik dira APIak garrantzitsuak?

- **a) Automatizazioa eta berrerabilera**  
  Aplikazioek edo webguneek datuak zuzenean eskuratzen dituzte

- **b) Eguneratze jarraitua**
Fitxategi estatikoekin alderatuta, API bidez datuak beti eguneratuak egon daitezke.

- **c) Kontsulta selektiboa**
Soilik behar duzun zatia eska dezakezu (adib. “2024ko garraio-datuak Gipuzkoan”).

- **d) Interoperabilitatea**
Estándar irekiak (REST, JSON, XML, SDMX, RDF…) → sistema ezberdinek elkarreragina.

- **e) Gardentasuna eta trazabilitatea**
Dokumentatutako sarbideak, bertsioak eta logak → kontrol eta gobernantza hobea.


## 3. Datu irekiei eta APIei buruzko araudia

- **Europako Parlamentuaren eta Kontseiluaren 2019/1024 (EB) Zuzentaraua, 2019ko ekainaren 20koa, sektore publikoko datu irekiei eta informazioaren berrerabilerari buruzkoa**
Open Data Directive bezala ezaguna, 2003/98/EE eta 2013/37/UE zuzentarauak ordezkatzen ditu. “Balio handiko datu multzoak” (High Value Datasets) doan, API bidez eta formatu irekian argitaratu behar direla dio. Datuak formatu ireki eta makina bidez irakurgarrietan argitaratu behar dira, lizentzia argiekin.

- **37/2007 Legea, azaroaren 16koa, sektore publikoko informazioa berrerabiltzeari buruzkoa**

- **108/2012 Dekretua: Euskal Autonomia Erkidegoko Administrazio Orokorrean informazioaren berrerabilerari buruzkoa**

Lege hauek ez dute APIen erabilera derrigorrezkoa egiten, baina bai gomendatua.


## 4 Adibide praktikoak 

Datu estatistikoen APIak probatzeko kuaderno hauek prestatu dira, R hizkuntza erabilita. Google Colab-en irekitzeko Google-eko kontu bat beharko duzu

📘  Eurostaten web zerbitzua erabiltzeko adibideak :[![Ireki Colab-en](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/uxue-sudupe/API-adibideak/blob/main/code_examples/eu/API_Eurostat_eu.ipynb)  

📘  INEren web zerbitzua erabiltzeko adibideak: [![Ireki Colab-en](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/uxue-sudupe/API-adibideak/blob/main/code_examples/eu/API_INE_eu.ipynb)  

📘  Open Data Euskadiren API erabiltzeko adibideak:[![Ireki Colab-en](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/uxue-sudupe/API-adibideak/blob/main/code_examples/eu/API_Opendata_Euskadi_eu.ipynb)  









