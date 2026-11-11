# Panzerpakt

**Spielen: https://panzerpakt.onrender.com**

Rundenbasierte Panzerschlacht für bis zu 12 Spieler, Teil der Swimming-Lions-Spielesammlung.
Jeden Takt bekommt jeder Panzer einen Aktionspunkt – von der Blitz-Schlacht (jede Minute) bis zur Wochen-Schlacht (einmal am Tag zur festen Uhrzeit): fahren, schießen, aufrüsten, AP verschenken
oder die Fähigkeit seiner Klasse nutzen. Dazu Pakte und Verrat, ein schrumpfender Sturm,
der Titan und der Geisterrat der Gefallenen.

## Starten

    node server.js

Keine Abhängigkeiten, Node 18+. Zum Testen läuft `SCHNELLTEST=1 node server.js` 60-mal schneller.

## Render

Web Service, Start-Befehl `node server.js`. Damit Partien einen Neustart überleben:
`supabase_setup.sql` in Supabase ausführen und `SUPABASE_URL` und `SUPABASE_SERVICE_KEY` setzen.
