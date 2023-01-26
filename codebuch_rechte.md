# Datensatz Rechte Parteien innerhalb der EU #
Codebuch Stand 2023-01
erstellt von Florian Frankenhuis (ff059@hdm-stuttgart.de)

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung

Das Netzwerk soll die Vernetzung der rechten Parteien innerhalb der EU darstellen.



# EDGE-Attribute

**from**
Initiierender Knoten


**to**
erhaltender Knoten

**relation**
Beziehungsart 
1 = Persönlicher Kontakt
2 = Mitglied der Partei
3 = Intellektueller Austausch
4 = Finanzielle Unterstützung
5 = Gegenseitige Werbung

**weight**
Beziehungsstärke
1 = Intensive Beziehung
2 = Gute Beziehung
3 = Oberflächliche Beziehung


# NODE-Attribute  
  
**id**  
Eindeutige Kodierung des Knotens: Initialen der Person bzw. der Partei

**id**  
Klarname

**type** 
1 = Rechtsextreme Parteien in Regierung/nationalen Parlamenten
2 = Parteiangeörige
3 = Internationale Versammlungen/Kongresse im rechtem Milieu

**party** 
Parteizugehörigkeit

**role** 
Art der Beteiligung
1 = Beteiligung an der Regierung
2 = In der Opposition

**country** 
Nationalität
##


**Zeitplan**
Eventuelle Aufteilung nach der ersten Recherche: Weitere Konkretisierung und Aufteilung

heute bis 04.02.: Vorrecherche und Pretest
05.02. - Ende Februar: Recherche und Datenerhebung, parallel Aktualisierung Edge- und Nodelist
08.03. Abgabe Datensatz

