#KVB Rad


Die Webapplikation soll die Benutzung von Wegen in Köln auf Basis der [Standorte Fahrradverleih Koeln - KVB-Rad](http://www.offenedaten-koeln.de/dataset/standorte-fahrradverleih-koeln-kvb-rad) mit dem Fahrrad verdeutlichen. Hierzu werden die Standorte der KVB-Fahrräder periodisch gespeichert und die Wege zwischen zwei gespeicherten Standorten über [Graphhopper](https://graphhopper.com/) auf Basis der OSM Daten geroutet. Die Ergebnisse des Routings werden in Teilabschnitte aufgetrennt. Durch Zählen dieser Teilabschnitte läßt sich die Nutzungsintensität von bestimmten Wegen für die Fahrräder bestimmen.
Für diese Projekt  wird eine angepasste Version des [Bootleaf](https://github.com/bmcbride/bootleaf) Templates verwendet. 

## Services

Dieses Webapplikation beruht auf Services, die Informationen auslesen, persistieren, aufbereiten und analysieren:
- [kvbradlive](https://github.com/codeforcologne/kvbradlive)
- [kvbradpositions](https://github.com/codeforcologne/kvbradpositions) 
- [kvbradrouting](https://github.com/codeforcologne/kvbradrouting)
- [kvbradanalysis](https://github.com/weberius/kvbradanalysis)
- [graphhopper](https://graphhopper.com/)

## Entwicklungsstand

Dieser Service ist in Entwicklung.

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Dieses Werk ist lizenziert unter einer <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Namensnennung - Weitergabe unter gleichen Bedingungen 4.0 International Lizenz</a>.