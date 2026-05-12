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
- [Zahlensysteme](#zahlensysteme)
- [IPv6](#ipv6)
- [IPv4](#ipv4)
- [Allgemeine Ressourcen](#allgemeine-ressourcen)
- [Prüfungsvorbereitung](#prüfungsvorbereitung)

---

## Legende Symbole
* ✅ = AP1 (Grundlagen)
* 🌐 = AP2 FISI (Netzwerk / Infrastruktur)
* 💻 = AP2 FIAE (Entwicklung / Software)
* 🔐 = Security / zusätzlich wichtig

## Grundlagen Netzwerktechnik
### Videos
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
### Videos
- [Sebastian Philippi Netzwerksicherheit Reloaded Playlist](https://www.youtube.com/watch?v=bF_u0vCfrl0&list=PLCb8EhYsrW_ukGeh-8uSkv5ktYM41fgfV)
- [Sebastian Philippi Verschlüsseln, Signieren, Korrektheit garantieren Playlist](https://www.youtube.com/watch?v=Lq5u4YsiY_s&list=PLCb8EhYsrW_tZQ4bRkoGz3XzHuExiDWuF)
- [Sebastian Philippi: Hashfunktionen](https://www.youtube.com/watch?v=ZWoqy_V2C3M)
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
### Videos
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
### Videos
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
### Videos
- [Professor Messer: Härtungstechniken Comptia Security+](https://www.youtube.com/watch?v=wXoC46Qr_9Q)
- [Ken Harris: Windows Hardening](https://www.youtube.com/watch?v=dP-qNXRrRpA)
---

| Link | Beschreibung |
|---|---|
| [Härten – Computer (Wikipedia)](https://de.wikipedia.org/wiki/H%C3%A4rten_(Computer)) | Erklärt das Konzept des System-Hardenings – gezieltes Absichern von Systemen durch Reduzierung der Angriffsfläche. |
| [OS Hardening (fb-pro.com)](https://www.fb-pro.com/os-hardening/) | Praxisorientierter Leitfaden zum schrittweisen Absichern von Betriebssystemen. |

## Virtualisierung
### Videos
- [Stefan Macke Virtualisierung Video](https://www.youtube.com/watch?v=dcaJRPjI2QQ)

---

| Link | Beschreibung | AP |
|---|---|:---:|
| [Virtualisierung](https://www.elektronik-kompendium.de/sites/com/1101011.htm) | Erklärt das Konzept der Virtualisierung – die Abstraktion physischer Ressourcen in logische Einheiten. | ✅🌐💻 |
| [Virtuelle Maschine](https://www.elektronik-kompendium.de/sites/com/3003121.htm) | Beschreibt, was eine virtuelle Maschine ist und wie sie auf einem Hypervisor betrieben wird. | ✅🌐💻 |
| [Virtualisierung Computertechnik](https://www.elektronik-kompendium.de/sites/com/3003131.htm) | Erklärt Virtualisierungskonzepte speziell im Bereich der Computertechnik (Hardware-Ebene). | 🌐💻 |
| [Virtualisierung Prozessor](https://www.elektronik-kompendium.de/sites/com/3003141.htm) | Beschreibt, wie Prozessoren virtualisiert werden, um mehrere VMs gleichzeitig auszuführen. | 🌐💻 |
| [Vertikale Skalierung](https://phoenixnap.de/Glossar/vertikale-Skalierung) | Erklärt vertikale Skalierung (Scale-up) – das Erweitern der Ressourcen eines einzelnen Systems. | |

## Zahlensysteme
### Videos
- [Stefan Macke: Zahlensysteme, Zweierpotenzen, Binärzahlen](https://www.youtube.com/watch?v=Tq69ov1Q1MI&list=PLunzHF-cqEKNOpDGznc7SfT2cy8c2BXyj&index=6)
- [Sebastian Philippi: Binärsystem einfach](https://www.youtube.com/watch?v=zVbCDlBc7AI)

## IPv6
### Videos
- [Sebastian Philippi: IPv6 Grundlagen Playlist](https://www.youtube.com/playlist?list=PLCb8EhYsrW_symL1qayFNWN1yXkUjNAFz)
- [Stefan Macke: IPv6](https://www.youtube.com/watch?v=9HJVbclAb-w&list=PLunzHF-cqEKNOpDGznc7SfT2cy8c2BXyj&index=16)
- [CCC FSCK 2026: 340 Sextillionen Gründe für IPv6](https://www.youtube.com/watch?v=hW_1T3bewm4)
---

### Adressen und Header

| Link | Beschreibung | AP |
|---|---|:---:|
| [IPv6 - Internet Protocol Version 6](https://www.elektronik-kompendium.de/sites/net/0812201.htm) | Grundlegende Einführung in IPv6 und dessen wesentliche Unterschiede zu IPv4. | ✅🌐 |
| [IPv6-Adressen](https://www.elektronik-kompendium.de/sites/net/1902111.htm) | Erklärt den Aufbau und die Struktur der 128-Bit-langen IPv6-Adressen. | ✅🌐 |
| [Schreibweise von IPv6-Adressen](https://www.elektronik-kompendium.de/sites/net/2003011.htm) | Beschreibt Notation, Kurzschreibweise und Regeln zur korrekten Darstellung von IPv6-Adressen. | ✅🌐 |
| [Vergabe von IPv6-Adressen (Präfix)](https://www.elektronik-kompendium.de/sites/net/2102161.htm) | Erklärt die präfixbasierte Adressvergabe und Subnetting in IPv6. | 🌐 |
| [IPv6-Address-Scopes (Gültigkeitsbereiche)](https://www.elektronik-kompendium.de/sites/net/2107111.htm) | Unterscheidet Link-Local, Unique-Local und globale Gültigkeitsbereiche von IPv6-Adressen. | 🌐 |
| [IPv6-Multicast](https://www.elektronik-kompendium.de/sites/net/2009221.htm) | Beschreibt das Multicast-Konzept in IPv6, das IPv4-Broadcast vollständig ersetzt. | 🌐 |
| [IPv6-Header und Extension Headers](https://www.elektronik-kompendium.de/sites/net/1902121.htm) | Erklärt den vereinfachten IPv6-Hauptheader und den flexiblen Erweiterungsheader-Mechanismus. | 🌐 |

### IPv6-Protokolle: SLAAC, DHCPv6, NDP, ICMPv6

| Link | Beschreibung | AP |
|---|---|:---:|
| [IPv6-Autokonfiguration](https://www.elektronik-kompendium.de/sites/net/2004011.htm) | Überblick über die automatische Adresskonfiguration ohne manuellen Eingriff in IPv6. | ✅🌐 |
| [SLAAC - Stateless Address Autoconfiguration](https://www.elektronik-kompendium.de/sites/net/1902131.htm) | Erklärt, wie IPv6-Geräte ohne DHCP-Server automatisch eine globale Adresse aus dem Router-Präfix ableiten. | 🌐 |
| [Privacy Extensions (IPv6)](https://www.elektronik-kompendium.de/sites/net/1601271.htm) | Beschreibt, wie zufällig generierte Schnittstellenkennungen die Privatsphäre bei SLAAC verbessern. | 🌐 |
| [DHCPv6 (Stateful Address Autoconfiguration)](https://www.elektronik-kompendium.de/sites/net/1902141.htm) | Zustandsbehaftete Adressvergabe in IPv6 durch einen DHCPv6-Server, analog zu DHCP in IPv4. | 🌐 |

### Dual Stack: Übergang IPv4 zu IPv6

| Link | Beschreibung | AP |
|---|---|:---:|
| [Address Selection (IPv6)](https://www.elektronik-kompendium.de/sites/net/2004021.htm) | Erklärt, wie ein Dual-Stack-Gerät zwischen IPv4 und IPv6 für ausgehende Verbindungen wählt. | 🌐 |
| [Übergangsverfahren von IPv4 auf IPv6](https://www.elektronik-kompendium.de/sites/net/1806031.htm) | Überblick über Mechanismen (Dual Stack, Tunneling, Translation) zur schrittweisen Migration. | ✅🌐 |
| [Dual Stack](https://www.elektronik-kompendium.de/sites/net/1904041.htm) | Betrieb beider Protokollversionen gleichzeitig auf einem Gerät als gängigste Übergangsstrategie. | ✅🌐 |
| [IPv6-Tunneling mit 6in4 / 6to4 / 6over4 / 4in6](https://www.elektronik-kompendium.de/sites/net/1904031.htm) | Erklärt Tunnelmechanismen, die IPv6-Pakete in einer IPv4-Infrastruktur transportieren. | 🌐 |
| [Dual Stack Lite (DS-Lite / DSlite)](https://www.elektronik-kompendium.de/sites/net/2010211.htm) | Übergangsverfahren, bei dem IPv4 des Kunden über das IPv6-Netz des Providers getunnelt wird. | 🌐 |
| [CG-NAT - Carrier Grade NAT](https://www.elektronik-kompendium.de/sites/net/2010221.htm) | Beschreibt die Mehrfachnutzung einer öffentlichen IPv4-Adresse durch viele Kunden beim Provider. | 🌐 |
| [Umstieg von IPv4 auf IPv6](https://www.elektronik-kompendium.de/sites/net/1905101.htm) | Praktischer Leitfaden zur Planung und Durchführung der Migration von IPv4 auf IPv6. | 🌐 |

## IPv4
### Videos
- [Sebastian Philippi: IPv4 verstehen Playlist](https://www.youtube.com/playlist?list=PLCb8EhYsrW_vHZDA_8UOtTNPXRQ33-mOr)
- [Stefan Macke: IPv4](https://www.youtube.com/watch?v=rDCzSppPDHw&list=PLunzHF-cqEKNOpDGznc7SfT2cy8c2BXyj&index=4)

---

### Adressen und Header

| Link | Beschreibung | AP |
|---|---|:---:|
| [IPv4 - Internet Protocol Version 4](https://www.elektronik-kompendium.de/sites/net/0811271.htm) | Grundlegende Einführung in IPv4, seine Eigenschaften und Funktionsweise im Netzwerk. | ✅🌐 |
| [IPv4-Adressen](https://www.elektronik-kompendium.de/sites/net/2011211.htm) | Erklärt den 32-Bit-Aufbau von IPv4-Adressen und die Einteilung in Netz- und Hostanteil. | ✅🌐 |
| [IPv4-Konfiguration](https://www.elektronik-kompendium.de/sites/net/2011091.htm) | Beschreibt die manuelle und automatische Konfiguration von IPv4-Netzwerkadressen. | ✅🌐 |
| [IPv4-Netzklassen](https://www.elektronik-kompendium.de/sites/net/2011221.htm) | Erklärt die historische Einteilung in Klasse A–E und deren jeweilige Adressbereiche. | ✅🌐 |
| [Subnetting](https://www.elektronik-kompendium.de/sites/net/0907201.htm) | Beschreibt die Aufteilung eines IP-Netzes in kleinere Teilnetze mittels Subnetzmaske. | ✅🌐 |
| [CIDR - Classless Inter-Domain Routing](https://www.elektronik-kompendium.de/sites/net/2011231.htm) | Erklärt die klassenlose Adressvergabe zur effizienteren Nutzung des knappen IPv4-Adressraums. | ✅🌐 |
| [IPv4-Header](https://www.elektronik-kompendium.de/sites/net/2011241.htm) | Beschreibt die Felder und die Struktur des 20-Byte-IPv4-Headers. | 🌐 |
| [IPv4-Multicasting](https://www.elektronik-kompendium.de/sites/net/1806041.htm) | Erklärt die Übertragung von Paketen an eine definierte Gruppe von Empfängern in IPv4. | 🌐 |

### IPv4-Protokolle: DHCP, NAT, ARP, ICMP

| Link | Beschreibung | AP |
|---|---|:---:|
| [DHCP - Dynamic Host Configuration Protocol](https://www.elektronik-kompendium.de/sites/net/0812221.htm) | Automatische Vergabe von IP-Adresse, Subnetzmaske, Gateway und DNS an Netzwerkclients. | ✅🌐 |
| [NAT - Network Address Translation](https://www.elektronik-kompendium.de/sites/net/0812111.htm) | Übersetzt private IP-Adressen in eine öffentliche Adresse und ermöglicht die gemeinsame Internetnutzung. | ✅🌐 |
| [ARP - Address Resolution Protocol](https://www.elektronik-kompendium.de/sites/net/0901061.htm) | Ermittelt zu einer bekannten IP-Adresse die zugehörige MAC-Adresse im lokalen Netzwerk. | ✅🌐 |
| [ICMP - Internet Control Message Protocol](https://www.elektronik-kompendium.de/sites/net/0901011.htm) | Überträgt Steuer- und Fehlermeldungen im IP-Netz, u. a. genutzt von Ping und Traceroute. | ✅🌐 |

## Allgemeine Ressourcen

| Link | Beschreibung | AP |
|---|---|:---:|
| [FI-Forum OSI Modell Überblick](https://www.fachinformatiker.de/files/file/5-iso-osi-schichtenmodell/) | Übersichtliche Lernunterlage zu den sieben OSI-Schichten vom Fachinformatiker-Forum. | ✅🌐💻 |
| [FI-Forum USV Typen](https://www.fachinformatiker.de/files/file/9-usv-typen/) | Erklärt die verschiedenen Typen unterbrechungsfreier Stromversorgung (Offline, Line-Interactive, Online). | ✅🌐 |
| [FI-Forum Backup Formen](https://www.fachinformatiker.de/files/file/8-backup-formen/) | Überblick über Vollbackup, differentielles und inkrementelles Backup mit Vor- und Nachteilen. | ✅🌐💻 |
| [FI-Forum IPv4 und IPv6](https://www.fachinformatiker.de/files/file/40-ipv4-und-ipv6/) | Vergleich und Grundlagen der Adressierungskonzepte IPv4 und IPv6. | ✅🌐💻 |
| [FI-Forum Fachbegriffe Glossar](https://www.fachinformatiker.de/files/file/48-fachbegriffe-und-themen-kurzerklärung/) | Kompaktes Glossar mit kurzen Erklärungen wichtiger IT-Fachbegriffe für die Prüfungsvorbereitung. | ✅🌐💻 |

## Prüfungsvorbereitung
### Videos
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
