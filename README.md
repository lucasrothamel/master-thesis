# Optimierung der automatisierten Bereitstellung von Zügen im Eisenbahnbetriebsfeld Darmstadt
Optimisation of the automated provision of trains in the Eisenbahnbetriebsfeld (Railway Operations Lab) Darmstadt


My Master Thesis, written in 2015, at the Eisenbahnbetriebsfeld Darmstadt
 
 
## Implementation Highlights:

![Screenshot](https://raw.githubusercontent.com/lucasrothamel/master-thesis/master/gfx/screenshot.png)
![Timetable Display](https://raw.githubusercontent.com/lucasrothamel/master-thesis/master/gfx/path/zwl.png)


## Abstract
The Eisenbahnbetriebsfeld Darmstadt is a simulation lab for railway operations based on a model railway, on which different seminars take place. Before a seminar, the required trains need to be driven to their respective starting tracks. The existing semi-automatic provision of trains require an active technician, and it can take a considerable amount of time until all trains have been provisioned on their needed tracks.
Goal of this work is to develop a new automatic provision tool. This shall require as few interventions of the technician as possible whilst shortening the required driving time. For this, the lab was accurately surveyed, such that precise, conflict-free timetables for provision can be calculated. Many specific properties of the EBD were exploited in order to calculate good solutions for this NP-Complete Problem. A new driving controller was implemented which can drive a given timetable considerably faster than the existing, realistic driving controller. In the process it drops or reduces some side constraints present in real railway operations, which can in turn be dropped or removed from the side constraints of a valid timetable.
The combination of timetable calculation and new driving controller has proven to be fast and reliable. Only few interventions are necessary, for example to fix derailments, otherwise the software is working independently. At the same time, usually a considerable time saving is measurable against the existing semi-automatic provision solutions, for more complex provisions often the time required is nearly halved.

## Kurzfassung
Das Eisenbahnbetriebsfeld Darmstadt (EBD) ist eine Simulationsanlage für den Eisenbahnbetrieb basierend auf einer Modelleisenbahn, auf der unterschiedlichste Seminare stattfinden. Vor Beginn eines Seminars müssen die benötigten Züge auf die Startgleise des zu fahrenden Fahrplans gefahren werden. Die hierfür bereits existierenden Halbautomatiken benötigen einen durchgehend aktiven Fahrdienstleiter und es dauert relativ lange, bis alle Züge auf ihren Startgleisen bereitgestellt sind.
Ziel dieser Arbeit ist es, eine neue Bereitstellungs-Automatik zu entwickeln, welche mit möglichst wenigen Eingriffen seitens des Fahrdienstleiters und mit deutlich kürzerer Fahrzeit die Züge auf ihre Startgleise fährt. Hierzu wurde die Anlage genau vermessen, um präzise, konfliktfreie Fahrpläne zur Bereitstellung berechnen zu können. Viele spezifische Eigenschaften des EBD werden vom Fahrplanalgorithmus ausgenutzt, um für dieses grundsätzlich NP-Vollständige Problem gute Lösungen zu berechnen. Eine neue Fahrsteuerung wurde implementiert, welche einen berechneten Fahrplan deutlich schneller abfahren kann, als dies mit der existierenden, realistischen Fahrsteuerung möglich ist. Da mit der neuen Fahrsteuerung einige Nebenbedingungen des realen Eisenbahnverkehrs entfallen oder abgeschwächt werden, werden entsprechend auch einige Nebenbedingungen an einen gültigen Fahrplan abgeschwächt oder entfallen gänzlich.
Die Kombination aus Fahrplan-Berechnung und neuer Fahrsteuerung hat sich als schnell und zuverlässig erwiesen. Es sind nur noch wenige Eingriffe notwendig, beispiels- weise bei Entgleisungen, andernfalls arbeitet die Software eigenständig. Gleichzeitig ist meistens eine deutliche Zeitersparnis gegenüber den bisherigen Halbautomatiken messbar, bei komplexeren Bereitstellungen wurde der notwendige Zeitaufwand fast halbiert.

