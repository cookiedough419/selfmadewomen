# Datensatz Self-Made-Women

Codebuch Stand 2021-12 erstellt von Florian Striegl, Julia Dusemond, Lina Quotschalla, Pascal Eichner und Jessica Schreiner

## Inhalt

    Edges_Selfmadewomen.csv (Edgelist)
    Nodes_Selfmadewomen.csv (Nodelist)
    Codebuch_Selfmadewomen.md (Codierung der Datensätze)

## Ursprung und Datenerhebung

Wir haben den Datensatz aus der Forbes-Liste der Self-Made-Women 2021 erhoben. Für unser Projekt analysieren wir die Top 25 und deren Investments, Stiftungen und Beteiligungen an Firmen/Organisationen.

Das Netzwerk ist ein gerichtetes two-mode Akteursnetzwerk.


## EDGE-Attribute

**from**
id der Woman, die in der Firma involviert ist

**to**
Company/Organisation, mit der die Woman eine Verbindung hat

**relation**
1 = Owner 
2 = Anteile an der Firma
3 = Spenden
4 = Stiftung


## NODE-Attribute

**id**
Identische ID wie aus der edgelist zur Identifikation der Knoten. In diesem Fall sind alle personenbezogenen Daten anonymisiert von 1 bis 25.

**name** Vorname abgekürzt, z.B. für Visualisierung, falls der Name zu lange ist

**type**
0 = Women
1 = Company

**net worth**
Vermögen in $

**state**
Name Us-Staat

**source**
Sektor der Firma

**invest**???
Menge die investiert wurde?

**age_real**???
Alter in natürlichen Zahlen.

**age**??
Bitte geben Sie Ihr Alter an:
1 = 32 bis 40 Jahre
2 = 41 bis 50 Jahre
3 = 51 bis 60 Jahre
4 = 61 bis 70 Jahre
5 = 71 bis 80 Jahre
6 = über 80 Jahre

