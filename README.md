wp-ticketsystem
===============

Installation
------------
Plugin zip-Datei in den Wordpress-Plugin-Ordner entpacken und im Wordpress-Backend aktivieren.

Eine extra Seite anlegen auf welcher die einzelnen Tickets angezeigt werden sollen, in den Inhaltsbereich folgenden Shortcode eintragen:
```html
[wp_ticketsystem_single /]
```
Diese Seite auf der Plugin-Einstellungsseite auswählen und speichern.



Shortcodes
------------
+ **Ticketformular:** `[wp_ticketsystem_form excl="{TypeID}" /]`
+ **Ticketformular:** `[wp_ticketsystem_list excl="{TypeID}" /]`
+ **Ticketformular:** `[wp_ticketsystem_single /]`
+ **Ticketverlinkung:** `@#{TicketID}` (in Seiten, Beiträgen, Tickets, Ticketkommentaren & bbPress-Foren-Beiträgen)


Changelog
------------
**1.0 stable**
+ eigene Tickettypen erstellen
+ Tickettypen an- und abschalten
+ Ticket Sidebar-Widget
+ neue Einstellungsmöglichkeiten im Backend
+ Tickets bearbeiten
+ Duplikate zusammenführen
+ Kommentare zu extra Tickets machen
+ Dashboard-Widget vereinfacht
+ Shortcodes angepasst
+ Einstellungsmöglichkeiten für Shortcodes
+ 

**0.5 alpha**
+ Shortcodes für Ticketformular, Ticketliste, Ticketeinzelansicht
+ Einstellungsseite & Ticketübersichtsseiten
+ Dashboard-Widgets
+ Ticketverlinkung in Seiten, Beiträgen, Tickets, Ticketkommentaren & bbPress-Foren-Beiträgen
