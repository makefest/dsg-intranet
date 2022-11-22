# HumHub

wikipedia: https://de.wikipedia.org/wiki/Humhub
website: https://www.humhub.com/de

Wir haben eine Testinstanz. Zugang bei Interesse bitte erfragen.

## Ergebnisse

- eine detaillierte Anforderungsanalyse steht noch aus, aber HumHub bietet viele relevante Funktionen und macht einen sehr guten Eindruck
- HumHub ist eher minimalistisch gehalten, aber dafür sehr übersichtlich und leicht zu bedienen
- es gibt keine native mobile App, aber man kann HumHub als [Progressive Web App](https://de.wikipedia.org/wiki/Progressive_Web_App) (PWA) auf dem Smartphone installieren.
- meine Versuche unter iOS push-Benachrichtungen der PWA zu erhalten waren bisher leider erfolglos; dies wäre nice-to-have, ist aber verzichtbar

## Login erzwingen

Derzeit landet man für intranet.dsgenf.ch auf der login Seite, wenn man nicht authentifiziert ist. Es gibt ja die Option, Spaces anzulegen, die auch Benutzer sehen können, die nicht angemeldet sind. Das legt nahe, dass es eine Einstellung gibt, den login zu erzwingen. Beim Anlegen eines neuen Spaces gibt es aktuell nur die beiden Optionen "Öffentlich (Nur Mitglieder)" und "Privat (unsichtbar)". Vermutlich ist die Option anonymer Sichtbarkeit ausgeschaltet. 

Bestätigt, s. [hier](https://docs.humhub.org/docs/user/user-management/) für das Erlauben von Gast-Zugang. Gäste landen auf dem sogenannten Dashboard. Dort werden allerdings Spaces gelistet, die nicht privat sind, also auch solche, die nur für registrierte Nutzer zugänglich sind. Aktuell wird also die Existenz solcher Spaces für  Gäste nicht verborgen, was u.U. wünschenswert sein könnte.

❓ kann man das Dashboard anpassen? Ja, s. [hier](https://docs.humhub.org/docs/admin/config-options/): "hideActivitySidebarWidget - Hides the activities sidebar widget. "

## Gäster auf andere Seiten als das Dashboard weiterleiten

https://github.com/humhub/custom-pages/issues/23

## Zugriff auf Benutzerprofile durch Gäste

Benutzer können dies konfigurieren, s. [hier](https://github.com/humhub/humhub/issues/787). Wichtiger ist, dass der Default global konfiguriert werden kann, s. [hier](https://docs.humhub.org/docs/user/user-management/).
