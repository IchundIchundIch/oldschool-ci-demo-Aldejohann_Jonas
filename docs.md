# Dokumentation – OldSchool CI Demo

## Was macht das Dockerfile?
Das Dockerfile erstellt einen Docker-Container auf Basis von Alpine Linux.
Es kopiert ein Shell-Skript in den Container, macht es ausführbar und legt fest,
dass dieses Skript beim Start des Containers ausgeführt wird.

## Was ist der Zweck der Pipeline?
Die Pipeline automatisiert das Bauen und Testen der Anwendung.
Bei jedem Push wird das Docker-Image gebaut, ein Container gestartet
und überprüft, ob die erwartete Konsolenausgabe erscheint.

## Was war der schwierigste Teil dieser Aufgabe und warum?
Zu erkennen dass man mit Git Desktop nichts hinbekommt
