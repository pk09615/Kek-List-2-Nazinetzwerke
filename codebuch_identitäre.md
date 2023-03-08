# Datensatz Rechte Parteien innerhalb der EU #
Codebuch Stand 2023-01
erstellt von Florian Frankenhuis (ff059@hdm-stuttgart.de)

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung

Das Netzwerk soll die Vernetzung der rechten Parteien innerhalb der EU darstellen.



# Node-Attribute

id: Eindeutige Kodierung des Knotens: Initialen der Person bzw. der Partei				
name: Klarname				
				
Sector: In welchem Bereich die Personen tätig sind (außerhalb ihrer Beteiligung in der Identitären)				
1: Politik auf europäischer Ebene				
2: Politik auf nationaler Ebene				
3: Politik auf regionaler Ebene				
4: Medien- und Publizistik				
5: Nicht bekannt				
6: Wirtschaft				
				
party: Parteizugehörigkeit (auf nationaler Ebene)				
afd	Alternative für Deutschland			
fpö	Freiheitliche Partei Österreichs			
rn	Rassemblement National			
				
role: Art der Beteiligung				
1: Gründer von der ganzen IB auf nationaler Ebene (heute noch aktiv)				
2: führende Mitglieder: Obere Führer				
3: aktive Mitglieder: Bestätigtes Mitglied				
4: Sympathisanten: Im realen Leben				
5: Sympathisanten: Auf Social Media/Propaganda/Spendenaufrufe				
6: Förderung von Mitgliedern				
				
country: Nationalität				
				
Ereignis: Demonstration/Versammlung ausschließlich von der Identitären organisiert (nur für den Ort, ab 4/5 Personen)				
				
				
# Edge-Attribute			
from: initiierender Knoten				
to: erhaltender Knoten				
				
relation: Beziehungsart				
1: Interaktion: Definierung über Weight				
2: Finanzielle Unterstützung				
3: Mitglied der Partei				
4: Förderung (Beschaffung von Arbeitsplätzen)				
5: Anwesenheit				
				
				
weight: Beziehungsstärke				
1: Familie (Verwandschaft & Verheiratet)				
2: Intensive Beziehung (Öftere Treffen, Kaffee trinken, Intensiver Austausch, Vertrauensverhältnis)				
3: Gute Beziehung (Gelegentliche Treffen, Austausch)				
4: Oberflächliche Beziehung (einmalige Interaktion, im realen Leben (z.B. Foto, mündl. Verteidigung von IB-Mitgliedern), auf Social Media (z.B. Tweet, einmaliger (Re-)Post, schriftl. Verteidigung von IB-Mitgliedern)				
5: Spendenverhätnis				
6: Keine Beziehung		
