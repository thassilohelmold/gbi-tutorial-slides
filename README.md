# Grundbegriffe der Informatik – Tutoriumsfolien

WICHTIG: Dieses Repository enthält Materialien, die ausschließlich für Tutoren der Veranstaltung „Grundbegriffe der Informatik“ am KIT gedacht sind.
Daher dürfen diese Quellen und Rohmaterialien insbesondere nicht den Tutanden oder anderen Personen zugänglich gemacht werden!
Vielen Dank für euere Mitarbeit!

**Verwendung**:
Zunächst muss eine aktuelle Version des KIT-Themes installiert werden, siehe dazu das KIT-Vorlagen-Archiv im Ordner `Documents`. Es wird zwar eine leicht modifizierte Variante des KIT-Themes verwendet, diese greift aber trotzdem noch auf gewisse KIT-Packages zu, da das vollständige Entfernen aller Abhängigkeiten ein hoher (unnötiger) Aufwand wäre.

Anschließend muss eine Kopie der `config_template.tex` als `config.tex` abgespeichert werden.
Bitte alle persönlichen Modifikationen in dieser `config.tex` vornhemen **und die Datei nicht ins Git einchecken**!

Wenn ihr Fragen habt, stellt sie gerne im Tutoren-ILIAS im entsprechenden Thread oder direkt an Thassilo/Daniel.

### FAQ
1. _Ich verwende eure Folien als Grundlage für meine eigenen. Ist das für euch ok?_  
 Ja, das Material darf beliebig weiterverwendet und modifziert werden. Aber wenn du Fehler findest, sei so lieb und sag uns Bescheid. Danke! :o)
2. _Da sind komische LaTeX-Tags, die ich nicht kenne. Hilfe!_  
 Ja, Standard-LaTeX ist ziemlich mickrig und umständlich, weshalb wir es etwas aufgepeppt haben. :D  
 Viele Sachen sind selbsterklärend, wenn man sie im Einsatz sieht, ansonsten lohnt sich ein Blick in die `PraeambelTut.tex` bzw. `Style_Tut.tex`. (Einige Dinge sind auch aus Herrn Worschs Feder übernommen worden, siehe `gbi-macros.tex`.)  
 Viele dieser LaTeX-Kommandos sorgen dafür, dass die Folien überwiegend das hervorragende Vorlesungsdesign und dazugehörige typografische Standards matchen und die Tutanden somit weniger verwirrt sind und weniger Probleme haben, den Stoff zu verstehen, weshalb wir schwer empfehlen, diese Features zu nutzen. :)  
 Die `\thasse{}`-, `\daniel{}`- und `\thassedaniel{}{}`-Tags geben verschiedene Versionen für Formulierungen und andere Sachen an; nicht wundern, wenn bei euch nur die „Thasse“- oder nur die „Daniel“-Variante angezeigt wird. Ihr könnt es ja nach eurem Belieben ändern.
3. _Was ist mit dem KIT-Logo?_  
 Das Logo kann aus dem Theme herausgenommen werden, da die offiziellen Logorichtlinien eine Verwendung durch Tutoren eigentlich nicht vorsehen und das Logo eine geschützte Marke ist. Wer es _unbedingt_ für nötig hält, sich daran halten zu müssen, kann in der `config.tex`-Datei die entsprechende Zeile anpassen. ;-) (Standardmäßig ist das Logo drin.)

