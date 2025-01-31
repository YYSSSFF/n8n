# Weerbericht en smoes-generator om niet naar school te gaan
"Dagelijks een weerbericht met een smoes om niet naar school te gaan. Bij regen krijg je een herinnering dat je de juiste keuze hebt gemaakt. Is het zonnig? (wat het nooit is in Nederland) Dan is het tijd om naar buiten te gaan!" 🌦️😆

##  Over dit project
Dit n8n-project combineert een dagelijks weerbericht met een unieke smoes-generator en extra meldingen via e-mail en Discord.

- Dagelijks een creatief weerbericht in verhaalvorm.
- Smoes-generator – Krijg een originele reden waarom je vandaag niet naar school hoeft. 
- Regenmelding – Een herinnering als het regent, zodat je weet dat je de juiste keuze hebt gemaakt om thuis te blijven. 
- Stormmelding – Waarschuwing als de wind 70 km/u of harder is. 
- Zonnemelding – Notificatie bij mooi weer, zodat je weet dat het tijd is om naar buiten te gaan. ☀

Alle meldingen worden verzonden via e-mail en Discord. 

## Functionaliteiten
- Automatische Weerupdates – Haalt actuele weerdata op via de OpenWeather API. 
- AI Smoes-Generator – Laat ChatGPT een smoes bedenken op basis van het weerbericht. 
- Waarschuwingen voor Extreem Weer – Regen-, storm- en zonnemeldingen. 
- E-mail & Discord Notificaties – Dagelijkse updates rechtstreeks in je inbox of Discord-kanaal. 

## Technologieën
n8n – Workflow automation
OpenWeather API – Weerdata ophalen
ChatGPT API – AI gegenereerde smoesjes en verhalen
E-mail & Discord Webhooks – Meldingen versturen

## Installatie & Gebruik
1. Clone de repository:
````bash
git clone https://github.com/jouw-gebruikersnaam/n8n-weerbericht.git
cd n8n-weerbericht
````
2. Start n8n (Docker of lokaal):
bash
Kopiëren
Bewerken
``` bash
docker-compose up -d
```
3. Importeer de n8n workflow JSON en stel je API-keys in (OpenWeather & ChatGPT).
4. Voeg je e-mail en Discord-webhook toe in de workflow.
5. Geniet van dagelijkse weerupdates met een twist! 








