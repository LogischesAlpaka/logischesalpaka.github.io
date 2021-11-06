---
layout: post
title: Syncthing - Immer alles dabei
description: Syncthing ist eine OpenSource Software, die Dateisynchronisation so einfach wie möglich macht und doch viele detaillierte Einstellungen möglich macht. 
categories: [Software]
---
[Syncthing](https://syncthing.net/ "Webseite des Projekts") ist eine OpenSource Software, die Dateisynchronisation so einfach wie möglich macht und doch viele detaillierte Einstellungen möglich macht.  
Dabei funktioniert das Programm ohne zwischengeschaltete Server. Sozusagen die eigene Cloud, nur einfacher.  
  
Ich persönlich nutze es um meine Musikbibliothek, meine Joplin Notizen (vielleicht mache ich hier auch mal einen Artikel drüber) und einige Dateien zwischen Notebook, Android Smartphone und RaspberryPi Synchron zu halten.  
Mit Syncthing stehen einem praktisch alle Möglichkeiten zur Verfügung.  

## Ich will das auch - Was muss ich tun?
Nach Download und Start des Programmes, wird man auf das Webinterface verwiesen:

[<img src="{{ site.baseurl }}/images/2021-11-06 121339.png">]({{ site.baseurl }}/images/2021-11-06 121339.png)
  
Hier angekommen fügt man als allererstes einen Ordner hinzu. Jeder Ordner hat eine eigene Ordnerkennung. Über diese wird der Ordner im Geräteverbund identifiziert.  
Interessierte können sich noch an den anderen Einstellungen austoben, aber im Grunde reicht dies aus, um diesen Ordner zu Synchronisieren.  
Um unseren Ordner auch auf anderen Geräten zu synchronisieren, benötigen wir Syncthing auch dort. Syncthing gibt es praktisch für jede Plattform.  
Wenn andere Geräte mit Synchting in eurem Netzwerk sind, dann wird euch die Gerätekennung schon beim Hinzufügen des Gerätes vorgeschlagen. Dort könnt ihr auch auswählen, welche Ordner ihr mit dem Gerät teilen wollt.  
Gegebenenfalls müsst ihr auf dem fremden Gerät noch einmal bestätigen, dass ihr den Ordner auch wirklich synchronisieren wollt.  

## Was sonst noch wichtig ist...
Außerdem praktisch an Syncthing ist, dass es die Verbindungen verschlüsselt zwischen den Geräten aufbaut.  
Und sollten die Geräte nicht im selben Netzwerk sein, dann synchronisieren sie sich über die Synchting Relay Server, natürlich auch nur Ende-zu-Ende Verschlüsselt.  
Sollte man den öffentlichen Servern nicht vertrauen, kann man sogar seinen eigenen Aufsetzen oder die Synchronisation über das Internet deaktivieren.  
  
  
Solltet ihr Fragen oder Anregungen haben, lasst es mich gerne wissen.
