### Vorlage für das Rom-Buch

#### Ablauf

* Teilnehmer stellen Ihren Beitrag. Die Regelungen für die Bezeichnungen finden sich in dem [ReadMe.md](https://github.com/ugroh/AGFA-Rom-Teilnehmer/blob/main/ReadMe.md) in der Vorlage für die Teilnehmer.

* das Unterverzeichnis `content-abcd` wird in das Unterverzeichnis `content` kopiert und via 

	  \input{./content/content-abcd/abcd-Beitrag}
	  
	wird es eingebunden.
	
*  Die `abcd-Biblio.bib` müssen in eine einzige Datei übertragen werden (muss dies nochmals prüfen). Diese findet sich in 

	\addbibresource{./bib/Rom-Biblio.bib}
	
	eingebunden. Für die Pflege der eigenen Bibliothek ist der Teilnehmer verantwortlich. 
	
*  Zu klären sind dann noch die verwendeten eigenen definitionen der Teilnehmer. Vielleicht ist es insgesamt besser, wenn man alle in eine Gesamtdatei überführt und diese prüft. 

#### Sonstiges

* Zur [Vorlage der Teilnehmer](https://github.com/ugroh/AGFA-Rom-Teilnehmer) 
* **TODO** Überarbeiten, damit alles kompakter wird.

<ulgr@math.uni-tuebingen.de>


