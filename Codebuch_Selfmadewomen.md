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
id der Frau, die in der Firma involviert ist

**to**
Company/Organisation, mit der die Frau eine Verbindung hat

**relation**
1 = Ownerin zu 100 % (alleinig)
2 = Anteile an der Firma
3 = Spenden an Organisation ab 500.000 US-Dollar
4 = Stiftung


## NODE-Attribute

**id**
Identische ID wie aus der edgelist zur Identifikation der Knoten.

**name** Ganzer Name

**type**
0 = Woman
1 = Company

**state**
Name US-Staat

**country**
Land mit Sitz der Firma bzw. Herkunft der Frau

**net worth**
Vermögen in Us-Dollar

**source**
Sektor der Firma (z.B. IT, ...)

**source_type**
1 = Baubereich
2 = IT
3 = Gastronomie-Sektor

**organisation** (Art der Firma)
1 = Partei
2 = Organisation, an die gespendet wird
3 = Stiftung
4 = Firma

99 = Frau, nicht def. Art der Firma

**invest**
Menge an US-Dollar, die investiert wurde

99 = nicht definiert

**age**
1 = 32 bis 40 Jahre
2 = 41 bis 50 Jahre
3 = 51 bis 60 Jahre
4 = 61 bis 70 Jahre
5 = 71 bis 80 Jahre
6 = über 80 Jahre

99 = Firma, nicht def. Alter

