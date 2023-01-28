# iot_project
In dit IoT project staat beveiliging centraal. Het doel van mijn project is dat wanneer mijn scooteraccu van zijn plek wordt gehaald, er een melding wordt gestuurd naar mijn mobiele telefoon. De werking van dit project werkt als volgt:
- De bewegingssensor registreert een beweging wanneer de accu wordt verplaatst;
- De bewegingssensor stuurt een signaal naar de raspberry pi;
- De raspberry pi geeft aan dat er een beweging is gedetecteerd door een rood LEDje te laten knipperen;
- Na het knipperen zet de raspberry pi een reactie in gang op IFTTT;
- De reactie op IFTTT zorgt ervoor dat er een bepaalde melding wordt gestuurt via PushBullet;
- De melding wordt via PushBullet gestuurd naar mijn mobiele telefoon;
- Op mijn mobiele telefoon zie ik vervolgens dat mijn accu is meegenomen op een bepaalde datum om een bepaalde tijd.
