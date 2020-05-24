{\rtf1\ansi\ansicpg1252\cocoartf2511
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fmodern\fcharset0 Courier;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sl280\partightenfactor0

\f0\fs24 \cf2 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 # Codebuch Ego-Netzwerkanalyse\
\
Wir erstellen ein gerichtetes Ego-Netzwerk aus dem Namensgenerator und -interpretator. Fehlende Daten werden mit NA codiert. Die Daten sind aus Partnerinterviews entstanden. Sie erstellen ihr eigenes Ego-Netzwerk mit den Daten, die Ihr Interviewpartner erhoben hat.\
\
Grunds\'e4tzlich: bitte keine Sonderzeichen verwenden, keine Leerzeichen in den Datenfelder. Fehlende Werte freilassen oder mit NA codieren. Nicht vergessen, auch das Ego (also sich selbst) zu erheben. \
\
WICHTIG: die IDs von der Edgelist m\'fcssen mit den IDs der Nodelist genau \'fcbereinstimmen!\
\
### Edgelist\
F\'fcr die Edgelist m\'fcssen Sie die Beziehungen aus Abschnitt 2 und Abschnitt 3 als Edgelist erfassen.\
  \
from = ID des Knoten  \
to = ID des Knoten (Richtung)\
  \
*weight* \
Beziehungsgewicht f\'fcr Frage 2.1, codiert als   \
1 = weniger als ein Mal im Monat,  \
2 = mindestens ein Mal im Monat,  \
3 = mindestens ein Mal pro Woche,  \
4 = t\'e4glich.  \
\
*duration*  \
1 = weniger als drei Jahre,   \
2 = drei bis sechs Jahre,  \
3 = mehr als sechs Jahre.  \
  \
*relationship*  \
1 = Eltern oder Kinder (Verwandtschaft ersten Grades),  \
2 = Geschwister (Verwandtschaft ersten Grades),  \
3 = Verwandtschaft zweiten Grades (Onkel, Tante),   \
4 = Nachbarn,   \
5 = Arbeitskollege,   \
6 = Kommilitone,   \
7 = Mitglied in gleicher Gruppe (Sport, Verein, Kirche, etc.),   \
8 = Ratgeber (z.B. Anwalter, Berater, Therapeut, spiritueller Beistand, etc.),   \
9 = feste Beziehung / Partnerschaft.\
  \
## Nodelist\
Die Nodelist erfasst alle soziodemographischen Daten. Dazu geh\'f6ren auch ihre eigenen ;-).\
\
*ID*  \
ID muss identisch zur Edgelist sein (z.B. Name, Abk\'fcrzung, etc.)\
\
*sex* (Geschlecht)  \
1 = weiblich,  \
2 = m\'e4nnlich,  \
3 = divers,  \
\
*ethnicity* (Herkunft)  \
1 = deutsch,   \
2 = Mittel/Osteuropa (auch UK),  \
3 = S\'fcdeuropa,  \
4 = Asien, \
5 = Skandinavien,  \
6 = S\'fcdamerika,  \
7 = Nordamerika,  \
8 = Russland,  \
9 = Afrika  \
\
*age*  \
1 = unter 18,  \
2 = 18 bis 25,  \
3 = 26 bis 34,   \
4 = 35 bis 64,  \
5 = \'fcber 64.  \
  \
*religion*  \
1 = evangelisch/protestantisch,  \
2 = katholisch,  \
3 = j\'fcdisch,  \
4 = muslimisch,  \
5 = buddhistisch,  \
6 = orthodox,  \
7 = andere,  \
8 = keine.  \
  \
*education*\
1 = Hauptschule,  \
2 = Mittlere Reife,  \
3 = Fachhochschulreife,  \
4 = Abitur,  \
5 = Studium,  \
6 = Promotion,  \
7 = weiss nicht.\
}