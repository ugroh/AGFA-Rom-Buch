# Vorlage für das Rom-Buch (Stand 2023/04/12)

## Ablauf

* Teilnehmer erstellen Ihren Beitrag mit den Regelungen für die Bezeichnungen, die sich in dem [README.md](https://github.com/ugroh/AGFA-Rom-Teilnehmer/blob/main/README.md) für die Teilnehmer findet. 

* Die Teilnehmer schicken ihren Beitrag als `content-abcd.zip` zu und dieses wird in dem Unterverzeichnis  `content` entpackt.

* Der Beitrag wird über  

	  \input{./content/content-abcd/abcd-Beitrag}
	  
	eingebunden.
	
*  Die `abcd-Biblio.bib` müssen in eine einzige Datei übertragen werden (muss dies nochmals prüfen). Diese findet sich in 

	\addbibresource{./bib/Rom-Biblio.bib}.
	
	Für die Pflege der eigenen Bibliothek ist der Teilnehmer verantwortlich (da werden wir aber noch eine separate Schulung machen müssen). 
	
## Sonstiges

* Hier findet sich die [Vorlage der Teilnehmer](https://github.com/ugroh/AGFA-Rom-Teilnehmer) 


## Updates

* 2023/04/12: Der »Aufschlag« für das Romseminar 2024 ist eingestellt inkl. des zugehörigen Posters.

* 2023/02/05  : Man kann nun wählen, ob man ein Rom-Buch als PDF haben will (dann fangen alle Beiträge auf einer ungeraden Seite an), oder ob man eine Online-Version haben will (kompakter). 

* 2023/02/04  : LuaLaTeX Unterstützung; man kann sowohl mit PDFLaTeX als auch mit LuaLaTeX die Datei kompilieren. Der Vorteil von LuaLaTeX ist es, dass alle Unicode-Charakter unterstützt werden.

<ulgr@math.uni-tuebingen.de>


