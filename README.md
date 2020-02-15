# Downloader Fatture elettroniche e i modelli f24 bolli

Progetto derivato da FeCscraper di Pizzillo e modificato da Salvatore Crapanzano https:\\www.salvatorecrapanzano.com

Script per automatizzare il download delle fatture elettroniche e i bolli e le fatture transfrontaliere e le fatture a disposizione usando il servizio Fatture e Corrispettivi. 

Scarica:
a) le fatture emesse e ricevute 
b) modello f24 dei bolli
c) le fatture a disposizione

Vo consiglio di eseguire lo script per il download delle fatture elettroniche ricevute dopo l'esecuzione dello script fatture a disposizione.

Dipendenze Librerie da installare via pip: requests e pytz.

Dati di input in ordine:

CF (Codice fiscale o codice Entratel dell'intermediario commercialista o dello studio associato o del contribuente) di FeC.
PIN di FeC.
Password di FeC.
Codice Fiscale # indicare il cf del cliente o cf del soggetto intermediario appartenente allo studio associato
Data dal
Data al
cf cliente # ripete il cf del cliente, 
piva cliente

Nella sottocartella contenente il cf del contribuente troverai le tue FE e i relativi metadati.

Per i bolli 
CF (Codice fiscale o codice Entratel) di FeC.
PIN di FeC.
Password di FeC.
Codice Fiscale
Partita IVA
Numero Trimestre es: 1 o 2 o 3 o 4 
Anno Es. 2020

att.ne per funzionare la data di scaricamento devi essere antecedente o uguale alla data di pagamento

Ci sono diverse modalitù di accesso, da madificare direttamente nel file
a) me stesso
b) incaricati singoli professionisti
c) incaricati professionisti che fanno parte di uno studio associato

SE NON FUNZIONA, PER VOI DOVETE VEDERE QUESTA PARTE DEL CODICE. CON LO SCRIPT CHE HO CARICATO EE FUNZIONA




