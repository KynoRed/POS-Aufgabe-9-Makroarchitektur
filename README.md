# POS-Aufgabe-9-Makroarchitektur

## Aufgabe - Makroarchitektur Teil 1 (Modulith + Theorie)
### A) Theorie: Recherchiere zu folgenden Fragestellungen und fasse deine Erkenntnisse übersichtlich und illustrativ zusammen!

Was ist Softwarearchitektur?
Softwarearchitektur ist nicht das, was im Handbuch steht, sondern das, was die klügsten Köpfe im Team im Kopf haben, wenn sie über das System nachdenken. Die andere Antwort möglichkeit wäre, Softwarerchitektur ist das, was für die Experten eines Teams am wichtigsten ist und sich später nur sehr schwer ändern lässt.

Wie kann man Softwarearchitektur dokumentieren?
Architecture Decision Record (ADR):
Anstatt nur das Ergebnis aufzuschreiben, hält man die Dokumentation dazu fest. Ein Architecture Decision Record (ADR) ist ein kurzes Textdokument, was die Problemstellung zusammenfässt, unsere Wahl was wir gewählt haben und was die Nachteile beziehungsweise die Kompromissen waren.

C4:
Nutze Diagramme, die man wie eine Landkarte zoomen kann (vom groben Kontext bis zum Detail-Code).
Context: Das System im Verhältnis zu Nutzern und anderen Systemen.
Containers: Die grobe Aufteilung (Web-App, Datenbank, API).
Components: Das Innenleben eines Containers.
Code: (Optional) Details wie Klassen-Diagramme.

arc42:
Nutze bewährte Vorlagen, um nur die wirklich wichtigen Aspekte (Ziele, Risiken, Bausteine) zu beschreiben.
Man nutzt nur die Teile, die für das Projekt „wichtig“ sind.
Tools wie PlantUML oder Mermaid erlauben es, Diagramme direkt im Code-Repository als Text zu speichern. So ändern sie sich mit dem Code mit.

Welches sind die wichtigsten Eigenschaften von Langlebigen Softwarearchitekturen (Lilienthal)


Was ist ein Modulith?

Wie funktioniert die Ports and Adapters Architektur?

DDD: Was sind die wesentlichen Bausteine des modellgetriebenen Entwurfs (Taktische Pattern) aus DDD?
