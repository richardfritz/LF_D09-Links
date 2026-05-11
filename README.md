# Ressourcen

## Inhaltsverzeichnis
- [Legende Symbole](#legende-symbole)
- [Grundlagen Netzwerktechnik](#grundlagen-netzwerktechnik)
- [Schichtenmodelle](#schichtenmodelle)
- [Netzwerkgeräte](#netzwerkgeräte)
- [Kryptographie / Verschlüsselung](#kryptographie--verschlüsselung)
- [Firewall / Paketfilterung](#firewall--paketfilterung)
- [VPN](#vpn)
- [Virtualisierung](#virtualisierung)
- [Allgemeine Ressourcen](#allgemeine-ressourcen)
- [Prüfungsvorbereitung](#prüfungsvorbereitung)

---

## Legende Symbole
* ✅ = AP1 (Grundlagen)
* 🌐 = AP2 FISI (Netzwerk / Infrastruktur)
* 💻 = AP2 FIAE (Entwicklung / Software)
* 🔐 = Security / zusätzlich wichtig

## Grundlagen Netzwerktechnik
- [Sebastian Philippi: Netzwerk Grundlagen Playlist](https://www.youtube.com/watch?v=MpmfKq5Aq9A&list=PLCb8EhYsrW_tPXXICCdlCpIO9Ur0iXNg6)
- [Stefan Macke: Netzpläne](https://www.youtube.com/watch?v=ETcc9H3NlVg&list=PLunzHF-cqEKNOpDGznc7SfT2cy8c2BXyj&index=17&pp=iAQB)
---

- [Grundlagen Netzwerktechnik (ElKo)](https://www.elektronik-kompendium.de/sites/net/0503271.htm) ✅
- [Grundbegriffe Netzwerktechnik (ElKo)](https://www.elektronik-kompendium.de/sites/net/1710111.htm) ✅
- [Organisationen in der Netzwerktechnik (ElKo)](https://www.elektronik-kompendium.de/sites/net/1912011.htm) ✅
- [Netzwerk-Infrastruktur (ElKo)](https://www.elektronik-kompendium.de/sites/net/2809061.htm) ✅🌐
- [Netzwerk-Topologie (ElKo)](https://www.elektronik-kompendium.de/sites/net/0503281.htm) ✅🌐
- [Lokale Vernetzung (ElKo)](https://www.elektronik-kompendium.de/sites/net/2509031.htm) ✅🌐
- [Strukturierte Verkabelung (ElKo)](https://www.elektronik-kompendium.de/sites/net/0908031.htm) 🌐

### Schichtenmodelle
- [TCP/IP-Schichtenmodell (ElKo)](https://www.elektronik-kompendium.de/sites/net/0907011.htm) ✅🌐💻
- [OSI-Schichtenmodell (ElKo)](https://www.elektronik-kompendium.de/sites/kom/0301201.htm) ✅🌐💻
- [OSI-Schichtenmodell in der Netzwerktechnik (ElKo)](https://www.elektronik-kompendium.de/sites/net/0706101.htm) ✅🌐
- [OSI Modell Überblick (FI-Forum)](https://www.fachinformatiker.de/files/file/5-iso-osi-schichtenmodell/) ✅🌐💻

## Netzwerkgeräte

| Gerät | Beschreibung | AP |
|---|---|:---:|
| [Router vs. Gateway (Reolink)](https://reolink.com/blog/router-vs-gateway-was-ist-der-unterschied/) | Ein Router vermittelt Pakete zwischen Netzwerken; ein Gateway übersetzt zudem zwischen unterschiedlichen Protokollen. | ✅🌐 |
| [Netzwerkkarte (ElKo)](https://www.elektronik-kompendium.de/sites/net/0811011.htm) | Stellt die physische Schnittstelle eines Geräts zum Netzwerk bereit und besitzt eine eindeutige MAC-Adresse. | ✅🌐 |
| [Repeater (ElKo)](https://www.elektronik-kompendium.de/sites/net/0901091.htm) | Verstärkt und regeneriert Signale auf Schicht 1, um größere Übertragungsdistanzen zu überbrücken. | ✅ |
| [Hub (ElKo)](https://www.elektronik-kompendium.de/sites/net/1405161.htm) | Sendet eingehende Datenpakete an alle angeschlossenen Ports gleichzeitig, ohne Adressfilterung. | ✅ |
| [Bridge (ElKo)](https://www.elektronik-kompendium.de/sites/net/0901101.htm) | Verbindet zwei Netzwerksegmente auf Schicht 2 und filtert den Datenverkehr anhand von MAC-Adressen. | ✅🌐 |
| [Switch (ElKo)](https://www.elektronik-kompendium.de/sites/net/0811021.htm) | Leitet Datenpakete gezielt nur an den Port weiter, an dem das Zielgerät (MAC-Adresse) angeschlossen ist. | ✅🌐 |
| [Managed Switch (ElKo)](https://www.elektronik-kompendium.de/sites/net/2509021.htm) | Konfigurierbarer Switch mit erweiterten Funktionen wie VLANs, Port-Mirroring und QoS. | 🌐 |
| [Router (ElKo)](https://www.elektronik-kompendium.de/sites/net/1404181.htm) | Verbindet verschiedene IP-Netzwerke und entscheidet anhand von Routing-Tabellen, wohin Pakete weitergeleitet werden. | ✅🌐 |
| [Layer-3-Switch (ElKo)](https://www.elektronik-kompendium.de/sites/net/1405171.htm) | Kombiniert die Weiterleitungsgeschwindigkeit eines Switches mit der IP-Routing-Fähigkeit eines Routers. | 🌐 |
| [Gateway (ElKo)](https://www.elektronik-kompendium.de/sites/net/0901111.htm) | Übergangsknoten zwischen Netzwerken mit unterschiedlichen Protokollen; übernimmt die Protokollübersetzung. | ✅🌐 |
| [Server (ElKo)](https://www.elektronik-kompendium.de/sites/net/0505081.htm) | Stellt Dienste (z. B. Dateien, Web, E-Mail) oder Ressourcen für Clients im Netzwerk bereit. | ✅🌐💻 |
| [Firewall (ElKo)](https://www.elektronik-kompendium.de/sites/net/0803051.htm) | Überwacht und kontrolliert den Netzwerkverkehr nach Regelwerken, um unerlaubte Zugriffe zu blockieren. | ✅🌐🔐 |
| [Load Balancer (ElKo)](https://www.elektronik-kompendium.de/sites/net/0904131.htm) | Verteilt eingehende Verbindungen auf mehrere Server, um Überlastung einzelner Systeme zu verhindern. | 🌐💻 |
| [Load Balancing (ElKo)](https://www.elektronik-kompendium.de/sites/net/0906201.htm) | Verfahren zur gleichmäßigen Lastverteilung auf mehrere Systeme für höhere Verfügbarkeit und Performance. | 🌐💻 |

## Kryptographie / Verschlüsselung / Netzwerksicherheit 
- [Sebastian Philippi: Netzwerksicherheit Reloaded Playlist](https://www.youtube.com/watch?v=bF_u0vCfrl0&list=PLCb8EhYsrW_ukGeh-8uSkv5ktYM41fgfV)
- [Sebastian Philippi: Verschlüsseln, Signieren, Korrektheit garantieren Playlist](https://www.youtube.com/watch?v=Lq5u4YsiY_s&list=PLCb8EhYsrW_tZQ4bRkoGz3XzHuExiDWuF)
- [Stefan Macke: Verschlüsselung Video](https://www.youtube.com/watch?v=n87q9bb-Kl4&list=PLunzHF-cqEKNOpDGznc7SfT2cy8c2BXyj&index=7&pp=iAQB)

---
- [Grundlagen Netzwerksicherheit (ElKo)](https://www.elektronik-kompendium.de/sites/net/0908021.htm) ✅🌐💻🔐
- [Sicherheitsrisiken (ElKo)](https://www.elektronik-kompendium.de/sites/net/1811091.htm) ✅🌐💻🔐
- [Sicherheitskonzepte (ElKo)](https://www.elektronik-kompendium.de/sites/net/1901181.htm) 🌐💻🔐
- [Kryptografie (ElKo)](https://www.elektronik-kompendium.de/sites/net/1901151.htm) ✅🌐💻🔐
- [Verschlüsselung (ElKo)](https://www.elektronik-kompendium.de/sites/net/1907041.htm) ✅🌐💻🔐
- [Verschlüsselung prüfen (ElKo)](https://www.elektronik-kompendium.de/sites/net/2005261.htm) 💻🔐
- [Digitale Schlüssel (ElKo)](https://www.elektronik-kompendium.de/sites/net/1909011.htm) ✅🌐💻🔐
- [Kryptografische Verfahren (ElKo)](https://www.elektronik-kompendium.de/sites/net/2006261.htm) 🌐💻🔐
- [Symmetrische Kryptografie (ElKo)](https://www.elektronik-kompendium.de/sites/net/1910101.htm) ✅🌐💻🔐
- [Asymmetrische Kryptografie (ElKo)](https://www.elektronik-kompendium.de/sites/net/1910111.htm) ✅🌐💻🔐
- [Hybride Verfahren (ElKo)](https://www.elektronik-kompendium.de/sites/net/1910141.htm) 🌐💻🔐
- [SSL (ElKo)](https://www.elektronik-kompendium.de/sites/net/0902281.htm) ✅🌐💻🔐
- [TLS (ElKo)](https://www.elektronik-kompendium.de/sites/net/1706131.htm) ✅🌐💻🔐
- [SSL/TLS Schwachstellen (ElKo)](https://www.elektronik-kompendium.de/sites/net/1906041.htm) 🌐💻🔐
- [PGP (ElKo)](https://www.elektronik-kompendium.de/sites/net/1810181.htm) 💻🔐

## Firewall / Paketfilterung
- [Sebastian Philippi: ACL Playlist](https://www.youtube.com/watch?v=zXZgsVPRqnw&list=PLCb8EhYsrW_tLYFnK17Yb_kaoCmqJ3Lzk)

---

- [Firewall (ElKo)](https://www.elektronik-kompendium.de/sites/net/0803051.htm) ✅🌐🔐
- [DMZ (ElKo)](https://www.elektronik-kompendium.de/sites/net/0907241.htm) 🌐🔐
- [Zero Trust (ElKo)](https://www.elektronik-kompendium.de/sites/net/2512031.htm) 🌐💻🔐
- [Deep Packet Inspection (ElKo)](https://www.elektronik-kompendium.de/sites/net/1408271.htm) 🌐🔐
- [Stateful Packet Inspection (ElKo)](https://www.elektronik-kompendium.de/sites/net/1409291.htm) 🌐🔐

## VPN
- [Sebastian Philippi: VPN Playlist](https://www.youtube.com/watch?v=uAgbCoc-s7A&list=PLCb8EhYsrW_vtL-fKFr3lnJJ2yYPNFS6y)

---

- [VPN Grundlagen (ElKo)](https://www.elektronik-kompendium.de/sites/net/0512041.htm) ✅🌐🔐
- [VPN Tunnel (ElKo)](https://www.elektronik-kompendium.de/sites/net/1410141.htm) 🌐🔐
- [WireGuard (ElKo)](https://www.elektronik-kompendium.de/sites/net/2502231.htm) 🌐🔐
- [SSL-VPN (ElKo)](https://www.elektronik-kompendium.de/sites/net/1410151.htm) 🌐🔐
- [OpenVPN (ElKo)](https://www.elektronik-kompendium.de/sites/net/1706181.htm) 🌐🔐
- [IPsec (ElKo)](https://www.elektronik-kompendium.de/sites/net/0906191.htm) 🌐🔐

## System Hardening
- [Systemhärtung (Wiki)](https://de.wikipedia.org/wiki/H%C3%A4rten_(Computer))
- [OS-Hardening (fb-pro)](https://www.fb-pro.com/os-hardening/)


## Virtualisierung
- [Stefan Macke Virtualisierung Video](https://www.youtube.com/watch?v=dcaJRPjI2QQ)
---
- [Virtualisierung (ElKo)](https://www.elektronik-kompendium.de/sites/com/1101011.htm) ✅🌐💻
- [Virtuelle Maschine (ElKo)](https://www.elektronik-kompendium.de/sites/com/3003121.htm) ✅🌐💻
- [Virtualisierung Computertechnik (ElKo)](https://www.elektronik-kompendium.de/sites/com/3003131.htm) 🌐💻
- [Virtualisierung Prozessor (ElKo)](https://www.elektronik-kompendium.de/sites/com/3003141.htm) 🌐💻
- [Vertikale Skalierung](https://phoenixnap.de/Glossar/vertikale-Skalierung)

## Allgemeine Ressourcen

- [USV Typen (FI-Forum)](https://www.fachinformatiker.de/files/file/9-usv-typen/) ✅🌐
- [Backup Formen (FI-Forum)](https://www.fachinformatiker.de/files/file/8-backup-formen/) ✅🌐💻
- [IPv4 und IPv6 (FI-Forum)](https://www.fachinformatiker.de/files/file/40-ipv4-und-ipv6/) ✅🌐💻
- [Fachbegriffe Glossar (FI-Forum)](https://www.fachinformatiker.de/files/file/48-fachbegriffe-und-themen-kurzerklärung/) ✅🌐💻

## Prüfungsvorbereitung
- [Stefan Macke: AP1 Playlist](https://www.youtube.com/playlist?list=PLunzHF-cqEKNOpDGznc7SfT2cy8c2BXyj)✅
---
- [Prüfungskatalog 2025 (FI-Forum)](https://www.fachinformatiker.de/files/file/33-prüfungskatalog-2025-auszug/) ✅🌐💻
---
- [AP1 Masterplan (FI-Forum)](https://www.fachinformatiker.de/files/file/44-ap1-prüfungsvorbereitung-masterplan/) ✅
- [AP1 Lernzettel (FI-Forum)](https://www.fachinformatiker.de/files/file/36-fachinformatiker-ap1-lernzettel-ab-2025/) ✅
---
- [AP2 FISI Masterplan (FI-Forum)](https://www.fachinformatiker.de/files/file/51-ap2-fisi-masterplan/) 🌐
- [AP2 FISI Prüfungsvorbereitung (FI-Forum)](https://www.fachinformatiker.de/files/file/52-fisi-ap-2-prüfungsvorbereitung/) 🌐
---
- [AP2 FIAE Masterplan (FI-Forum)](https://www.fachinformatiker.de/files/file/50-ap2-fiae-masterplan-v10/) 💻
- [Stefan Macke AP2 FIAE Prüfungsvorbereitung Playlist](https://www.youtube.com/watch?v=eQoC4GDzYbI&list=PLunzHF-cqEKMBkR6Jqg1YApkbJWEsy1gy)



