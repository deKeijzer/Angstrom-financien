*Ångström financien
Dit script zet de transactions.csv welke zijn gedownload via de Rabobank om naar een gebruiksvriendelijk Excel bestand.

**Hoe te gebruiken
Volg onderstaand stappenplan om de transacties bij de Rabobank te downloaden.

1. Open de website van de [Rabobank](https://www.rabobank.nl/bedrijven/)
2. Ga naar het tabblad 'Internetbankieren' en klik op de betreffende rekening.
![alt text][figuren/stap1.png]
3. Links op het scherm is nu 'Downloaden transacties' zichtbaar, klik hier op.
![alt text][figuren/stap2.png]
4. Stel vervolgens de instellingen in zoals is weergegeven in onderstaande screenshot.
![alt text][figuren/stap3.png]
5. Klik op 'Bestand downloaden' en sla het bestand op in dezelfde folder als waar het python script staat opgeslagen.
6. Voer het Python script uit.
7. Open het gegenereerde 'transactions.xlsx' bestand en controleer via de website van de [Rabobank](https://www.rabobank.nl/bedrijven/) of de gedownloade transacties exact aansluiten met de huidige administratie. Wanneer er niet tussendoor transacties met de optie 'Vanaf de laatste download' gedownload zijn, dan zouden de gedownloade transacties netjes moeten aansluiten. Indien dit niet het geval is dan kan de optie 'Specifieke datum reeks' bij het downloaden van de transacties gekozen worden om hiervoor te corrigeren. 
![alt text][figuren/stap4.png]