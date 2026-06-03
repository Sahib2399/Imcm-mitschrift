# IMCM-Mitschrift
 
Das ist die README.md-Datei. med steht für Markdown. Markdown ist eine im Internet weit verbreitete Auszeichnungssprache (*Markup-Language*)
 
- HTML (Hypertext Markup Language)
- XML (Extensible Markup Language)
- YAML, YML (Yet Another Markup Language)
 
## Playlist zur Funktionsweise des Internets
 
### Teil 1 - What is the Internet?
 
- wurde in den 1970er-Jahren erfunden
- Motivation: schaffung eines dezentralen Netzwerks das auch noch nach einem Atomschlag noch funktioniert (Kontext des Kalten Krieges)
- Funktionsweise: Paketvermittlung (*Packet Switching*) - jedes Datenpaket sucht sich eine eigene Route durch das Netzwerk
- Internet: das Netz der Netze - besteht aus vielen kleinen Netzen unterschiedlicher Internetanbietern (*Internet Service Provider - ISP*, z.B.: A1, Magenta, Salzburg AG, ...)
 
### Teil 2 - The Internet: Wires, Cables & Wifi
 
- Informationen werden im Internet als Bits übertrage.
- Bits haben zwei Werte: 0 oder 1.
- 8 Bits ergeben 1 Byte. Mit einem Byte kann man 256 verschiedene Werte speichern (2^8).
 
- Bits können über verschiedene Übertragungsmedien zwischen Computern versendt werden.
- Die Anzahl der Übertragenen Bits pro Sekunde wird als Bandbreite bezeichnet - z.b.: 300MBit/s -> 300 Millionen Bit können pro Sekunde über diese Leitung laufen.
- Die zwei Hauptübertrager sind :
 
1. Kupfer / Elektrizität
    - billig
    - einfache Verarbeitung
    - weit verbreitet
    - hohe Verluste über lange Distanzen (hunderte Meter)
 
 
2. Glasfaser / Licht
    - teuer
    - schwierige Verarbeitung
    - schnelle Übertragung
    - verlustfrei
    - geeignet für Ozeankabel
 
3. Funk / Radiowellen
    - hoher Komfort, Internet überall
    - hohe Verluste über Distanzen
 
### Teil 3 - The Internet: IP-Adressen ß DNS
 
    - protokolle sind die Regel der Kommunikation
    - eines der wichtigsten Protokolle im Internet ist das Internet Protocoll (IP)
    - jedes Gerät im Internet hat zumindest eine (eindeutige) IP-Adresse, viele Geräte haben aber eine externe IP (ähnlich wie die      Raumnummer)
    - das Domain name system (DNS) übersetzt menschenlesbare Domainnamen (z.B.: www.google.com) in IP Adressen
    - DNS server führen Tabellen mit Domainnamen und den entsprechenden IP-Adressen
 
### Teil 4 - The Internet: Packets, Routing and Reliability
    - daten die Über das Internet versendet werden, werden in Pakete aufgeteilt
    - pakete sind in der Regel rund 1500 Byte groß (= 1.5 KB). Das heißt 10 MB großes Foto würde in etwa 6667 Pakete aufgeteilt werden (10MB = 10.000 KB = 10.000.000 Byte / 1500 Byte = 6667 Pakete)
    - pakete können unterschiedliche ruten durch das Internet nehmen, die Rutenplanung erfolgt durch spezielle Computer - Router. Router entscheiden welchen Weg ein Paket durch das Internet nimmt. Die Entscheidung basiert auf verschiedenen Faktoren, wie z.B. der aktuellen Auslastung der Verbindungen und der Entfernung zum Ziel.
    - jedes Paket enthält die IP-Adressen der Quelle und des Ziels spwie die Reihenfolge der Pakete (damit sie am Ziel wieder korrekt zusammengesetzt werden können)
