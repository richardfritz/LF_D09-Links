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
- [Sebastian Philippi Netzwerk Grundlagen Playlist](https://www.youtube.com/watch?v=MpmfKq5Aq9A&list=PLCb8EhYsrW_tPXXICCdlCpIO9Ur0iXNg6)
- [Stefan Macke Netzpläne](https://www.youtube.com/watch?v=ETcc9H3NlVg&list=PLunzHF-cqEKNOpDGznc7SfT2cy8c2BXyj&index=17&pp=iAQB)

---

| Link | Beschreibung | AP |
|---|---|:---:|
| [Grundlagen Netzwerktechnik](https://www.elektronik-kompendium.de/sites/net/0503271.htm) | Einführung in grundlegende Konzepte und Begriffe der Netzwerktechnik. | ✅ |
| [Grundbegriffe Netzwerktechnik](https://www.elektronik-kompendium.de/sites/net/1710111.htm) | Kompakte Erklärung der wichtigsten Fachbegriffe aus der Netzwerktechnik. | ✅ |
| [Organisationen in der Netzwerktechnik](https://www.elektronik-kompendium.de/sites/net/1912011.htm) | Überblick über wichtige Normierungs- und Standardisierungsorganisationen (IEEE, IETF, ISO). | ✅ |
| [Netzwerk-Infrastruktur](https://www.elektronik-kompendium.de/sites/net/2809061.htm) | Beschreibt Aufbau und Komponenten einer typischen Netzwerk-Infrastruktur. | ✅🌐 |
| [Netzwerk-Topologie](https://www.elektronik-kompendium.de/sites/net/0503281.htm) | Erklärt physische und logische Anordnungsformen von Netzwerken (Bus, Ring, Stern usw.). | ✅🌐 |
| [Lokale Vernetzung](https://www.elektronik-kompendium.de/sites/net/2509031.htm) | Grundlagen zur Vernetzung in lokalen Netzwerken (LAN) inkl. Medien und Technologien. | ✅🌐 |
| [Strukturierte Verkabelung](https://www.elektronik-kompendium.de/sites/net/0908031.htm) | Erklärt den standardisierten Aufbau einer strukturierten Gebäudeverkabelung nach EN 50173. | 🌐 |

### Schichtenmodelle

| Link | Beschreibung | AP |
|---|---|:---:|
| [TCP/IP-Schichtenmodell](https://www.elektronik-kompendium.de/sites/net/0907011.htm) | Beschreibt das vierschichtige TCP/IP-Modell als praktische Grundlage der Internetkommunikation. | ✅🌐💻 |
| [OSI-Schichtenmodell](https://www.elektronik-kompendium.de/sites/kom/0301201.htm) | Erläutert das siebenschichtige ISO/OSI-Referenzmodell zur Standardisierung von Netzwerkkommunikation. | ✅🌐💻 |
| [OSI-Schichtenmodell in der Netzwerktechnik](https://www.elektronik-kompendium.de/sites/net/0706101.htm) | Zeigt die praktische Bedeutung und Zuordnung des OSI-Modells in der Netzwerktechnik. | ✅🌐 |
| [OSI Modell Überblick](https://www.fachinformatiker.de/files/file/5-iso-osi-schichtenmodell/) | Kompakte Übersicht der OSI-Schichten als Lernunterlage vom Fachinformatiker-Forum. | ✅🌐💻 |

## Netzwerkgeräte

| Gerät | Beschreibung | AP |
|---|---|:---:|
| [Router vs. Gateway](https://reolink.com/blog/router-vs-gateway-was-ist-der-unterschied/) | Ein Router vermittelt Pakete zwischen Netzwerken; ein Gateway übersetzt zudem zwischen unterschiedlichen Protokollen. | ✅🌐 |
| [Netzwerkkarte](https://www.elektronik-kompendium.de/sites/net/0811011.htm) | Stellt die physische Schnittstelle eines Geräts zum Netzwerk bereit und besitzt eine eindeutige MAC-Adresse. | ✅🌐 |
| [Repeater](https://www.elektronik-kompendium.de/sites/net/0901091.htm) | Verstärkt und regeneriert Signale auf Schicht 1, um größere Übertragungsdistanzen zu überbrücken. | ✅ |
| [Hub](https://www.elektronik-kompendium.de/sites/net/1405161.htm) | Sendet eingehende Datenpakete an alle angeschlossenen Ports gleichzeitig, ohne Adressfilterung. | ✅ |
| [Bridge](https://www.elektronik-kompendium.de/sites/net/0901101.htm) | Verbindet zwei Netzwerksegmente auf Schicht 2 und filtert den Datenverkehr anhand von MAC-Adressen. | ✅🌐 |
| [Switch](https://www.elektronik-kompendium.de/sites/net/0811021.htm) | Leitet Datenpakete gezielt nur an den Port weiter, an dem das Zielgerät (MAC-Adresse) angeschlossen ist. | ✅🌐 |
| [Managed Switch](https://www.elektronik-kompendium.de/sites/net/2509021.htm) | Konfigurierbarer Switch mit erweiterten Funktionen wie VLANs, Port-Mirroring und QoS. | 🌐 |
| [Router](https://www.elektronik-kompendium.de/sites/net/1404181.htm) | Verbindet verschiedene IP-Netzwerke und entscheidet anhand von Routing-Tabellen, wohin Pakete weitergeleitet werden. | ✅🌐 |
| [Layer-3-Switch](https://www.elektronik-kompendium.de/sites/net/1405171.htm) | Kombiniert die Weiterleitungsgeschwindigkeit eines Switches mit der IP-Routing-Fähigkeit eines Routers. | 🌐 |
| [Gateway](https://www.elektronik-kompendium.de/sites/net/0901111.htm) | Übergangsknoten zwischen Netzwerken mit unterschiedlichen Protokollen; übernimmt die Protokollübersetzung. | ✅🌐 |
| [Server](https://www.elektronik-kompendium.de/sites/net/0505081.htm) | Stellt Dienste (z. B. Dateien, Web, E-Mail) oder Ressourcen für Clients im Netzwerk bereit. | ✅🌐💻 |
| [Firewall](https://www.elektronik-kompendium.de/sites/net/0803051.htm) | Überwacht und kontrolliert den Netzwerkverkehr nach Regelwerken, um unerlaubte Zugriffe zu blockieren. | ✅🌐🔐 |
| [Load Balancer](https://www.elektronik-kompendium.de/sites/net/0904131.htm) | Verteilt eingehende Verbindungen auf mehrere Server, um Überlastung einzelner Systeme zu verhindern. | 🌐💻 |
| [Load Balancing](https://www.elektronik-kompendium.de/sites/net/0906201.htm) | Verfahren zur gleichmäßigen Lastverteilung auf mehrere Systeme für höhere Verfügbarkeit und Performance. | 🌐💻 |

## Kryptographie / Verschlüsselung / Netzwerksicherheit
- [Sebastian Philippi Netzwerksicherheit Reloaded Playlist](https://www.youtube.com/watch?v=bF_u0vCfrl0&list=PLCb8EhYsrW_ukGeh-8uSkv5ktYM41fgfV)
- [Sebastian Philippi Verschlüsseln, Signieren, Korrektheit garantieren Playlist](https://www.youtube.com/watch?v=Lq5u4YsiY_s&list=PLCb8EhYsrW_tZQ4bRkoGz3XzHuExiDWuF)
- [Stefan Macke Verschlüsselung Video (1,5h)](https://www.youtube.com/watch?v=n87q9bb-Kl4&list=PLunzHF-cqEKNOpDGznc7SfT2cy8c2BXyj&index=7&pp=iAQB)

---

| Link | Beschreibung | AP |
|---|---|:---:|
| [Grundlagen Netzwerksicherheit](https://www.elektronik-kompendium.de/sites/net/0908021.htm) | Einführung in die wichtigsten Konzepte und Schutzziele der Netzwerksicherheit (CIA-Triade). | ✅🌐💻🔐 |
| [Sicherheitsrisiken](https://www.elektronik-kompendium.de/sites/net/1811091.htm) | Überblick über typische Bedrohungen und Angriffsvektoren in Netzwerken. | ✅🌐💻🔐 |
| [Sicherheitskonzepte](https://www.elektronik-kompendium.de/sites/net/1901181.htm) | Erklärt grundlegende Konzepte und Maßnahmen zum Schutz von IT-Systemen und Netzwerken. | 🌐💻🔐 |
| [Kryptografie](https://www.elektronik-kompendium.de/sites/net/1901151.htm) | Einführung in die Grundlagen der Kryptografie und ihrer Einsatzgebiete in der IT-Sicherheit. | ✅🌐💻🔐 |
| [Verschlüsselung](https://www.elektronik-kompendium.de/sites/net/1907041.htm) | Beschreibt die Grundprinzipien und gängigen Verfahren zur Datenverschlüsselung. | ✅🌐💻🔐 |
| [Verschlüsselung prüfen](https://www.elektronik-kompendium.de/sites/net/2005261.htm) | Zeigt, wie die Stärke und Korrektheit einer Verschlüsselungsimplementierung überprüft werden kann. | 💻🔐 |
| [Digitale Schlüssel](https://www.elektronik-kompendium.de/sites/net/1909011.htm) | Erklärt Aufbau und Funktionsweise digitaler Schlüssel in kryptografischen Systemen. | ✅🌐💻🔐 |
| [Kryptografische Verfahren](https://www.elektronik-kompendium.de/sites/net/2006261.htm) | Überblick über gängige kryptografische Algorithmen und ihre jeweiligen Einsatzbereiche. | 🌐💻🔐 |
| [Symmetrische Kryptografie](https://www.elektronik-kompendium.de/sites/net/1910101.htm) | Erklärt das Prinzip symmetrischer Verschlüsselung, bei der Sender und Empfänger denselben Schlüssel nutzen. | ✅🌐💻🔐 |
| [Asymmetrische Kryptografie](https://www.elektronik-kompendium.de/sites/net/1910111.htm) | Beschreibt das Public-Key-Verfahren mit getrennten Schlüsseln für Verschlüsselung und Entschlüsselung. | ✅🌐💻🔐 |
| [Hybride Verfahren](https://www.elektronik-kompendium.de/sites/net/1910141.htm) | Kombiniert symmetrische und asymmetrische Kryptografie, um deren jeweilige Vorteile zu verbinden. | 🌐💻🔐 |
| [SSL](https://www.elektronik-kompendium.de/sites/net/0902281.htm) | Erläutert das ältere SSL-Protokoll zur gesicherten Datenübertragung – Vorläufer von TLS. | ✅🌐💻🔐 |
| [TLS](https://www.elektronik-kompendium.de/sites/net/1706131.htm) | Erklärt TLS als modernen Nachfolger von SSL für verschlüsselte Kommunikation (z. B. HTTPS). | ✅🌐💻🔐 |
| [SSL/TLS Schwachstellen](https://www.elektronik-kompendium.de/sites/net/1906041.htm) | Beschreibt bekannte Angriffe und Schwachstellen in SSL/TLS-Implementierungen (POODLE, BEAST usw.). | 🌐💻🔐 |
| [PGP](https://www.elektronik-kompendium.de/sites/net/1810181.htm) | Erklärt PGP (Pretty Good Privacy) zur Ende-zu-Ende-Verschlüsselung von E-Mails und Dateien. | 💻🔐 |

## Firewall / Paketfilterung
- [Sebastian Philippi ACL Playlist](https://www.youtube.com/watch?v=zXZgsVPRqnw&list=PLCb8EhYsrW_tLYFnK17Yb_kaoCmqJ3Lzk)

---

| Link | Beschreibung | AP |
|---|---|:---:|
| [Firewall](https://www.elektronik-kompendium.de/sites/net/0803051.htm) | Überwacht und filtert den Netzwerkverkehr nach definierten Regelwerken zum Schutz vor unerlaubtem Zugriff. | ✅🌐🔐 |
| [DMZ](https://www.elektronik-kompendium.de/sites/net/0907241.htm) | Eine demilitarisierte Zone trennt öffentlich erreichbare Server vom internen Netzwerk durch zwei Firewalls. | 🌐🔐 |
| [Zero Trust](https://www.elektronik-kompendium.de/sites/net/2512031.htm) | Sicherheitsmodell, das grundsätzlich keinem Nutzer oder Gerät vertraut und jede Anfrage einzeln prüft. | 🌐💻🔐 |
| [Deep Packet Inspection](https://www.elektronik-kompendium.de/sites/net/1408271.htm) | Analysiert den vollständigen Inhalt von Datenpaketen (inkl. Nutzdaten), um unerwünschten Traffic zu erkennen. | 🌐🔐 |
| [Stateful Packet Inspection](https://www.elektronik-kompendium.de/sites/net/1409291.htm) | Prüft Pakete im Kontext bestehender Verbindungen und bietet mehr Sicherheit als einfache Paketfilter. | 🌐🔐 |

## VPN
- [Sebastian Philippi VPN Playlist](https://www.youtube.com/watch?v=uAgbCoc-s7A&list=PLCb8EhYsrW_vtL-fKFr3lnJJ2yYPNFS6y)

---

| Link | Beschreibung | AP |
|---|---|:---:|
| [VPN Grundlagen](https://www.elektronik-kompendium.de/sites/net/0512041.htm) | Erklärt das Konzept virtueller privater Netzwerke und deren typische Einsatzzwecke. | ✅🌐🔐 |
| [VPN Tunnel](https://www.elektronik-kompendium.de/sites/net/1410141.htm) | Beschreibt, wie VPN-Tunnel verschlüsselte Verbindungen über öffentliche Netzwerke aufbauen. | 🌐🔐 |
| [WireGuard](https://www.elektronik-kompendium.de/sites/net/2502231.htm) | Modernes, schlankes VPN-Protokoll mit hoher Performance und besonders einfacher Konfiguration. | 🌐🔐 |
| [SSL-VPN](https://www.elektronik-kompendium.de/sites/net/1410151.htm) | VPN-Variante auf Basis von TLS/SSL, die ohne speziell installierte Client-Software auskommt. | 🌐🔐 |
| [OpenVPN](https://www.elektronik-kompendium.de/sites/net/1706181.htm) | Weit verbreitetes Open-Source-VPN auf Basis von TLS mit flexibler plattformübergreifender Konfiguration. | 🌐🔐 |
| [IPsec](https://www.elektronik-kompendium.de/sites/net/0906191.htm) | Protokollsuite zur verschlüsselten und authentifizierten Kommunikation direkt auf IP-Ebene. | 🌐🔐 |

## System Hardening

| Link | Beschreibung |
|---|---|
| [Härten – Computer (Wikipedia)](https://de.wikipedia.org/wiki/H%C3%A4rten_(Computer)) | Erklärt das Konzept des System-Hardenings – gezieltes Absichern von Systemen durch Reduzierung der Angriffsfläche. |
| [OS Hardening (fb-pro.com)](https://www.fb-pro.com/os-hardening/) | Praxisorientierter Leitfaden zum schrittweisen Absichern von Betriebssystemen. |

## Virtualisierung
- [Stefan Macke Virtualisierung Video](https://www.youtube.com/watch?v=dcaJRPjI2QQ)

---

| Link | Beschreibung | AP |
|---|---|:---:|
| [Virtualisierung](https://www.elektronik-kompendium.de/sites/com/1101011.htm) | Erklärt das Konzept der Virtualisierung – die Abstraktion physischer Ressourcen in logische Einheiten. | ✅🌐💻 |
| [Virtuelle Maschine](https://www.elektronik-kompendium.de/sites/com/3003121.htm) | Beschreibt, was eine virtuelle Maschine ist und wie sie auf einem Hypervisor betrieben wird. | ✅🌐💻 |
| [Virtualisierung Computertechnik](https://www.elektronik-kompendium.de/sites/com/3003131.htm) | Erklärt Virtualisierungskonzepte speziell im Bereich der Computertechnik (Hardware-Ebene). | 🌐💻 |
| [Virtualisierung Prozessor](https://www.elektronik-kompendium.de/sites/com/3003141.htm) | Beschreibt, wie Prozessoren virtualisiert werden, um mehrere VMs gleichzeitig auszuführen. | 🌐💻 |
| [Vertikale Skalierung](https://phoenixnap.de/Glossar/vertikale-Skalierung) | Erklärt vertikale Skalierung (Scale-up) – das Erweitern der Ressourcen eines einzelnen Systems. | |

## Allgemeine Ressourcen

| Link | Beschreibung | AP |
|---|---|:---:|
| [FI-Forum OSI Modell Überblick](https://www.fachinformatiker.de/files/file/5-iso-osi-schichtenmodell/) | Übersichtliche Lernunterlage zu den sieben OSI-Schichten vom Fachinformatiker-Forum. | ✅🌐💻 |
| [FI-Forum USV Typen](https://www.fachinformatiker.de/files/file/9-usv-typen/) | Erklärt die verschiedenen Typen unterbrechungsfreier Stromversorgung (Offline, Line-Interactive, Online). | ✅🌐 |
| [FI-Forum Backup Formen](https://www.fachinformatiker.de/files/file/8-backup-formen/) | Überblick über Vollbackup, differentielles und inkrementelles Backup mit Vor- und Nachteilen. | ✅🌐💻 |
| [FI-Forum IPv4 und IPv6](https://www.fachinformatiker.de/files/file/40-ipv4-und-ipv6/) | Vergleich und Grundlagen der Adressierungskonzepte IPv4 und IPv6. | ✅🌐💻 |
| [FI-Forum Fachbegriffe Glossar](https://www.fachinformatiker.de/files/file/48-fachbegriffe-und-themen-kurzerklärung/) | Kompaktes Glossar mit kurzen Erklärungen wichtiger IT-Fachbegriffe für die Prüfungsvorbereitung. | ✅🌐💻 |

## Prüfungsvorbereitung
- [Stefan Macke AP1 Playlist](https://www.youtube.com/playlist?list=PLunzHF-cqEKNOpDGznc7SfT2cy8c2BXyj) ✅
- [Stefan Macke AP2 FIAE Prüfungsvorbereitung Playlist](https://www.youtube.com/watch?v=eQoC4GDzYbI&list=PLunzHF-cqEKMBkR6Jqg1YApkbJWEsy1gy)

---

| Link | Beschreibung | AP |
|---|---|:---:|
| [FI-Forum Prüfungskatalog 2025](https://www.fachinformatiker.de/files/file/33-prüfungskatalog-2025-auszug/) | Auszug des offiziellen Prüfungskatalogs 2025 für Fachinformatiker-Ausbildungen. | ✅🌐💻 |
| [FI-Forum AP1 Masterplan](https://www.fachinformatiker.de/files/file/44-ap1-prüfungsvorbereitung-masterplan/) | Strukturierter Lernplan mit allen relevanten Themen zur Vorbereitung auf die AP1-Prüfung. | ✅ |
| [FI-Forum AP1 Lernzettel](https://www.fachinformatiker.de/files/file/36-fachinformatiker-ap1-lernzettel-ab-2025/) | Kompakte Lernzettel mit den wichtigsten Inhalten für die AP1-Prüfung ab 2025. | ✅ |
| [FI-Forum AP2 FISI Masterplan](https://www.fachinformatiker.de/files/file/51-ap2-fisi-masterplan/) | Strukturierter Lernplan für alle relevanten Themen der AP2-Prüfung im Bereich Systemintegration. | 🌐 |
| [FI-Forum AP2 FISI Prüfungsvorbereitung](https://www.fachinformatiker.de/files/file/52-fisi-ap-2-prüfungsvorbereitung/) | Umfassende Prüfungsunterlagen und Übersichten für den AP2-Bereich FISI. | 🌐 |
| [FI-Forum AP2 FIAE Masterplan](https://www.fachinformatiker.de/files/file/50-ap2-fiae-masterplan-v10/) | Strukturierter Lernplan für alle relevanten Themen der AP2-Prüfung im Bereich Anwendungsentwicklung. | 💻 |
