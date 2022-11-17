# Fem tips för ett lyckat .Net-projekt

## Utgå från behov, inte teknik

Undvik att optimera i förväg. 

## Skriv tester

Uttryck kraven för en funktion i testfall, gärna med BDD och SpecFlow, *innan* du börjar koda funktionen. Använd testfallen som ett sätt att "driva programmeringen". 

Skriv tester som uttrycker *vad* systemet förväntas göra, snarare än tester som verifierar *hur* systemet fungerar.

Det innebär att hellre skriva funktionstester på API-nivå, än enhetstester av klasser. Enhetstester på klassnivå kommer ofta kunna vara i vägen för fortsatt utveckling då de är väldigt beroende av *hur* man skrivit koden. Det innebär att en förändring eller refaktorisering riskerar att påverka väldigt många tester, vilket gör att enhetstesterna är i vägen istället för att hjälpa.

## Automatisera, bygge/deployment
## Stuprör, inte lager
## Refaktorisera


