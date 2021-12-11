Datensatz Semesterverbund CRPR2

Codebuch Stand 2021-12 erstellt von Florian Striegl, Julia Dusemond, Lina Quotschalla, Pascal Eichner und Jessica Schreiner
Inhalt

    Edges_Selfmadewomen.csv (Edgelist)
    Nodes_Selfmadewomen.csv (Nodelist)
    Codebuch_Selfmadewomen.md (Codierung der Datensätze)

Ursprung und Datenerhebung

Wir haben den Datensatz aus der Forbes-Liste der Self-Made-Women 2021 erhoben. Für unser Projekt analysieren wir die Top 25 und deren Investments, Stiftungen und Beteiligungen??

Das Netzwerk ist ein ungerichtetes one-mode Akteursnetzwerk.

id
(eindeutige Codierung des Knoten)
codiert von 1 bis ??, jede ID entspricht einer Self-Made-Women

weight
Beziehungsstärke aufgrund der Nennung in den Fragen)
3 = sehr starke Beziehung (erste Nennung),
1 = starke Beziehung vorhanden (zweite Nennung)

investment (Wird gemeinsam in etwas investiert?)
1 = Ja, gemeinsames Investment
2 = Nein, kein gemeinsames Investment

complicated
1 = Beziehung (typische Paarbeziehung, d.h. reziprok zwischen beiden PartnerInnen),
2 = Tinder-Like (hat die person rechts geswiped, muss aber nicht gegenseitig sein)
3 = Crush (einseitig verliebt, ohne dass die Person etwas davon weiss).

NODE-Attribute

id
Identische ID wie aus der edgelist zur Identifikation der Knoten. In diesem Fall sind alle personenbezogenen Daten anonymisiert von 1 bis 25.

name numerische ID

name_first Vorname abgekürzt, z.B. für Visualiserung, falls der Name zu lange ist

net worth
Vermögen in $

state
Name Us-Staat

source
Sektor der sie berühmt gemacht hat

age_real
Alter in natürlichen Zahlen.

age
Bitte geben Sie Ihr Alter an:
1 = 32 bis 40 Jahre
2 = 41 bis 50 Jahre
3 = 51 bis 60 Jahre
4 = 61 bis 70 Jahre
5 = 71 bis 80 Jahre
6 = über 80 Jahre
