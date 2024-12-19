# 🌾 CampiAgricoli

Benvenuto nel repository principale del progetto **CampiAgricoli**! Qui vengono raccolte e organizzate tutte le repository del nostro ecosistema di monitoraggio e gestione dati agricoli sviluppato da **Nicolas Corini** e **Pietro Mori**.

---

## 🚀 Obiettivi del Progetto

Il progetto ha lo scopo di:

- Monitorare parametri ambientali e del suolo nei campi agricoli o serre.
- Fornire agli agricoltori strumenti per ottimizzare l’uso delle risorse.
- Migliorare la resa agricola attraverso un sistema centralizzato di analisi dei dati.

---

## 📦 Struttura del progetto

L'organizzazione raccoglie i seguenti componenti:

1. **Stazioni Sensore**  
   Repository per il firmware delle stazioni sensore basato su **ESP32** e comunicazione **LoRa**.
   
2. **Home Station**  
   Repository del codice per la stazione centrale che riceve i dati via LoRa e li invia al server via **Wi-Fi**.
   
3. **Backend e API**  
   Servizi backend sviluppati con **.NET Core 8** e API RESTful per gestire la comunicazione con il database.
   
4. **Database**  
   Struttura del database **MSSQL** per memorizzare e analizzare i dati provenienti dai sensori.
   
5. **Dashboard Web**  
   Frontend sviluppato con **React** e **Mantine**, supportato da **Vite**, per la visualizzazione dei dati in tempo reale.

---

## 📊 Architettura del Sistema

- **Microcontrollori ESP32** con sensori per rilevare parametri come temperatura, umidità del suolo e ambiente.
- **Comunicazione LoRa** per la trasmissione dati a lunga distanza.
- **Server Backend** con API RESTful per la gestione dei dati e l'interazione con il database.
- **Dashboard Web** per una visualizzazione intuitiva dei dati raccolti.

---

## 🛠 Tecnologie Utilizzate

- **Hardware**: ESP32, sensori SEN0193, DS18B20, DHT22  
- **Comunicazione**: LoRa, Wi-Fi  
- **Backend**: .NET Core 8, Entity Framework  
- **Database**: MSSQL  
- **Frontend**: React, Mantine, Vite  
- **Contenitori**: *(Sviluppi futuri)* Docker  

---

## 🌱 Sviluppi Futuri

- Integrazione con **LoRaWAN** e **The Things Network (TTN)**.  
- Algoritmi di **Machine Learning** per l'analisi predittiva.  
- Integrazione con dati meteorologici esterni.  
- Ottimizzazione energetica tramite pannelli solari.  

---

## 🤝 Contributori

- **Nicolas Corini**  
- **Pietro Mori**

Contribuisci anche tu! Ogni miglioramento è benvenuto. 🌟

---

Per suggerimenti o domande, sentiti libero di aprire un'**issue** o un **pull request** nei vari repository.
