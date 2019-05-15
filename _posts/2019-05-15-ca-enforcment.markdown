---
title:	"Netzwerkbasierte Erkennung von CA-Anomalien"
date:	2019.05-15 12:00:00
categories: studienprojekt bachelorarbeit masterarbeit
---

Motivation
==========
Verschlüsselte Verbindungen werden in der Regel durch
TLS-basierte Authentifizierung von mindestens einem
Kommunikationspartner abgesichert.

Die Authentizität des Kommunikationspartners wird mit einer
Prüfung seines Zertifikats sichergestellt.
Diese Zertifikate werden von Zertifizierungsstellen (CAs) ausgestellt,
denen der Nutzer (Client, Browser, Betriebssystem) vertraut.

Es gibt derzeit keinen etablierten Mechanismus um dieses
Vertrauen feingranular zu konfigurieren oder überhaupt zu
verifizieren, ob dieses Vertrauen notwendig bzw. gerechtfertigt ist.


Aufgabenstellung
================
Sie entwickeln mit einem Embedded-Rechner (z.B. Raspberry PI)
ein Netzwerkgerät, das lernt, welche Zertifizierungsstellen
Zertifikate für die tatsächlich genutzten verschlüsselten
Verbindungen ausgestellt haben.

In einem zweiten Schritt erkennen Sie Abweichungen von diesen
gelernten Daten.

Mögliche alternative Bearbeitungsmöglichkeiten
----------------------------------------------
* Analyse des Handshakes verschlüsselter Verbindungen
* Entwicklung eines Browser-Plugins anstelle eines Netzwerkgeräts
* Verwendung eines Proxies anstelle eines embedded devices
* Warnungen/Blockaden von Verbindungen bei Abweichungen
* Sammlung großer Datenmengen von unterschiedlichen Clients ("Citizen Science")
* Entwicklung eines Web-Interfaces für Steuerung von Learning/Enforcing

Hinweise
========
* Interesse an IT-Sicherheitsthemen wird vorausgesetzt.
* Grundsätzliche Kenntnisse in Netzwerkthemen und von Zertifikaten werden vorausgesetzt.