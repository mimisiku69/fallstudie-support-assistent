# Fallstudie: KI-Assistent für einen Software-Support

Eine Fallstudie aus meiner Zeit als Software Trainer bei der FIO SYSTEMS AG in Leipzig (02/2026 bis 06/2026). Code und Inhalte des Assistenten gehören FIO. Deshalb steht hier kein Quellcode, sondern das Vorgehen.

## Ausgangslage

Das Support-Team beantwortete Kundenfragen zu einer webbasierten Software für die Immobilienvermarktung. Die Antworten standen in einem Produkthandbuch mit rund 600 Seiten als PDF. Das Handbuch hatte den Stand 2024. Neuere Funktionen fehlten darin.

Wer eine Antwort brauchte, suchte von Hand im PDF. Das kostete Zeit, und für neuere Funktionen gab es oft gar keine Fundstelle.

## Lösung

Ein KI-Assistent, den die Mitarbeitenden in normaler Sprache fragen können.

1. **Wissensbasis aufbauen.** Grundlage war das Produkthandbuch. Die Lücke zwischen 2024 und 2026 habe ich geschlossen: Eine Kollegin und ich haben unsere Hands-on-Produktschulungen aufgezeichnet und transkribiert. Diese Transkripte sind mit in den Assistenten eingeflossen.
2. **Eigene Oberfläche bauen.** Die Web-Anwendung habe ich mit agentischem Programmieren entwickelt, also im Dialog mit KI-Werkzeugen statt Zeile für Zeile von Hand.
3. **Menschen mitnehmen.** Parallel habe ich die Kolleg:innen aus Support und Onboarding in KI-Grundlagen und Prompting geschult. Außerdem habe ich im unternehmensweiten Arbeitskreis „KI Awareness“ mitgearbeitet und dort eine Umfrage erstellt und ausgewertet.

## Was die Anwendung kann

- Chat mit dem Assistenten, Antworten erscheinen fortlaufend während des Schreibens
- Anmeldung nur für freigeschaltete Mitarbeitende
- Admin-Bereich: Nutzer:innen einladen, deaktivieren und löschen
- Passwort vergessen und zurücksetzen
- Datenschutzerklärung und Hinweis zur Datenspeicherung
- Erklärung zur Barrierefreiheit mit Ausrichtung auf WCAG 2.1 AA

## Technik

- Oberfläche: React, TypeScript, Vite, Tailwind CSS, erstellt mit Lovable
- Backend: Supabase (Anmeldung, Datenbank, serverseitige Funktionen)
- Antworten: großes Sprachmodell über eine Programmierschnittstelle

## Meine Rolle

Konzeption, Aufbereitung des Wissens, Bau der Oberfläche und Schulung der Kolleg:innen. Ich habe den Assistenten von der Problemstellung bis zum Pilotbetrieb begleitet: Er lief als Testanwendung, die ausgewählte Mitarbeitende erprobt haben.

## Was ich daraus mitnehme

- Ein Assistent ist nur so gut wie seine Wissensbasis. Die eigentliche Arbeit steckt im Aufbereiten und Aktualisieren des Wissens.
- Technik allein reicht nicht. Ohne Schulung und Austausch im Team bleibt das Werkzeug ungenutzt.
- Datenschutz und Barrierefreiheit habe ich vor der breiteren Nutzung nachgerüstet. Beim nächsten Projekt plane ich sie von Anfang an ein.

## Kontakt

Ingo Günther, Leipzig. Mehr zu mir auf meinem [GitHub-Profil](https://github.com/mimisiku69).
