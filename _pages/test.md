---
layout: post
title: Test
permalink: /test/
---
# Dies ist ein Test

```sql
-- Arbeitsauftrag Nr. 19
-- Aufgabe 4)
-- a)
SELECT Saison, fname AS 'Fahrerweltmeister'
FROM tbl_fahrer, tbl_wmtitel
WHERE tbl_fahrer.fnummer = tbl_wmtitel.fnummer;

-- b)
SELECT Saison, tname AS 'Teamweltmeister'
FROM tbl_team, tbl_wmtitel
WHERE tbl_team.tnummer = tbl_wmtitel.tnummer;

-- c) 
SELECT Saison, tname AS 'Teamweltmeister', tpunkte AS 'Team_Punkte'
FROM tbl_team, tbl_wmtitel
WHERE tbl_team.tnummer = tbl_wmtitel.tnummer
AND tpunkte > 140;

-- d)
SELECT saison, fname AS Fahrerweltmeister, fpunkt AS Fahrer_Punkte, tname AS Teamweltmeister, tpunkte AS Team_punkte
FROM tbl_wmtitel, tbl_fahrer, tbl_team
WHERE tbl_fahrer.fnummer=tbl_wmtitel.fmnummer
AND tbl_wmtitel.tnnummer=tbl_team.tnnummer;

-- e)
SELECT saison, fname AS Fahrerweltmeister, fpunkt AS Fahrer_Punkte, tname AS Teamweltmeister, tpunkte AS Team_punkte
FROM tbl_wmtitel, tbl_fahrer, tbl_team
WHERE tbl_fahrer.fnummer=tbl_wmtitel.fmnummer
AND tbl_wmtitel.tnnummer=tbl_team.tnnummer
AND tname = 'Ferarri'
AND fname = 'Schuhmacher'
AND fvorname = 'Michael';
```