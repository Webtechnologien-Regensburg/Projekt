---
title: Abschlussprojekt Webtechnologien SS20
author: Alexander Bazo, Martin Kocur
documentclass: scrartcl
classoption:
  - a4paper
header-includes: |
    \usepackage{german}
	\usepackage{xcolor} 
    \usepackage[a4paper,left=2.5cm, right=2.5cm,top=2.5cm, bottom=3cm]{geometry}
    \usepackage{fancyhdr}
    \pagestyle{fancy}
    \fancyhf{}
    \rhead{Webtechnologien}
    \lhead{Projekt}
    \fancypagestyle{plain}{
      \fancyhf{}
      \rhead{Webtechnologien}
      \lhead{Projekt}}


---



## Aufgabenstellung: William Shakespeare - Hamlet

Im Rahmen Ihres Abschlussprojektes implementieren Sie eine Webanwendung, die der Erfassung und Darstellung des Dramas "Hamlet" von William Shakespeare dient. Zur Implementierung des Projekts setzen Sie die im Kurs erworbenen Fähigkeiten und die dort besprochenen Technologien ein. Das Projekt muss bis zum 30. September abgegeben werden.



## Anforderungen

Das wesentliche Ziel des Projektes ist es, die im JSON-Format bereitgestellten Daten zum Drama "Hamlet" in das System einzupflegen und im Anschluss für den/die Nutzer/in – aufbereitet – zugänglich zu machen. Die zu implementierende Anwendung erfüllt dazu drei Funktionen: 

(1) Über eine entsprechende graphische Schnittstelle können Nutzer/innen das Drama um zusätzliche Informationen ergänzen. So können z.B. Textpassagen markiert und kommentiert werden. 

(2) Die Informationen zu Hamlet werden dem/der Nutzer/in strukturiert, d.h. nach Akten und Szenen sortiert angezeigt und zugänglich gemacht.

(3) Als Nutzer/in können Sie einen Überblick über die Akte und die die am Akt und an den Szenen beteiligten Charakter erhalten.  Darüber hinaus geben Diagramme Aufschluss über die jeweiligen Sprechanteile der Charaktere und die Anzahl der Wörter des jeweiligen Aktes. 

## Technischer Rahmen

Die Implementierung der Anwendung erfolgt auf der im Kurs gelernten Technologien. Die relevanten Daten werden in einer SQLite-Datenbank
gespeichert. Zur Gestaltung der Benutzeroberfäche verwenden Sie HTML & CSS. Die graphische
Aufbereitung auf der Übersichtsseite erfolgt mit der Javascript-Bibliothek Chart.js
[http://www.chartjs.org/].  Bitte reichen Sie bei Abgabe die erstelle und befüllte Datenbank mit
ein.



## Beschreibung der Datengrundlage

Die Datenbasis umfasst das Drama "Hamlet" im JSON-Format. 



## Skizzen der Benutzeroberfläche

Die folgenden Skizzen beschreiben die wesentlichen Bestandteile der Benutzeroberfläche. Bei
der Implementierung der Anwendung müssen Sie sich an diesen Vorgaben orientieren. Bitte
beachten Sie dabei jedoch, dass die Skizzen die Struktur und den Inhalt der Benutzeroberfläche
beschreiben, nicht zwangsläufig deren finales oder vollständiges Aussehen.

![Home](Home.PNG){ height=8cm }

![Akte](Acts.PNG)

Achten Sie auf eine aussagekräftige Variablenbenennung und auf die Auslagerung von Methoden.



![Scenes](Scene.PNG){ height=8cm }



_Abgabekriterien:_

Laden Sie Ihre Lösung bis spätestens 26.7.2020 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch.  Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und verwenden Sie geeignete Formate:

- Aufgabe: Ihr gesamtes Projekt

Der Name der Zip-Datei ergibt sich aus dem Präfix „SL_WT_SS20“, der Nr. der Studienleistung, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **Projekt_WT_SS20_Max_Mustermann.zip**

